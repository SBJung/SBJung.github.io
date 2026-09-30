# sbjung.github.io

Source for my personal site, live at **[sbjung.github.io](https://sbjung.github.io/)**.

Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. The layout
started from the [researcher](https://github.com/ankitsultana/researcher) template;
all of its files (`_layouts/`, `_sass/`, `css/`) now live in this repo, so there is
no `remote_theme` and no theme gem to install.

## Previewing changes locally

Always preview before pushing — see the deploy note below for why.

```bash
bundle exec jekyll serve
```

Then open **http://localhost:4000**. The site rebuilds automatically when you save a
file; reload the browser to see it. Generated output goes to `_site/` (git-ignored).

Add `--livereload` to have the browser refresh itself, or `--drafts` to include drafts.

## One-time environment setup

The site needs Ruby 3.x and Bundler. On this machine that is already installed via
`chruby` (Ruby 3.3.6), so only the last step is needed after a fresh clone:

```bash
bundle install
```

For a new machine:

1. Install a Ruby version manager and a stable Ruby — `chruby` + `ruby-install` on
   macOS, or your distro's equivalent on Linux:
   ```bash
   ruby-install ruby 3.3.6
   ```
2. Point your shell at it (`chruby ruby-3.3.6`) and confirm with `ruby -v`.
3. Install Bundler and the site's gems:
   ```bash
   gem install bundler && bundle install
   ```

## Deploying

Pushing to **`gh-pages`** (the default branch) triggers the GitHub Actions workflow in
[`.github/workflows/jekyll.yml`](.github/workflows/jekyll.yml), which builds the site
with this repo's `Gemfile` and deploys it to Pages:

```bash
git add -A && git commit -m "your message" && git push
```

**Pushing publishes** — the live site updates once the workflow finishes, usually a
minute or two. Watch it on the repo's **Actions** tab; a red X there means the site did
not update. That is why the local preview above matters: there is no staging step.

Because CI builds from `Gemfile.lock`, that file is committed. If you change the
`Gemfile`, run `bundle install` and commit the updated lockfile with it.

> **Note:** Pages must be set to **Settings → Pages → Source: GitHub Actions** for this
> workflow to deploy. The older "Deploy from a branch" mode builds with GitHub's own
> Jekyll 3.10 and fails on this repo's Jekyll 4 `Gemfile`.

## Editing the content

| What | Where |
| --- | --- |
| Homepage (bio, interests, research, projects) | `index.md` |
| Contact page | `contact.md` |
| Site title, URL, nav links, footer | `_config.yml` |
| Page shell — `<head>`, navbar, footer markup | `_layouts/default.html` |
| Styling | `_sass/_style.scss`, plus `vars.scss` (colors), `typography.scss`, `tables.scss` |
| Images, videos, CV | `assets/`, `CV_renewed.pdf` |

Nav links are defined as a `nav:` list in `_config.yml`. Accent color (hyperlinks) is
the `accent` variable in `_sass/vars.scss`.

Any new `foo.md` in the repo root becomes a page at `/foo`.

## License

[GNU GPL v3](LICENSE), inherited from the researcher template.

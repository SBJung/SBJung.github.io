---
layout: default
---

## About Me

<img class="profile-picture" src="assets/face.jpg">

Hi! I am a Mechanical Engineering master's student at Carnegie Mellon University.

You can find my source code on [GitHub](https://github.com/bk2dcradle/researcher).

## Research Interest

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam finibus ipsum ac erat aliquam dapibus. Vestibulum vehicula placerat ex, a consectetur odio pharetra quis. Mauris id urna ante. Fusce pharetra diam ac nisi aliquet, vel egestas ex iaculis. Pellentesque laoreet cursus tellus sed pellentesque. Praesent a rhoncus elit. Nunc ipsum nisl, consequat sit amet pretium quis, gravida id ipsum.

## Publications

1. F.Bar, J.Doe: Effects of having a placeholder of a name
2. S.Holmes, J.Watson: Consequences of living with a sociopath in London

## Projects

This is a [link](http://google.com). Something *italics* and something **bold**.

Here is a table

Year | Award | Category
-----|-------|--------
2014 | Emmy  | Won Outstanding Lead Actor in a miniseries or a movie
2015 | BAFTA | Nominated for Best Leading Actor for Sherlock
2014 | Satellite | Won Best Actor miniseries or television film

Here is a horizontal rule

---

Here is a blockquote

> To a great mind, nothing is little

<!-- ----------------------------------------------------------------------- -->
<!--                                 Project                                 -->
<!-- ----------------------------------------------------------------------- -->

<table class="project-table" style="width: 100%;">
  <tr onmouseout="project1_stop()" onmouseover="project1_start()" style="border: none;">
    <td style="padding:16px;width:25%;vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='project1_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/project1_video.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/project1_thumb.jpg' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:middle; border: none;">
      <a href="https://your-project-page.com">
        <span class="papertitle">🧠 Project Title: What It Does</span>
      </a>
      <br>
      <span class="authors">
        <strong>Sebin Jung</strong>, Your Collaborators
      </span>
      <br>
      <em>Your Venue</em>, Year
      <br>
      <div style="margin: 0;">
        <a href="#" class="btn btn-primary">Project Page</a>
        <a href="#" class="btn btn-info">arXiv</a>
      </div>
      <p>
        A short sentence explaining what your project is about.
      </p>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function project1_start() {
    document.getElementById('project1_video').style.opacity = "1";
  }
  function project1_stop() {
    document.getElementById('project1_video').style.opacity = "0";
  }
  project1_stop();
</script>





## References

* Foo Bar: Head of Department, Placeholder Names, Lorem
* John Doe: Associate Professor, Department of Computer Science, Ipsum

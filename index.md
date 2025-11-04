---
layout: default
title: Sebin Jung
---

## Hi there 👋

<img class="profile-picture" src="assets/surf.jpg">

I’m a Master’s student in Mechanical Engineering at Carnegie Mellon University. I’m currently part of the [Intelligent Control Lab](http://icontrol.ri.cmu.edu/) at the Robotics Institute, where I’m fortunate to be advised by Prof. [Changliu Liu](https://scholar.google.com/citations?user=vvzAfOwAAAAJ&hl=en). Before coming to CMU, I earned my B.S. in Mechanical Engineering from Kyungpook National University in South Korea. During my undergraduate years, I worked on autonomous driving research in the [VOICE Lab](https://sites.google.com/view/voice-lab), advised by Prof. [Kyoungseok Han](https://scholar.google.com/citations?user=CEEipNoAAAAJ&hl=en&oi=ao).


## Interests

My research interests lie at the intersection of control, machine learning, optimization, and robotics. I'm particularly interested in developing methods that enable robots to act both safely and intelligently in complex environments. Recently, my work has focused on combining safe control techniques with learning-based approaches to improve the performance and reliability of autonomous systems.


## Research
<!-- ---------------------------- Safe Koopman ----------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="research3_stop()" onmouseover="research3_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='research3_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/research/safe_koopman.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/research/safe_koopman.png' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a>
            <span class="papertitle">Whole-Body Safe Control of Robotic Manipulators with Koopman Neural Dynamics</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong>, Abulikemu Abuduweili, Jiaxing Li and Changliu Liu
            </span>
            <br>
            <em>Submitted to International Conference on Robotics and Automation(ICRA), 2026.</em>
            <br>
            <div>
              <!-- <a href="https://arxiv.org/pdf/2502.03132" class="btn btn-info"><strong>arXiv</strong></a> -->
              <a href="https://intelligent-control-lab.github.io/spark/" class="btn btn-info"><strong>Project Page</strong></a>
              <!-- <a href="https://www.youtube.com/watch?v=vIzeQ31YbCM" class="btn btn-info"><strong>Video</strong></a> -->
            </div>
          </div>
        </div>
        <div class="project-desc-center">
          <p class="project-summary">
            We present a unified whole-body safe-control framework for robotic manipulators that replaces nominal-plus-filter pipelines with a single quadratic program powered by Koopman neural dynamics. The method learns a Koopman embedding and globally linear dynamics from data, enabling linear optimal control and hard safety enforcement for high-dimensional, nonlinear systems within one QP. To maintain feasibility near the safe-set boundary, we introduce an adversarial fine-tuning procedure for the safety index that preserves forward invariance without degrading performance. The approach reasons over link-level, distributed safety indices and integrates cleanly with a velocity-level controller.
          </p>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function research3_start() {
    document.getElementById('research3_video').style.opacity = "1";
  }
  function research3_stop() {
    document.getElementById('research3_video').style.opacity = "0";
  }
  research3_stop();
</script>
<!-- ---------------------------- Safe Koopman ----------------------------- -->
<!-- -------------------------------- SPARK -------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="research2_stop()" onmouseover="research2_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='research2_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/research/spark_thumbnail.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/research/spark_image.png' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a>
            <span class="papertitle">SPARK: A Toolbox for Safe Humanoid Autonomy and Teleoperation</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              Yifan Sun, Rui Chen, Kai S. Yun, Yikuan Fang, <strong>Sebin Jung</strong>, Weiye Zhao and Changliu Liu
            </span>
            <br>
            <em>Submitted to Robotics: Science and Systems (RSS), 2025.</em>
            <br>
            <div>
              <a href="https://arxiv.org/pdf/2502.03132" class="btn btn-info"><strong>arXiv</strong></a>
              <a href="https://intelligent-control-lab.github.io/spark/" class="btn btn-info"><strong>Project Page</strong></a>
              <a href="https://www.youtube.com/watch?v=vIzeQ31YbCM" class="btn btn-info"><strong>Video</strong></a>
            </div>
          </div>
        </div>
        <div class="project-desc-center">
          <p class="project-summary">
            SPARK is a modular toolbox designed to ensure safety in humanoid robot autonomy and teleoperation. It integrates state-of-the-art safe control methods into a flexible framework that supports safety customization across tasks and environments.
          </p>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function research2_start() {
    document.getElementById('research2_video').style.opacity = "1";
  }
  function research2_stop() {
    document.getElementById('research2_video').style.opacity = "0";
  }
  research2_stop();
</script>
<!-- -------------------------------- SPARK -------------------------------- -->
<!-- -------------------------------- Graduation Proj -------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="research1_stop()" onmouseover="research1_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='research1_video'>
          <video width="100%" muted autoplay loop>
            <source src="#" type="video/mp4">
          </video>
        </div>
        <img src='assets/research/GradProj.png' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a>
            <span class="papertitle">Vehicle Dynamics-Aware RL Environment Using IPG CarMaker</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong>, Junghyo Kim, Hyojae Lee and Kyoungseok Han
            </span>
            <br>
            <em>KNU MechE Poster Session</em>, 2025
            <br>
            <div>
              <!-- <a href="#" class="btn btn-primary"><strong>Project Page</strong></a> -->
              <a href="https://github.com/SBJung/graduation_project.git" class="btn btn-info"><strong>Github</strong></a>
            </div>
          </div>
        </div>
        <div class="project-desc-center">
          <p class="project-summary">
            We developed a RL environment for autonomous driving using the commercial simulator IPG CarMaker, incorporating realistic vehicle dynamics. A TD3-based control policy was trained to handle continuous steering and throttle inputs. This work demonstrates the potential of learning-based driving in high-fidelity simulation and lays the foundation for future multi-agent and complex scenario extensions.
          </p>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function research1_start() {
    document.getElementById('research1_video').style.opacity = "1";
  }
  function research1_stop() {
    document.getElementById('research1_video').style.opacity = "0";
  }
  research1_stop();
</script>
<!-- -------------------------------- Graduation Proj -------------------------------- -->


## Projects
<!-- -------------------------------- F1Tenth Safety 21 -------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="project1_stop()" onmouseover="project1_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='project1_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/projects/safety21.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/projects/safety21.jpg' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a href="https://safety21.cmu.edu/2024-deployment-partner-consortium-symposium/">
            <span class="papertitle">F1Tenth Racing Demo at Safety21</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong> with Kai S. Yun, Abhinandan Vellanki, Anirudh Shrihari, Kailash Jagadeesh, Wenli Xiao
            </span>
            <br>
            Pittsburgh, PA, 2024
            <br>
            <!-- <div>
              <a href="#" class="btn btn-primary"><strong>Project Page</strong></a>
              <a href="https://safety21.cmu.edu/2024-deployment-partner-consortium-symposium/" class="btn btn-info"><strong>Website</strong></a>
            </div> -->
          </div>
        </div>
        <div class="project-desc-center">
          <div class="project-summary">
            As part of the Safety21 event, our team presented a live demonstration of autonomous racing using two F1Tenth vehicles. This showcase highlighted the F1Tenth: Autonomous Racing course offered at the Carnegie Mellon Robotics Institute, led by Professor John Dolan.
          </div>
        </div>
      </div>
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
<!-- -------------------------------- F1Tenth Safety 21 -------------------------------- -->
<!-- ------------------------------- CARLA ------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="project2_stop()" onmouseover="project2_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='project2_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/projects/carla.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/projects/carla.jpg' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a href="https://candy-train-51d.notion.site/CARLA_0-9-15-e73f6bd40f42487895586f471a56c167">
            <span class="papertitle">CARLA Tutorial for Korean Students</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong>
            </span>
            <br>
            Daegu, South Korea, 2024
            <br>
            <div>
              <!-- <a href="#" class="btn btn-primary"><strong>Project Page</strong></a> -->
              <a href="https://candy-train-51d.notion.site/CARLA_0-9-15-e73f6bd40f42487895586f471a56c167" class="btn btn-info"><strong>Notion</strong></a>
            </div>
          </div>
        </div>
        <div class="project-desc-center">
          <div class="project-summary">
            As a side project in the VOICE Lab, I developed a concise CARLA tutorial tailored for Korean students. The goal was to help lab members and peers quickly familiarize themselves with the simulator's core features and sensors for autonomous driving research.
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function project2_start() {
    document.getElementById('project2_video').style.opacity = "1";
  }
  function project2_stop() {
    document.getElementById('project2_video').style.opacity = "0";
  }
  project1_stop();
</script>
<!-- -------------------------------- CARLA -------------------------------- -->
<!-- ------------------------------- Quanser ------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="project3_stop()" onmouseover="project3_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='project3_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/projects/quanser.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/projects/quanser.png' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a href="https://www.quanser.com/community/student-competition-old/2024-student-self-driving-car-competition/">
            <span class="papertitle">2024 ACC Quanser Self-Driving Car Student Competition</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong> with Suyong Park, Jiwoo Oh, Chanhyuk Lee, Junghyo Kim, Hyeonjeong Kim, Ginyeong Yang, Dongryeol Won
            </span>
            <br>
            Toronto, ON, 2024
            <br>
            <div>
              <!-- <a href="#" class="btn btn-primary"><strong>Project Page</strong></a> -->
              <a href="https://github.com/SBJung/2024-ACC-Quanser.git" class="btn btn-info"><strong>Code</strong></a>
            </div>
          </div>
        </div>
        <div class="project-desc-center">
          <div class="project-summary">
            Our team (VOICE) competed in the 2024 ACC Quanser Self-Driving Student Competition, showcasing reliable line following using Pure Pursuit and robust traffic sign detection for stop-and-go control. After passing the qualifier, we placed 4th in the finals.
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function project3_start() {
    document.getElementById('project3_video').style.opacity = "1";
  }
  function project3_stop() {
    document.getElementById('project3_video').style.opacity = "0";
  }
  project1_stop();
</script>
<!-- -------------------------------- Quanser -------------------------------- -->
<!-- ------------------------------- f1tenth korea ------------------------------- -->
<table class="project-table" style="width: 100%; height: 180px;">
  <tr onmouseout="project4_stop()" onmouseover="project4_start()" style="border: none;">
    <td style="padding:16px 16px 16px 0; width:25%; vertical-align:middle; border: none;">
      <div class="thumb-wrapper">
        <div class="thumb-hover" id='project4_video'>
          <video width="100%" muted autoplay loop>
            <source src="assets/projects/f1tenth.mp4" type="video/mp4">
          </video>
        </div>
        <img src='assets/projects/f1tenth.jpg' width="100%">
      </div>
    </td>
    <td style="padding:8px;width:75%;vertical-align:top; border: none;">
      <div class="project-content-wrapper">
        <div class="project-text-top">
          <a href="https://korea-race23.f1tenth.org/">
            <span class="papertitle">2023 ICCAS F1Tenth Korea Championship</span>
          </a>
          <br>
          <div class="project-meta">
            <span class="authors">
              <strong>Sebin Jung</strong> with 	Suyong Park, Yundo Choi, Hyeonjeong Kim, ChanHyuk Lee
            </span>
            <br>
            Yeosu, South Korea, 2023
            <br>
            <!-- <div>
              <a href="#" class="btn btn-primary"><strong>Project Page</strong></a>
              <a href="https://github.com/SBJung/2024-ACC-Quanser.git" class="btn btn-info"><strong>Code</strong></a>
            </div> -->
          </div>
        </div>
        <div class="project-desc-center">
          <div class="project-summary">
            Our team, TigerOX, competed in the 2023 ICCAS 2nd F1Tenth Korea Championship, optimizing a minimum-time raceline and implementing Pure Pursuit with adaptive velocity control.
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<script type="text/javascript">
  function project4_start() {
    document.getElementById('project4_video').style.opacity = "1";
  }
  function project4_stop() {
    document.getElementById('project4_video').style.opacity = "0";
  }
  project1_stop();
</script>
<!-- -------------------------------- f1tenth korea -------------------------------- -->

<!-- 
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
 -->

<!-- ## Publications

1. F.Bar, J.Doe: Effects of having a placeholder of a name
2. S.Holmes, J.Watson: Consequences of living with a sociopath in London


## References

* Foo Bar: Head of Department, Placeholder Names, Lorem
* John Doe: Associate Professor, Department of Computer Science, Ipsum -->


## Recent Activities

<div class="glider-contain" style="width: 600px; margin: 0 auto;">
  <button class="glider-prev">«</button>
  <div class="glider">
    <div class="carousel-item">
      <div class="image-wrapper">
        <img src="assets/activities/f1tenth.JPG" alt="1">
      </div>
      <p class="carousel-caption">Competed in 2nd F1Tenth Korea Championship!</p>
    </div>
    <div class="carousel-item">
      <div class="image-wrapper">
        <img src="assets/activities/doe.jpg" alt="2">
      </div>
      <p class="carousel-caption">Now in Berkeley for summer!</p>
    </div>
    <div class="carousel-item">
      <div class="image-wrapper">   
        <img src="assets/activities/bair.jpg" alt="3">
      </div>
      <p class="carousel-caption">Visited the heart of Berkeley AI, BAIR!</p>
    </div>
  </div>
  <button class="glider-next">»</button>
</div>

<!-- Glider.js init -->
<script>
  const glider = new Glider(document.querySelector('.glider'), {
    slidesToShow: 1,
    draggable: true,
    arrows: {
      prev: '.glider-prev',
      next: '.glider-next'
    }
  });

  let currentSlide = 0;
  const totalSlides = document.querySelectorAll('.carousel-item').length;

  setInterval(() => {
    currentSlide = (currentSlide + 1) % totalSlides;
    glider.scrollItem(currentSlide);
  }, 6000);
</script>



---
layout: homepage
---

## About Me

Hi! I'm a first-year Ph.D. student in Computer Science at The University of Texas at Austin, advised by [Prof. Qixing Huang](https://www.cs.utexas.edu/~huangqx/) and [Prof. Brandon Y. Feng](https://brandonyfeng.github.io/). I received my bachelor's degree in Robotics Engineering from Zhejiang University.

My research interests lie at the intersection of Computer Graphics, Physical Simulation, and Machine Learning. I am particularly interested in understanding the physical properties of the real world from visual observations, as well as developing learning-based methods to improve physical simulation.

At UT Austin, I also collaborate with [Prof. Etienne Vouga](https://www.cs.utexas.edu/~evouga/) and [Prof. Chandrajit Bajaj](https://www.cs.utexas.edu/~bajaj/cvc/index.shtml). Previously, I was an exchange student at the University of Toronto, where I worked with [Prof. Lueder Kahrs](https://www.utm.utoronto.ca/math-cs-stats/people/lueder-kahrs). During my undergraduate studies at Zhejiang University, I worked with [Prof. Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/) and [Prof. Yuanchao Shu](https://yshu.org/).

I am actively seeking research internship opportunities for Summer 2027! I am open to opportunities in physical simulation, computer graphics, computer vision, and related areas of machine learning. Please feel free to reach out!


## Education

<!-- UT Austin -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">The University of Texas at Austin </strong> <span class="edu-date">Aug. 2026 - Jun. 2031</span> <br>
    <strong>Ph.D.</strong> in Computer Science
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UT_logo.png" alt="UT logo">
  </div>
</div>

<!-- UofT -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">University of Toronto </strong> <span class="edu-date">Sept. 2024 – Dec. 2024</span><br>
    <strong>Exchange Student</strong>, Applied Science & Engineering
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UofT_logo2.png" alt="UofT logo">
  </div>
</div>

<!-- ZJU -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">Zhejiang University </strong> <span class="edu-date">Sept. 2022 – Jun. 2026</span><br>
    <strong>B.Eng.</strong> in Robotic Engineering (Honors)
  </div>
  <div class="edu-logo">
    <img src="/assets/img/ZJU_logo.png" alt="ZJU logo">
  </div>
</div>

<style>
/* 轻量级排版，不会影响全站样式 */
.edu-item{
  display:flex; 
  align-items:flex-start; 
  margin-bottom:1.2rem;
}
.edu-info{ flex:1; }
.edu-logo{ width:70px; text-align:right; }
.edu-logo img{ max-width:100%; height:auto; }
.edu-date{ font-size:0.9rem; }
.edu-school{ font-weight:600;}
</style>

{% include_relative _includes/publications.md %}

{% comment %}
{% include_relative _includes/services.md %}
{% endcomment %}

---
layout: homepage
---

## About Me

I’m a fourth-year undergraduate at Zhejiang University and a research intern at the University of Texas at Austin, advised by [Prof. Qixing Huang](https://www.cs.utexas.edu/~huangqx/), [Prof. Brandon Y. Feng](https://brandonyfeng.github.io/), [Prof. Chandrajit Bajaj](https://www.cs.utexas.edu/~bajaj/cvc/index.shtml), and [Prof. Etienne Vouga](https://www.cs.utexas.edu/~evouga/). Previously, I was an exchange student at the University of Toronto, where I worked with [Prof. Lueder Kahrs](https://www.utm.utoronto.ca/math-cs-stats/people/lueder-kahrs). At Zhejiang University, I'm fortunate to have worked with [Prof. Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/) and [Prof. Yuanchao Shu](https://yshu.org/).

## Research Interests

I am broadly interested in **Computer Vision**, with a particular focus on **Physical Understanding**. My research explores how AI systems can infer physical information of the real world, how to narrow the gap between physical simulation and the real world, and how incorporating physical knowledge can enhance the performance of foundation models.

## Education

<!-- ZJU -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">Zhejiang University </strong> <span class="edu-date">Sept. 2022 – Present</span><br>
    <strong>BEng. (Honors)</strong> in Robotic Engineering, College of Control Science and Engineering
  </div>
  <div class="edu-logo">
    <img src="/assets/img/ZJU_logo.png" alt="ZJU logo">
  </div>
</div>

<!-- UofT -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">University of Toronto </strong> <span class="edu-date">Sept. 2024 – Dec. 2024</span><br>
    <strong>Exchange Student</strong>, Department of Electrical & Computer Engineering
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UofT_logo2.png" alt="UofT logo">
  </div>
</div>

## Experiences
<!-- UT Austin -->
<div class="edu-item">
  <div class="edu-info">
    <strong class="edu-school">The University of Texas at Austin </strong> <span class="edu-date">Jun. 2025 – Present</span> <br>
    <strong>Research Intern</strong>, Department of Computer Science
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UT_logo.png" alt="UT logo">
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

---
layout: homepage
---

## About Me

I’m a 4th-year undergraduate at Zhejiang University advised by [Prof. Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/). Currently, I am also a research intern at the University of Texas at Austin, fortunately advised by [Prof. Qixing Huang](https://www.cs.utexas.edu/~huangqx/), [Prof. Brandon Y. Feng](https://brandonyfeng.github.io/), and [Prof. Chandrajit Bajaj](https://www.cs.utexas.edu/~bajaj/cvc/index.shtml). Previously, I exchanged at the University of Toronto and worked with [Prof. Lueder Kahrs](https://www.utm.utoronto.ca/math-cs-stats/people/lueder-kahrs). 


## Research Interests

Broadly, my research sits at the intersection of Computer Vision and Physical Understanding. I study how AI systems can learn different physical properties from the natural world, and how different visual representations expose different physical information. My work aims to answer these questions.


## Education
<!-- ZJU -->
<div class="edu-item">
  <div class="edu-info">
    <span class="edu-school">Zhejiang University </span> <span class="edu-date">Sept. 2022 – Present</span><br>
    <strong>B.S. (Honors)</strong> in Robotic Engineering
  </div>
  <div class="edu-logo">
    <img src="/assets/img/ZJU_logo.png" alt="ZJU logo">
  </div>
</div>

<!-- UT Austin -->
<div class="edu-item">
  <div class="edu-info">
    <span class="edu-school">The University of Texas at Austin </span> <span class="edu-date">Jun. 2025 – Present</span> <br>
    <strong>Research Intern</strong>, Department of Computer Science
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UT_logo.png" alt="UT logo">
  </div>
</div>

<!-- UofT -->
<div class="edu-item">
  <div class="edu-info">
    <span class="edu-school">University of Toronto </span> <span class="edu-date">Sept. 2024 – Dec. 2024</span><br>
    <strong>Exchange Student</strong>, Department of Electrical & Computer Engineering
  </div>
  <div class="edu-logo">
    <img src="/assets/img/UofT_logo.png" alt="UofT logo">
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
.edu-logo{
  /* 右侧预留的“盒子”宽度，可按需要调大/调小 */
  width:90px;                 /* 给文本留个统一右边距 */
  display:flex;
  align-items:center;
  justify-content:center;
}
.edu-logo img{
  height:70px;                /* 想要的统一高度 */
  width:auto;                 /* 保持纵横比 */
}
.edu-date{ color:#666; font-size:0.9rem; }
.edu-school{ font-weight:600; }
</style>

{% include_relative _includes/publications.md %}

{% include_relative _includes/services.md %}

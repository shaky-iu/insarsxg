---
layout: single
title: ""
permalink: /people/
author_profile: false
toc: false
sidebar: false
classes: wide people
---

<!-- 1. People页Banner图（导航栏下显示，带标题） -->
<div class="hero-section" style="background-image: url('https://shaky-lu.github.io/insarsxg/assets/images/people/people_banner.jpg') !important;">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>People</h1>
  </div>
</div>

<!-- 2. 居中容器（确保内容在页面中间） -->
<div class="people-container">
  <div class="pi-section">
    <div class="pi-photo">
      <img src="/insarsxg/assets/images/people/xuguo_shi.jpg" alt="Xuguo Shi">
    </div>

    <div class="pi-info">
      <h2>Xuguo Shi</h2>
      <p><strong>Associate Professor, Ph.D., M.S. Supervisor</strong></p>
      <p>
        Born in Tai'an, Shandong, China. His research focuses on satellite radar
        interferometry (InSAR) and its applications in geohazard monitoring.
      </p>
      <p>
        He received the Ph.D. degree in Engineering from the State Key Laboratory of
        Information Engineering in Surveying, Mapping and Remote Sensing, Wuhan
        University, in 2016.
      </p>
      <p>
        He has led and participated in projects funded by the National Natural
        Science Foundation of China and the National 973 Program. He has published
        more than 20 SCI-indexed journal papers and co-authored one academic monograph.
      </p>
      <p>
        He has served as a reviewer for several international journals, including
        <em>ISPRS Journal of Photogrammetry and Remote Sensing</em>,
        <em>Remote Sensing</em>, <em>Landslides</em>, and
        <em>Science of the Total Environment</em>.
      </p>
    </div>
  </div>


  <!-- 修改：Current Students → Current Master’s Students，删除原Master’s Students -->
  <h2>Current Master’s Students</h2>

  <ul class="student-list">
    <li>
      <strong>Xue Li</strong><br>
      Master’s Student, 2022–<br>
      B.S., University of Electronic Science and Technology of China, 2022
    </li>

    <li>
      <strong>Fan Yang</strong><br>
      Master’s Student, 2022–<br>
      B.S., Peking University, 2022
    </li>

    <li>
      <strong>Yuhang Wang</strong><br>
      Master’s Student, 2023–<br>
      B.S., Peking University, 2023
    </li>
  </ul>

  <!-- 修改：Undergraduate Students → 往届毕业生（与Current Master’s Students同级） -->
  <h2>往届毕业生</h2>

  <ul class="student-list">
    <li>
      <strong>Yusheng Li</strong><br>
      Undergraduate Student, Peking University, 2022–
    </li>

    <li>
      <strong>Minrong Fan</strong><br>
      Undergraduate Student, Peking University, 2022–
    </li>
  </ul>

  <!-- 修改：Group Activities → Group Photos -->
  <h2>Group Photos</h2>

  <div class="group-photos">
    <img src="/insarsxg/assets/images/group/group1.jpg" alt="Group photo 1">
    <img src="/insarsxg/assets/images/group/group2.jpg" alt="Group photo 2">
    <img src="/insarsxg/assets/images/group/group3.jpg" alt="Group photo 3">
  </div>

  <h2>Prospective Students and Postdocs</h2>

  <p class="prospective">
    We are currently recruiting graduate students in Photogrammetry and Remote
    Sensing. Students with backgrounds in photogrammetry, surveying and mapping,
    computer science, or mathematics are highly encouraged to apply.
  </p>
</div>

<style>
/* 强制内容居中（增强优先级） */
.people-container {
  max-width: 1200px !important;
  margin: 0 auto !important;
  padding: 0 2rem !important;
  width: 100% !important;
}

/* PI section */
.pi-section {
  display: flex;
  gap: 2.5rem;
  margin: 3rem 0;
  align-items: flex-start;
  flex-wrap: wrap; /* 移动端换行 */
  justify-content: center; /* 增强PI区域居中 */
}

.pi-photo img {
  width: 700px;
  max-width: 100%;
  border-radius:10px;
}

/* PI text */
.pi-info h2 {
  margin-top: 0;
}

/* Student list */
.student-list {
  list-style: none;
  padding-left: 0;
}

.student-list li {
  margin-bottom: 1.2rem;
}

/* Group photos */
.group-photos {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  flex-wrap: wrap;
  margin: 2rem 0;
}

.group-photos img {
  width: 300px;
  border-radius: 6px;
}

/* Prospective */
.prospective {
  max-width: 1400px;
  margin: 1.5rem auto 3rem auto;
  text-align: center;
  font-size: 1.1rem;
}
</style>

---
layout: single
title: ""
permalink: /people/
author_profile: false
toc: false
sidebar: false
classes: wide people
---

<!-- 1. People页Banner图 -->
<div class="hero-section" style="background-image: url('https://shaky-lu.github.io/insarsxg/assets/images/people/people_banner.jpg') !important;">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>People</h1>
  </div>
</div>

<!-- 2. 复用Research的全局样式容器（关键：全屏宽+居中） -->
<section class="intro-section">
  <div class="intro-container">
    <!-- 导师部分：照片左 + 文字右 -->
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

    <!-- 分隔：增加导师与下方内容的间距 -->
    <div style="margin: 4rem 0;"></div>

    <!-- 在读硕士生部分 -->
    <div class="section-block">
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
    </div>

    <!-- 分隔：增加在读生与往届生的间距 -->
    <div style="margin: 3rem 0;"></div>

    <!-- 往届毕业生部分 -->
    <div class="section-block">
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
    </div>

    <!-- 分隔：增加毕业生与合照的间距 -->
    <div style="margin: 3rem 0;"></div>

    <!-- 合照部分（与Current Master’s Students同级） -->
    <div class="section-block">
      <h2>Group Photos</h2>
      <div class="group-photos">
        <img src="/insarsxg/assets/images/group/group1.jpg" alt="Group photo 1">
        <img src="/insarsxg/assets/images/group/group2.jpg" alt="Group photo 2">
        <img src="/insarsxg/assets/images/group/group3.jpg" alt="Group photo 3">
      </div>
    </div>

    <!-- 分隔：增加合照与招生信息的间距 -->
    <div style="margin: 3rem 0;"></div>

    <!-- 招生信息部分 -->
    <div class="section-block">
      <h2>Prospective Students and Postdocs</h2>
      <p class="prospective">
        We are currently recruiting graduate students in Photogrammetry and Remote
        Sensing. Students with backgrounds in photogrammetry, surveying and mapping,
        computer science, or mathematics are highly encouraged to apply.
      </p>
    </div>
  </div>
</section>

<style>
/* 复用Research的全局样式，强化优先级 */
.intro-section {
  width: 100vw !important;
  max-width: 100% !important;
  margin: 0 auto !important;
  padding: 0 !important;
}
.intro-container {
  width: 100% !important;
  max-width: 100vw !important;
  margin: 0 auto !important;
  padding: 0 2rem !important;
}

/* 导师部分：照片左 + 文字右（全屏宽适配） */
.pi-section {
  display: flex;
  gap: 3rem; /* 照片与文字的间距 */
  align-items: flex-start;
  flex-wrap: wrap; /* 移动端自动换行 */
  width: 100% !important;
  max-width: 2500px !important; /* 限制导师区域最大宽度（避免超宽） */
  margin: 0 auto !important; /* 导师区域居中 */
}
.pi-photo {
  flex: 0 0 500px; /* 照片固定宽度 */
}
.pi-photo img {
  width: 100%;
  border-radius: 10px;
}
.pi-info {
  flex: 1; /* 文字部分占剩余宽度 */
}

/* 各模块容器（全屏宽 + 内容居中） */
.section-block {
  width: 100% !important;
  max-width: 2500px !important; /* 限制模块最大宽度（避免文字过宽） */
  margin: 0 auto !important; /* 模块整体居中 */
  padding: 0 1rem !important;
}

/* 学生列表样式 */
.student-list {
  list-style: none;
  padding-left: 0;
}
.student-list li {
  margin-bottom: 1.5rem; /* 学生之间的间距 */
  line-height: 1.6;
}

/* 合照样式 */
.group-photos {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 1rem;
}
.group-photos img {
  width: 300px;
  border-radius: 6px;
}

/* 招生信息样式 */
.prospective {
  text-align: center;
  font-size: 1.1rem;
  line-height: 1.8;
}

</style>

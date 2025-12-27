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
<div class="hero-section">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>People</h1>
  </div>
</div>

<!-- 2. 全局居中容器（用content-center实现2/3宽度+居中） -->
<section class="intro-section">
  <div class="intro-container content-center"> <!-- 新增content-center -->
    <!-- 导师部分：照片左 + 文字右 -->
        <!-- 导师部分：照片左 + 文字右 -->
    <div class="pi-section">
      <div class="pi-photo">
        <img src="/insarsxg/assets/images/people/xuguo_shi.jpg" alt="Xuguo Shi">
      </div>
      <div class="pi-info">
        <h2 style="font-size: 2rem !important; font-weight: 700 !important;">Xuguo Shi</h2> <!-- 放大字号（默认1.5rem→2rem） -->
        <p><strong>Associate Professor, Ph.D., M.S. Supervisor</strong></p>
        <p style="font-size: 1rem !important; line-height: 1.7 !important;">Born in Tai'an, Shandong, China. His research focuses on satellite radar interferometry (InSAR) and its applications in geohazard monitoring.</p>
        <p style="font-size: 1rem !important; line-height: 1.7 !important;">He received the Ph.D. degree in Engineering from the State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing, Wuhan University, in 2016.</p>
        <p style="font-size: 1rem !important; line-height: 1.7 !important;">He has led and participated in projects funded by the National Natural Science Foundation of China and the National 973 Program. He has published more than 20 SCI-indexed journal papers and co-authored one academic monograph.</p>
        <p style="font-size: 1rem !important; line-height: 1.7 !important;">He has served as a reviewer for several international journals, including <em>ISPRS Journal of Photogrammetry and Remote Sensing</em>, <em>Remote Sensing</em>, <em>Landslides</em>, and <em>Science of the Total Environment</em>.</p>
      </div>
    </div>

    <!-- 分隔：增加导师与下方内容的间距 -->
    <div style="margin: 4rem 0;"></div>

    <!-- 在读硕士生部分（标题前空两行） -->
    <div class="section-block">
      <div style="margin-top: 2rem;"></div> <!-- 修改：空两行（2rem） -->
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

    <!-- 往届毕业生部分（标题前空两行） -->
    <div class="section-block">
      <div style="margin-top: 2rem;"></div> <!-- 修改：空两行（2rem） -->
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

    <!-- 合照部分（h2标题 + 小标题样式 + 前空两行） -->
    <div class="section-block">
      <div style="margin-top: 2rem;"></div> <!-- 空两行（2rem） -->
      <h2 style="font-size: 1.3rem; font-weight: 600; color: #333; margin-bottom: 1rem;">Group Photos</h2> <!-- 恢复h2标签 + 小标题样式，修复闭合错误 -->
      <div class="group-photos">
        <img src="/insarsxg/assets/images/group/group1.jpg" alt="Group photo 1">
        <img src="/insarsxg/assets/images/group/group2.jpg" alt="Group photo 2">
        <img src="/insarsxg/assets/images/group/group3.jpg" alt="Group photo 3">
      </div>
    </div>

    <!-- 分隔：增加合照与招生信息的间距 -->
    <div style="margin: 3rem 0;"></div>

    <!-- 招生信息部分（标题前空两行） -->
    <div class="section-block">
      <div style="margin-top: 2rem;"></div> <!-- 修改：空两行（2rem） -->
      <h2>Prospective Students and Postdocs</h2>
      <p class="prospective">
        We are currently recruiting graduate students in Photogrammetry and Remote Sensing. Students with backgrounds in photogrammetry, surveying and mapping, computer science, or mathematics are highly encouraged to apply.
      </p>
    </div>
  </div>
</section>

<!-- 补充样式：统一小标题视觉效果，避免与其他样式冲突 -->
<style>
/* 适配Group Photos小标题样式 */
.people .section-block h3 {
  font-size: 1.3rem !important;
  font-weight: 600 !important;
  color: #333 !important;
  margin-bottom: 1rem !important;
  line-height: 1.5 !important;
}
/* 确保学生列表样式统一 */
.people .student-list {
  list-style: none !important;
  padding-left: 0 !important;
}
.people .student-list li {
  margin-bottom: 1rem !important;
  line-height: 1.6 !important;
}
/* 合照容器样式优化 */
.people .group-photos {
  display: flex !important;
  gap: 1.5rem !important;
  flex-wrap: wrap !important;
  justify-content: flex-start !important;
}
.people .group-photos img {
  width: 300px !important;
  height: auto !important;
  border-radius: 6px !important;
}
</style>

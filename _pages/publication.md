---
layout: single
title: ""
permalink: /publications/
author_profile: false
toc: false
sidebar: false
classes: wide publications
---

<!-- 1. Publications页Banner图 -->
<div class="hero-section">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>Publications</h1>
  </div>
</div>

<!-- 2. 论文列表（改用HTML标签，避免Markdown解析冲突） -->
<section class="intro-section">
  <div class="intro-container content-center"> <!-- 关键：新增content-center -->
    <!-- 2021 -->
    <h2>2021</h2>
    <ul>
      <li>Shi X, Hu X, Sitar N, et al. <a href="https://doi.org/">"Hydrological control shift from river level to rainfall in the reactivated Guobu slope besides the Laxiwa hydropower station in China"</a>. <em>Remote Sensing of Environment</em>, 265: 112664.</li>
      <li>Shi X, Zhang S, Jiang M, et al. <a href="https://doi.org/">"Spatial and temporal subsidence characteristics in Wuhan (China), during 2015–2019, inferred from Sentinel-1 synthetic aperture radar (SAR) interferometry"</a>. <em>Nat Hazards Earth Syst Sci</em>, 21: 2285-2297.</li>
    </ul>

    <!-- 2020 -->
    <h2>2020</h2>
    <ul>
      <li>Shi X, Zhang L, Zhong Y, et al. <a href="https://doi.org/">"Detection and Characterization of Active Slope Deformations with Sentinel-1 InSAR Analyses in the Southwest Area of Shanxi, China"</a>. <em>Remote Sensing</em>, 12: 392.</li>
    </ul>

    <!-- 2019 -->
    <h2>2019</h2>
    <ul>
      <li>Shi X, Xu Q, Zhang L, et al. <a href="https://doi.org/">"Surface displacements of the Heifangtai terrace in Northwest China measured by X and C-band InSAR observations"</a>. <em>Engineering Geology</em>, 259: 105181.</li>
      <li>Shi X, Yang C, Zhang L, et al. <a href="https://doi.org/">"Mapping and characterizing displacements of active loess slopes along the upstream Yellow River with multi-temporal InSAR datasets"</a>. <em>Science of The Total Environment</em>, 674: 200-210.</li>
    </ul>

    <!-- 2018 -->
    <h2>2018</h2>
    <ul>
      <li>Shi X, Zhang L, Zhou C, et al. <a href="https://doi.org/">"Retrieval of time series three-dimensional landslide surface displacements from multi-angular SAR observations"</a>. <em>Landslides</em>, 15: 1015-1027.</li>
    </ul>

    <!-- 2017 -->
    <h2>2017</h2>
    <ul>
      <li>Shi X, Jiang H, Zhang L, et al. <a href="https://doi.org/">"Landslide Displacement Monitoring with Split-Bandwidth Interferometry: A Case Study of the Shuping Landslide in the Three Gorges Area"</a>. <em>Remote Sensing</em>, 9: 937.</li>
      <li>Shi X, Zhang L, Tang M, et al. <a href="https://doi.org/">"Investigating a reservoir bank slope displacement history with multi-frequency satellite SAR data"</a>. <em>Landslides</em>, 14: 1961-1973.</li>
    </ul>

    <!-- 2016 -->
    <h2>2016</h2>
    <ul>
      <li>Shi X, Liao M, Li M, et al. <a href="https://doi.org/">"Wide-Area Landslide Deformation Mapping with Multi-Path ALOS PALSAR Data Stacks: A Case Study of Three Gorges Area, China"</a>. <em>Remote Sensing</em>, 8: 136.</li>
      <li>Shi X, Liao M, Zhang L, et al. <a href="https://doi.org/">"Landslide stability evaluation using high-resolution satellite SAR data in the Three Gorges area"</a>. <em>Quarterly Journal of Engineering Geology and Hydrogeology</em>, qjegh2015-2029.</li>
    </ul>

    <!-- 2015 -->
    <h2>2015</h2>
    <ul>
      <li>Shi X, Zhang L, Balz T, et al. <a href="https://doi.org/">"Landslide deformation monitoring using point-like target offset tracking with multi-mode high-resolution TerraSAR-X data"</a>. <em>ISPRS Journal of Photogrammetry and Remote Sensing</em>, 105: 128-140.</li>
    </ul>

    <!-- 2014 -->
    <h2>2014</h2>
    <ul>
      <li>Shi X, Liao M, Wang T, et al. <a href="https://doi.org/">"Expressway deformation mapping using high-resolution TerraSAR-X images"</a>. <em>Remote Sensing Letters</em>, 5: 194-203.</li>
      <li>Shi X, Zhang L, Liao M, et al. <a href="https://doi.org/">"Deformation monitoring of slow-moving landslide with L- and C-band SAR interferometry"</a>. <em>Remote Sensing Letters</em>, 5: 951-960.</li>
    </ul>
  </div>
</section>

<style>
/* 核心：强制Banner图显示+内容居中 */
.publications .hero-section {
  background-image: url('/insarsxg/assets/images/publications/publications_banner.jpg') !important; /* 强制加载图片 */
  background-size: cover !important;
  background-position: center !important;
  height: 450px !important;
  width: 100vw !important;
}

/* 内容居中：和People页统一宽度（75%视口） */
.publications .intro-container.content-center {
  max-width: calc(100vw * 3 / 4) !important;
  width: 100% !important;
  margin: 0 auto !important; /* 水平居中核心 */
  padding: 4rem 2rem !important;
  text-align: left !important;
  box-sizing: border-box !important;
}

/* 论文列表样式优化 */
.publications .intro-container h2 {
  margin-top: 3rem !important;
  margin-bottom: 1rem !important;
  font-size: 1.5rem !important;
  font-weight: 700 !important;
  color: #333 !important;
}
.publications .intro-container h2:first-of-type {
  margin-top: 0 !important; /* 第一个年份标题取消上边距 */
}
.publications .intro-container ul {
  list-style: none !important;
  padding-left: 0 !important;
  margin: 0 !important;
}
.publications .intro-container li {
  margin-bottom: 1.2rem !important;
  line-height: 1.8 !important;
  font-size: 1.05rem !important;
  color: #444 !important;
}

/* 链接和斜体样式 */
.publications .intro-container em {
  font-style: italic !important;
  color: #666 !important;
}
.publications .intro-container a {
  color: #009688 !important;
  text-decoration: none !important;
}
.publications .intro-container a:hover {
  text-decoration: underline !important;
}

/* 移动端适配 */
@media (max-width: 768px) {
  .publications .intro-container.content-center {
    max-width: 100vw !important;
    padding: 2rem 1rem !important;
  }
  .publications .hero-section {
    height: 300px !important;
  }
}
</style>

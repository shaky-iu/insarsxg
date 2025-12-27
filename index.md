---
layout: single
title: ""
author_profile: false
toc: false
sidebar: false
masthead: true
header:
  overlay_image: false
---

<!-- 直接用 custom-hero，不需要嵌套 full-width-container -->
<div class="custom-hero">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1>XuGuo SHI Group</h1>
    <p class="hero-subtitle">China University of Geosciences (Wuhan)</p>
  </div>
</div>

<!-- 简介文字区域，同样去掉 full-width-container -->
<div class="home-intro">
  <div class="home-intro__inner">
    <p>We study synthetic aperture radar (SAR) and microwave scattering mechanisms.</p>
    <p>We develop processing algorithms and software.</p>
    <p>We apply these algorithms and software in engineering, geoscience, and natural hazard response.</p>
  </div>
</div>

/* 全局强制全屏：突破主题的宽度限制 */
body {
  overflow-x: hidden; /* 彻底隐藏横向滚动 */
}

/* 强制Banner容器横向占满页面 */
.custom-hero {
  /* 关键：用绝对定位+左右拉伸实现全屏，无视父容器宽度 */
  position: relative;
  left: 0;
  right: 0;
  width: 100vw; /* 强制占满视口宽度（横向） */
  min-height: 400px; /* 纵向高度保持400px */
  background-image: url(/insarsxg/assets/images/home/hero.jpg);
  background-size: cover !important; /* 强制背景图拉伸铺满容器 */
  background-position: center center !important; /* 背景图始终居中 */
  background-repeat: no-repeat !important;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  padding: 2rem;
}

/* 以下样式保持不变，只改上面的 .custom-hero */
.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.hero-content {
  position: relative;
  z-index: 2;
  text-align: center;
}

.hero-content h1 {
  font-size: clamp(2rem, 5vw, 3.5rem);
  margin-bottom: 0.8rem;
  font-weight: 700;
}

.hero-subtitle {
  font-size: clamp(1rem, 2vw, 1.5rem);
  opacity: 0.95;
  margin: 0;
}

.home-intro {
  width: 100%;
  margin: 4rem 0;
  padding: 0 1.5rem;
}

.home-intro__inner {
  max-width: 1000px;
  margin: 0 auto;
  text-align: center;
  font-size: clamp(1rem, 1.5vw, 1.25rem);
  line-height: 1.8;
  color: #333;
}

.home-intro__inner p {
  margin-bottom: 1.4rem;
}

.home-intro__inner p:last-child {
  margin-bottom: 0;
}

.skip-links {
  display: none !important;
}

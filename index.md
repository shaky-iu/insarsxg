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

<!-- 全屏Banner区域（图片横向铺满 + 文字居中） -->
<div class="hero-banner">
  <div class="hero-text">
    <h1>XuGuo SHI Group</h1>
    <p>China University of Geosciences (Wuhan)</p>
  </div>
</div>

<!-- 简介文字区域（居中显示） -->
<div class="intro-text">
  <p>We study synthetic aperture radar (SAR) and microwave scattering mechanisms.</p>
  <p>We develop processing algorithms and software.</p>
  <p>We apply these algorithms and software in engineering, geoscience, and natural hazard response.</p>
</div>

<!-- 页脚（深色背景，匹配示例） -->
<footer class="group-footer">
  <p>© XuGuo SHI Group 2025</p>
  <p style="font-size: 0.8rem; opacity: 0.8;">Alembic Theme</p>
</footer>

<style>
/* 全局重置：消除默认边距 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* 1. 全屏Banner：横向铺满，背景图自适应 */
.hero-banner {
  width: 100%; /* 横向铺满页面 */
  height: 300px; /* 固定Banner高度（和示例一致） */
  background-image: url(/insarsxg/assets/images/home/hero.jpg); /* 替换为你的图片路径 */
  background-size: cover; /* 背景图铺满容器，保持比例 */
  background-position: center; /* 背景图始终居中 */
  display: flex; /* 文字居中核心：Flex布局 */
  align-items: center; /* 垂直居中 */
  justify-content: center; /* 水平居中 */
  color: #ffffff; /* 文字白色 */
  text-align: center;
}

/* 2. Banner文字样式 */
.hero-text h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}
.hero-text p {
  font-size: 1.2rem;
  opacity: 0.9;
}

/* 3. 简介文字：居中+间距 */
.intro-text {
  width: 100%;
  padding: 4rem 1rem; /* 上下间距，左右留白 */
  text-align: center;
  color: #666; /* 文字灰色（和示例一致） */
  font-size: 1.1rem;
  line-height: 1.8;
}
.intro-text p {
  margin-bottom: 1rem;
}

/* 4. 页脚：深色背景+居中 */
.group-footer {
  width: 100%;
  background-color: #333; /* 深色背景 */
  color: #fff;
  padding: 1.5rem 1rem;
  text-align: center;
  font-size: 0.9rem;
}
</style>

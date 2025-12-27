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

<!-- 全屏Banner区域 -->
<div class="hero-banner">
  <div class="hero-text">
    <h1>XuGuo SHI Group</h1>
    <p>China University of Geosciences (Wuhan)</p>
  </div>
</div>

<!-- 简介文字区域 -->
<div class="intro-text">
  <p>We study synthetic aperture radar (SAR) and microwave scattering mechanisms.</p>
  <p>We develop processing algorithms and software.</p>
  <p>We apply these algorithms and software in engineering, geoscience, and natural hazard response.</p>
</div>

<!-- 页脚 -->
<footer class="group-footer">
  <p>© XuGuo SHI Group 2025</p>
  <p style="font-size: 0.8rem; opacity: 0.8;">Alembic Theme</p>
</footer>

<style>
/* 1. 突破主题的容器宽度限制（核心修复） */
.page, .page__content, .single {
  max-width: 100% !important; /* 强制页面宽度100% */
  width: 100% !important;
  padding: 0 !important;
  margin: 0 !important;
}

/* 2. 全屏Banner */
.hero-banner {
  width: 100vw; /* 无视任何父容器，强制占满视口宽度 */
  height: 300px;
  background-image: url(/insarsxg/assets/images/home/hero.jpg);
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  text-align: center;
}

/* 3. Banner文字 */
.hero-text h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}
.hero-text p {
  font-size: 1.2rem;
  opacity: 0.9;
}

/* 4. 简介文字 */
.intro-text {
  width: 100%;
  padding: 4rem 1rem;
  text-align: center;
  color: #666;
  font-size: 1.1rem;
  line-height: 1.8;
}
.intro-text p {
  margin-bottom: 1rem;
}

/* 5. 全屏页脚 */
.group-footer {
  width: 100vw; /* 页脚也强制全屏 */
  background-color: #333;
  color: #fff;
  padding: 1.5rem 1rem;
  text-align: center;
  font-size: 0.9rem;
}
</style>

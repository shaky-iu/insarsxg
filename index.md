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

<!-- 核心样式：覆盖主题限制 + 适配尺寸 -->
<style>
  /* 1. 彻底突破主题容器宽度限制（关键） */
  html, body {
    width: 100%;
    overflow-x: hidden !important; /* 杜绝横向滚动 */
    margin: 0 !important;
    padding: 0 !important;
  }
  .page, .page__content, .single, .wrapper {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 2. 导航栏样式（匹配目标效果） */
  .masthead {
    background: #fff;
    border-bottom: 1px solid #f0f0f0;
    padding: 1rem 2rem !important;
  }
  .main-navigation {
    text-align: right !important; /* 导航链接靠右 */
    max-width: 100% !important;
    width: 100% !important;
  }
  .main-navigation li {
    display: inline-block;
    margin: 0 0 0 1.5rem !important; /* 导航链接间距 */
  }
  .main-navigation a {
    font-size: 1rem !important;
    color: #333 !important;
    font-weight: 400 !important;
  }
  .main-navigation a:hover {
    color: #009688 !important;
  }

  /* 3. Banner：横向全屏 + 高度自适应 */
  .hero-banner {
    width: 100vw !important; /* 强制占满视口宽度 */
    height: 30vh !important; /* 自适应高度（视口30%） */
    min-height: 250px !important; /* 手机端最小高度 */
    background-image: url(/insarsxg/assets/images/home/hero.jpg) !important;
    background-size: cover !important;
    background-position: center !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    color: #fff !important;
    text-align: center !important;
    margin: 0 !important;
    padding: 2rem !important;
  }
  /* Banner文字大小（匹配目标示例） */
  .hero-text h1 {
    font-size: 2.5rem !important;
    margin-bottom: 0.5rem !important;
    font-weight: 700 !important;
  }
  .hero-text p {
    font-size: 1.2rem !important;
    opacity: 0.95 !important;
  }

  /* 4. 简介文字样式 */
  .intro-text {
    width: 100% !important;
    padding: 4rem 2rem !important;
    text-align: center !important;
    color: #666 !important;
    font-size: 1.1rem !important;
    line-height: 1.8 !important;
    max-width: 1000px !important;
    margin: 0 auto !important; /* 文字区域居中，不贴边 */
  }
  .intro-text p {
    margin-bottom: 1rem !important;
  }
  .intro-text p:last-child {
    margin-bottom: 0 !important;
  }

  /* 5. 页脚样式 */
  .group-footer {
    width: 100vw !important;
    background-color: #333 !important;
    color: #fff !important;
    padding: 1.5rem 2rem !important;
    text-align: center !important;
    font-size: 0.9rem !important;
    margin: 0 !important;
  }

  /* 6. 隐藏所有多余元素（杜绝文字显示问题） */
  .skip-links, .page__meta, .single__footer {
    display: none !important;
  }
</style>

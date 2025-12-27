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

<!-- 自定义黑色页脚（保留） -->
<footer class="group-footer">
  <p>© XuGuo SHI Group 2025</p>
  <p style="font-size: 0.8rem; opacity: 0.8;">Alembic Theme</p>
</footer>

<!-- 最终样式：精准匹配页面宽度 + 隐藏冗余页脚 -->
<style>
  /* 1. 全局重置：页面无默认边距，内容贴合宽度 */
  html, body {
    width: 100%;
    overflow-x: hidden !important; /* 杜绝横向滚动 */
    margin: 0 !important;
    padding: 0 !important;
  }
  /* 覆盖主题容器：内容宽度和页面一致 */
  .page, .page__content, .single, .wrapper {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 2. 导航栏样式：贴合页面宽度 */
  .masthead {
    background: #fff;
    border-bottom: 1px solid #f0f0f0;
    padding: 1rem 2rem !important;
    width: 100% !important;
  }
  .main-navigation {
    text-align: right !important;
    max-width: 100% !important;
    width: 100% !important;
  }
  .main-navigation li {
    display: inline-block;
    margin: 0 0 0 1.5rem !important;
  }
  .main-navigation a {
    font-size: 1rem !important;
    color: #333 !important;
    font-weight: 400 !important;
  }
  .main-navigation a:hover {
    color: #009688 !important;
  }

  /* 3. Banner：宽度和页面一致 + 高度适配 */
  .hero-banner {
    width: 100% !important; /* 贴合页面宽度，不再用100vw避免溢出 */
    height: 30vh !important;
    min-height: 250px !important;
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
  .hero-text h1 {
    font-size: 2.5rem !important;
    margin-bottom: 0.5rem !important;
    font-weight: 700 !important;
  }
  .hero-text p {
    font-size: 1.2rem !important;
    opacity: 0.95 !important;
  }

  /* 4. 简介文字：宽度贴合页面，内容居中 */
  .intro-text {
    width: 100% !important;
    padding: 4rem 2rem !important;
    text-align: center !important;
    color: #666 !important;
    font-size: 1.1rem !important;
    line-height: 1.8 !important;
    max-width: 1000px !important; /* 文字区域最大宽度，避免过长 */
    margin: 0 auto !important; /* 文字居中，不贴边 */
    box-sizing: border-box !important;
  }
  .intro-text p {
    margin-bottom: 1rem !important;
  }
  .intro-text p:last-child {
    margin-bottom: 0 !important;
  }

  /* 5. 黑色页脚：固定在页面最底部，宽度贴合页面 */
  .group-footer {
    width: 100% !important; /* 贴合页面宽度 */
    background-color: #333 !important;
    color: #fff !important;
    padding: 1.5rem 2rem !important;
    text-align: center !important;
    font-size: 0.9rem !important;
    margin: 0 !important;
    margin-top: auto !important; /* 自动推到页面底部 */
  }

  /* 6. 彻底隐藏所有冗余元素（包括feed页脚） */
  .skip-links, .page__meta, .single__footer, footer.footer, 
  .feed-links, .site-footer {
    display: none !important;
    visibility: hidden !important;
  }

  /* 7. 确保页面高度足够，页脚在底部 */
  body {
    display: flex !important;
    flex-direction: column !important;
    min-height: 100vh !important;
  }
  .page__content {
    flex: 1 !important; /* 内容区域占满剩余高度，页脚自然到底 */
  }
</style>

---
layout: single
title: ""
author_profile: false
toc: false
sidebar: false
# 新增：启用顶部导航 masthead
masthead: true
# 关闭主题默认的 hero 区域（避免冲突）
header:
  overlay_image: false
  page.full_width: true
---

<!-- 全屏 Hero 区域 -->
<div class="full-width-container">
  <div class="custom-hero">
    <div class="hero-overlay"></div> <!-- 遮罩层，提升文字可读性 -->
    <div class="hero-content">
      <h1>XuGuo SHI Group</h1>
      <p class="hero-subtitle">China University of Geosciences (Wuhan)</p>
    </div>
  </div>
</div>

<!-- 简介文字区域 -->
<div class="full-width-container">
  <div class="home-intro">
    <div class="home-intro__inner">
      <p>We study synthetic aperture radar (SAR) and microwave scattering mechanisms.</p>
      <p>We develop processing algorithms and software.</p>
      <p>We apply these algorithms and software in engineering, geoscience, and natural hazard response.</p>
    </div>
  </div>
</div>


<style>
/* 全局重置：避免主题样式干扰 */
.custom-hero, .home-intro {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* =============================
   首页 Hero 区域（全屏 Banner）
   ============================= */
.custom-hero {
  /* 更优雅的全屏方式：替代 left/right: -50vw */
  width: 100%;
  min-height: 400px; /* 固定最小高度，适配不同屏幕 */
  background-image: url(/insarsxg/assets/images/home/hero.jpg);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: relative; /* 为遮罩层定位 */
  display: flex;
  align-items: center; /* 文字垂直居中 */
  justify-content: center; /* 文字水平居中 */
  color: #ffffff;
  padding: 2rem 1rem;
}

/* 半透明遮罩：解决文字与背景对比不足的问题 */
.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2); /* 可调整透明度（0.1~0.5） */
  z-index: 1;
}

.hero-content {
  position: relative; /* 层级高于遮罩 */
  z-index: 2;
  text-align: center;
}

.hero-content h1 {
  font-size: clamp(2rem, 5vw, 3.5rem); /* 响应式字号：移动端2rem，大屏3.5rem */
  margin-bottom: 0.8rem;
  font-weight: 700;
}

.hero-subtitle {
  font-size: clamp(1rem, 2vw, 1.5rem);
  opacity: 0.95;
  margin: 0;
}

/* =============================
   简介文字区域
   ============================= */
.home-intro {
  width: 100%;
  margin: 4rem 0;
  padding: 0 1.5rem;
}

.home-intro__inner {
  max-width: 1000px; /* 限制最大宽度，避免文字过长 */
  margin: 0 auto;
  text-align: center;
  font-size: clamp(1rem, 1.5vw, 1.25rem);
  line-height: 1.8; /* 增大行高，提升可读性 */
  color: #333; /* 文字颜色更沉稳 */
}

.home-intro__inner p {
  margin-bottom: 1.4rem;
}

/* 最后一个p标签取消下外边距 */
.home-intro__inner p:last-child {
  margin-bottom: 0;
}

/* 隐藏跳过链接（彻底移除） */
.skip-links {
  display: none !important;
  visibility: hidden !important;
}
</style>

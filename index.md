---
layout: none
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>XuGuo SHI Group</title>
  <style>
    /* 全局重置 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: sans-serif;
    }

    /* 1. 顶部导航栏（修复错位） */
    .nav-bar {
      width: 100%;
      padding: 1rem 2rem; /* 左右留白，避免内容贴边 */
      background: #fff;
      border-bottom: 1px solid #f0f0f0;
      display: flex;
      align-items: center;
      justify-content: space-between; /* 组名左、导航右 */
    }
    .nav-bar .group-name {
      color: #666;
      font-size: 1.2rem;
      font-weight: bold;
    }
    .nav-links a {
      color: #333;
      text-decoration: none;
      margin-left: 1.5rem; /* 导航链接间距 */
      font-size: 1rem;
    }
    .nav-links a:hover {
      color: #009688;
    }

    /* 2. 全屏Banner（高度自适应，和目标示例一致） */
    .hero-banner {
      width: 100%;
      height: 30vh; /* 自适应高度：占视口30%（可根据需求调整） */
      min-height: 250px; /* 最小高度，避免手机端太矮 */
      background-image: url(/insarsxg/assets/images/home/hero.jpg);
      background-size: cover;
      background-position: center;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }
    .hero-text h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    .hero-text p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* 3. 简介文字 */
    .intro-text {
      width: 100%;
      padding: 4rem 2rem;
      text-align: center;
      color: #666;
      font-size: 1.1rem;
      line-height: 1.8;
    }
    .intro-text p {
      margin-bottom: 1rem;
    }

    /* 4. 页脚 */
    .group-footer {
      width: 100%;
      background-color: #333;
      color: #fff;
      padding: 1.5rem 2rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <!-- 导航栏 -->
  <div class="nav-bar">
    <div class="group-name">XuGuo SHI Group</div>
    <div class="nav-links">
      <a href="/insarsxg/">Home</a>
      <a href="/insarsxg/people/">People</a>
      <a href="/insarsxg/research/">Research</a>
      <a href="/insarsxg/publications/">Publications</a>
      <a href="/insarsxg/projects/">Projects</a>
      <a href="/insarsxg/contact/">Contact</a>
    </div>
  </div>

  <!-- Banner区域 -->
  <div class="hero-banner">
    <div class="hero-text">
      <h1>XuGuo SHI Group</h1>
      <p>China University of Geosciences (Wuhan)</p>
    </div>
  </div>

  <!-- 简介文字 -->
  <div class="intro-text">
    <p>We study synthetic aperture radar (SAR) and microwave scattering mechanisms.</p>
    <p>We develop processing algorithms and software.</p>
    <p>We apply these algorithms and software in engineering, geoscience, and natural hazard response.</p>
  </div>

  <!-- 页脚 -->
  <div class="group-footer">
    <p>© XuGuo SHI Group 2025</p>
    <p style="font-size: 0.8rem; opacity: 0.8;">Alembic Theme</p>
  </div>
</body>
</html>

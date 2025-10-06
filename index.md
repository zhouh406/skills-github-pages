---
layout: home
title: 个人主页 | zchhaa
---

<!-- 顶部欢迎区 -->
<div class="hero">
  <h1>👋 你好，我是 zchhaa</h1>
  <p class="hero-subtitle">
    通信领域硕士研究生 · 专注于 <strong>粒子群算法 × 天线设计 × 通信系统</strong> 的交叉研究
  </p>
  <p>这里记录我的学习笔记、项目实践与思考。</p>
</div>

<hr class="divider">

<!-- 关于我 模块 -->
<div class="card">
  <h2>📝 关于我</h2>
  <p>
    我是一名通信领域硕士研究生，热衷于 <strong>通信理论、射频技术、天线设计、电磁仿真</strong>，并探索其与 <strong>AI（如粒子群算法）</strong> 的交叉应用。
  </p>
  <ul>
    <li>🔭 研究方向：<em>粒子群算法在天线阵列优化中的应用</em></li>
    <li>🌱 正在学习：粒子群算法的改进与工程化落地</li>
    <li>💬 可交流：通信基础、天线设计流程、AI算法入门</li>
    <li>📫 联系我：<a href="mailto:zhouh268@mail2.sysu.edu.cn">your-email@example.com</a>（替换为你的邮箱）</li>
  </ul>
</div>

<hr class="divider">

<!-- 最新文章 模块 -->
<div class="card">
  <h2>📚 最新文章</h2>
  <!-- 若后续用Jekyll博客功能，可通过Liquid循环自动生成：
  {% for post in site.posts limit:3 %}
  <article class="post-preview">
    <a href="{{ post.url }}">{{ post.title }}</a>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
    <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
  </article>
  {% endfor %}
  -->
  <p>近期暂无文章，即将分享粒子群算法与天线设计的学习笔记～</p>
</div>

<hr class="divider">

<!-- 我的项目 模块 -->
<div class="card">
  <h2>🛠️ 我的项目</h2>
  <ul class="project-list">
    <li>
      <h3>粒子群算法优化天线阵列</h3>
      <p>使用粒子群算法对相控阵天线的阵元排布、相位加权进行迭代优化，提升波束指向精度与旁瓣抑制比。</p>
    </li>
    <li>
      <h3>射频电路自动化仿真工具链</h3>
      <p>基于Python脚本自动化调用HFSS、ADS等软件，实现射频电路的参数扫描、批量仿真与结果可视化。</p>
    </li>
  </ul>
</div>

<hr class="divider">

<!-- 社交媒体 模块 -->
<div class="card">
  <h2>🔗 社交媒体</h2>
  <ul class="social-links">
    <li><a href="https://github.com/zhouh406" target="_blank">GitHub →</a></li>
    <li><a href="https://www.researchgate.net/" target="_blank">ResearchGate →</a> <!-- 替换为你的链接 --></li>
    <li><a href="https://www.linkedin.com/" target="_blank">LinkedIn →</a> <!-- 替换为你的链接 --></li>
  </ul>
</div>

<!-- 引入外部样式文件 -->
<link rel="stylesheet" href="style.css">

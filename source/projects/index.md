---
title: 我的项目展示
date: 2024-01-01 00:00:00
type: "projects"
layout: "page"
---

# 🚀 我的项目展示

欢迎来到我的项目展示页面！这里展示了我开发的各种小工具和小游戏。每个项目都是我学习和探索新技术的成果。

## 🎮 小游戏系列

### 现代化贪吃蛇游戏

<div class="project-card">
  <div class="project-info">
    <h4>🐍 现代化贪吃蛇游戏</h4>
    <p>基于HTML5 Canvas技术开发的现代化贪吃蛇游戏，具有华丽的视觉效果、多种特殊食物、粒子系统、触屏优化等特性。</p>
    
    <div class="tech-stack">
      <span class="tech-tag">HTML5</span>
      <span class="tech-tag">Canvas</span>
      <span class="tech-tag">JavaScript</span>
      <span class="tech-tag">CSS3</span>
    </div>
    
    <div class="project-features">
      <h5>✨ 主要特性：</h5>
      <ul>
        <li>🎨 华丽的视觉效果和粒子系统</li>
        <li>🍎 多种特殊食物（普通、黄金、加速、减速）</li>
        <li>📱 完美的移动端适配和触屏操作</li>
        <li>🎯 实时分数系统和最高分记录</li>
        <li>⚡ 四档速度选择</li>
        <li>🎮 虚拟控制器支持</li>
      </ul>
    </div>
    
    <div class="project-links">
      <a href="/static/snake.html" class="btn-demo" target="_blank">🎮 在线试玩</a>
      <a href="https://github.com/lovesuolove/modern-snake-game" class="btn-source" target="_blank">📝 查看源码</a>
    </div>
  </div>
</div>

---

## 🛠️ 小工具系列

<div class="coming-soon">
  <h3>🚧 更多项目正在开发中...</h3>
  <p>敬请期待更多有趣的小工具和小游戏！</p>
</div>

---

## 📊 技术栈统计

<div class="tech-stats">
  <div class="tech-item">
    <span class="tech-name">JavaScript</span>
    <div class="tech-bar">
      <div class="tech-progress" style="width: 90%;"></div>
    </div>
  </div>
  
  <div class="tech-item">
    <span class="tech-name">HTML5/CSS3</span>
    <div class="tech-bar">
      <div class="tech-progress" style="width: 85%;"></div>
    </div>
  </div>
  
  <div class="tech-item">
    <span class="tech-name">Canvas</span>
    <div class="tech-bar">
      <div class="tech-progress" style="width: 80%;"></div>
    </div>
  </div>
</div>

<style>
.project-card {
  border: 1px solid #e1e8ed;
  border-radius: 12px;
  padding: 20px;
  margin: 20px 0;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
}

.tech-stack {
  margin: 15px 0;
}

.tech-tag {
  display: inline-block;
  background: #007acc;
  color: white;
  padding: 4px 8px;
  border-radius: 4px;
  font-size: 12px;
  margin: 2px 4px 2px 0;
}

.project-features ul {
  list-style: none;
  padding-left: 0;
}

.project-features li {
  margin: 8px 0;
  padding-left: 0;
}

.project-links {
  margin-top: 20px;
}

.btn-demo, .btn-source {
  display: inline-block;
  padding: 10px 20px;
  margin: 5px 10px 5px 0;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.3s ease;
}

.btn-demo {
  background: #28a745;
  color: white;
}

.btn-demo:hover {
  background: #218838;
  color: white;
}

.btn-source {
  background: #6c757d;
  color: white;
}

.btn-source:hover {
  background: #545b62;
  color: white;
}

.coming-soon {
  text-align: center;
  padding: 40px 20px;
  background: #f8f9fa;
  border-radius: 8px;
  margin: 20px 0;
}

.tech-stats {
  margin: 30px 0;
}

.tech-item {
  margin: 15px 0;
}

.tech-name {
  display: inline-block;
  width: 120px;
  font-weight: bold;
}

.tech-bar {
  display: inline-block;
  width: 200px;
  height: 20px;
  background: #e9ecef;
  border-radius: 10px;
  overflow: hidden;
  vertical-align: middle;
}

.tech-progress {
  height: 100%;
  background: linear-gradient(90deg, #007acc, #00d4ff);
  border-radius: 10px;
  transition: width 0.3s ease;
}
</style>
---
title: 小游戏展示
date: 2024-01-01 00:00:00
type: "games"
layout: "page"
---

# 🎮 小游戏展示

这里收集了我开发的各种有趣的小游戏，每个游戏都可以直接在浏览器中运行！

## 🐍 现代化贪吃蛇游戏

<div class="game-showcase">
  <div class="game-preview">
    <div class="game-screen">
      <div class="snake-demo">
        <div class="snake-head"></div>
        <div class="snake-body"></div>
        <div class="snake-body"></div>
        <div class="food"></div>
      </div>
    </div>
  </div>
  
  <div class="game-info">
    <h3>🐍 现代化贪吃蛇游戏</h3>
    <p>一款基于HTML5 Canvas技术开发的现代化贪吃蛇游戏，拥有华丽的视觉效果和流畅的游戏体验。</p>
    
    <div class="game-features">
      <div class="feature-grid">
        <div class="feature-item">
          <span class="feature-icon">🎨</span>
          <span>华丽视觉效果</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">🍎</span>
          <span>多种特殊食物</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">📱</span>
          <span>移动端适配</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">⚡</span>
          <span>粒子特效系统</span>
        </div>
      </div>
    </div>
    
    <div class="game-controls">
      <h4>🎮 游戏操作：</h4>
      <div class="controls-grid">
        <div class="control-item">
          <kbd>↑</kbd><kbd>↓</kbd><kbd>←</kbd><kbd>→</kbd>
          <span>方向键控制</span>
        </div>
        <div class="control-item">
          <kbd>SPACE</kbd>
          <span>暂停/继续</span>
        </div>
        <div class="control-item">
          <span class="mobile-icon">📱</span>
          <span>触屏滑动</span>
        </div>
      </div>
    </div>
    
    <div class="game-actions">
      <a href="/games/snake.html" class="play-btn" target="_blank">
        <span class="play-icon">▶️</span>
        立即游玩
      </a>
      <a href="https://github.com/lovesuolove/lovesuolove.github.io" class="source-btn" target="_blank">
        <span class="source-icon">📝</span>
        查看源码
      </a>
    </div>
  </div>
</div>

---

## 🧩 俄罗斯方块游戏

<div class="game-showcase tetris-showcase">
  <div class="game-preview">
    <div class="game-screen tetris-screen">
      <div class="tetris-demo">
        <div class="tetris-block t-block"></div>
        <div class="tetris-block i-block"></div>
        <div class="tetris-block o-block"></div>
        <div class="falling-piece"></div>
      </div>
    </div>
  </div>
  
  <div class="game-info">
    <h3>🧩 俄罗斯方块游戏</h3>
    <p>经典的俄罗斯方块游戏，采用Vue.js框架开发，拥有华丽的3D视觉效果和流畅的游戏体验。</p>
    
    <div class="game-features">
      <div class="feature-grid">
        <div class="feature-item">
          <span class="feature-icon">🎨</span>
          <span>3D视觉效果</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">✨</span>
          <span>粒子背景系统</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">📱</span>
          <span>移动端适配</span>
        </div>
        <div class="feature-item">
          <span class="feature-icon">🎵</span>
          <span>音效系统</span>
        </div>
      </div>
    </div>
    
    <div class="game-controls">
      <h4>🎮 游戏操作：</h4>
      <div class="controls-grid">
        <div class="control-item">
          <kbd>↑</kbd><kbd>↓</kbd><kbd>←</kbd><kbd>→</kbd>
          <span>移动和旋转</span>
        </div>
        <div class="control-item">
          <kbd>SPACE</kbd>
          <span>暂停/继续</span>
        </div>
        <div class="control-item">
          <span class="mobile-icon">📱</span>
          <span>触屏控制</span>
        </div>
      </div>
    </div>
    
    <div class="game-actions">
      <a href="/games/tetris.html" class="play-btn" target="_blank">
        <span class="play-icon">▶️</span>
        立即游玩
      </a>
      <a href="https://github.com/lovesuolove/lovesuolove.github.io" class="source-btn" target="_blank">
        <span class="source-icon">📝</span>
        查看源码
      </a>
    </div>
  </div>
</div>

---

## 🚧 更多游戏开发中

<div class="upcoming-games">
  <h3>即将推出的游戏：</h3>
  <div class="upcoming-grid">
    
    <div class="upcoming-item">
      <div class="upcoming-icon">🎯</div>
      <h4>打砖块游戏</h4>
      <p>经典的打砖块游戏，加入现代化特效</p>
      <span class="status planning">计划中</span>
    </div>
    
    <div class="upcoming-item">
      <div class="upcoming-icon">🎲</div>
      <h4>2048游戏</h4>
      <p>数字合并游戏，简洁优雅的设计</p>
      <span class="status planning">计划中</span>
    </div>
  </div>
</div>

<style>
.game-showcase {
  display: flex;
  gap: 30px;
  margin: 30px 0;
  padding: 30px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 15px;
  color: white;
  flex-wrap: wrap;
}

.game-preview {
  flex: 1;
  min-width: 300px;
}

.game-screen {
  width: 250px;
  height: 250px;
  background: #000;
  border-radius: 10px;
  position: relative;
  overflow: hidden;
  border: 3px solid #333;
}

.snake-demo {
  position: relative;
  width: 100%;
  height: 100%;
}

.snake-head {
  position: absolute;
  width: 20px;
  height: 20px;
  background: #00ff88;
  border-radius: 50%;
  top: 100px;
  left: 120px;
  box-shadow: 0 0 10px #00ff88;
  animation: pulse 2s infinite;
}

.snake-body {
  position: absolute;
  width: 18px;
  height: 18px;
  background: #00cc66;
  border-radius: 3px;
  top: 101px;
}

.snake-body:nth-child(2) {
  left: 100px;
}

.snake-body:nth-child(3) {
  left: 80px;
}

.food {
  position: absolute;
  width: 16px;
  height: 16px;
  background: #ff4444;
  border-radius: 50%;
  top: 60px;
  left: 160px;
  box-shadow: 0 0 15px #ff4444;
  animation: glow 1.5s infinite alternate;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.1); }
}

@keyframes glow {
  0% { box-shadow: 0 0 15px #ff4444; }
  100% { box-shadow: 0 0 25px #ff4444, 0 0 35px #ff4444; }
}

/* Tetris Game Styles */
.tetris-showcase {
  background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
}

.tetris-demo {
  position: relative;
  width: 100%;
  height: 100%;
}

.tetris-block {
  position: absolute;
  width: 20px;
  height: 20px;
  border: 1px solid #333;
}

.t-block {
  background: #9b59b6;
  top: 80px;
  left: 100px;
  box-shadow: 0 0 10px #9b59b6;
}

.i-block {
  background: #3498db;
  top: 120px;
  left: 80px;
  width: 80px;
  height: 20px;
  box-shadow: 0 0 10px #3498db;
}

.o-block {
  background: #f1c40f;
  top: 160px;
  left: 120px;
  width: 40px;
  height: 40px;
  box-shadow: 0 0 10px #f1c40f;
}

.falling-piece {
  position: absolute;
  width: 20px;
  height: 20px;
  background: #e74c3c;
  top: 40px;
  left: 140px;
  box-shadow: 0 0 15px #e74c3c;
  animation: tetris-fall 3s infinite linear;
}

@keyframes tetris-fall {
  0% { top: 40px; }
  100% { top: 200px; }
}

.game-info {
  flex: 2;
  min-width: 300px;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin: 20px 0;
}

.feature-item {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 8px;
}

.feature-icon {
  font-size: 1.2em;
}

.controls-grid {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin: 15px 0;
}

.control-item {
  display: flex;
  align-items: center;
  gap: 10px;
}

kbd {
  background: #333;
  color: white;
  padding: 4px 8px;
  border-radius: 4px;
  font-family: monospace;
  margin: 0 2px;
}

.mobile-icon {
  font-size: 1.2em;
}

.game-actions {
  display: flex;
  gap: 15px;
  margin-top: 25px;
  flex-wrap: wrap;
}

.play-btn, .source-btn {
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.3s ease;
}

.play-btn {
  background: #28a745;
  color: white;
}

.play-btn:hover {
  background: #218838;
  transform: translateY(-2px);
  color: white;
}

.source-btn {
  background: rgba(255, 255, 255, 0.2);
  color: white;
  border: 2px solid rgba(255, 255, 255, 0.3);
}

.source-btn:hover {
  background: rgba(255, 255, 255, 0.3);
  transform: translateY(-2px);
  color: white;
}

.upcoming-games {
  margin: 40px 0;
  padding: 30px;
  background: #f8f9fa;
  border-radius: 15px;
}

.upcoming-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.upcoming-item {
  padding: 20px;
  background: white;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.upcoming-item:hover {
  transform: translateY(-5px);
}

.upcoming-icon {
  font-size: 3em;
  margin-bottom: 15px;
}

.status {
  display: inline-block;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  font-weight: bold;
  margin-top: 10px;
}

.status.developing {
  background: #ffc107;
  color: #856404;
}

.status.planning {
  background: #17a2b8;
  color: white;
}

@media (max-width: 768px) {
  .game-showcase {
    flex-direction: column;
    text-align: center;
  }
  
  .feature-grid {
    grid-template-columns: 1fr;
  }
  
  .game-actions {
    justify-content: center;
  }
}
</style>
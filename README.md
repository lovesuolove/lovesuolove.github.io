# 我的技术博客 🚀

这是一个基于 Hexo 和 NexT 主题构建的现代化技术博客，专门用于展示个人开发的小工具和小游戏。

## ✨ 特性

- 🎨 **现代化设计**: 使用 NexT 主题的 Gemini 方案，简洁优雅
- 📱 **响应式布局**: 完美适配桌面端和移动端
- 🎮 **项目展示**: 专门的页面展示游戏和工具项目
- 🚀 **自动部署**: 通过 GitHub Actions 自动部署到 GitHub Pages
- 🔍 **SEO 优化**: 内置搜索引擎优化配置
- 💬 **社交集成**: 集成 GitHub 和邮箱联系方式
- 🌙 **暗色模式**: 支持明暗主题切换
- 📊 **访问统计**: 集成不蒜子访问统计

## 🛠️ 技术栈

- **静态站点生成器**: [Hexo](https://hexo.io/)
- **主题**: [NexT](https://theme-next.js.org/)
- **部署平台**: GitHub Pages
- **CI/CD**: GitHub Actions
- **开发环境**: Node.js 18+

## 📁 项目结构

```
my-blog/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions 部署配置
├── source/
│   ├── _posts/                 # 博客文章
│   ├── about/
│   │   └── index.md           # 关于页面
│   ├── projects/
│   │   └── index.md           # 项目展示页面
│   ├── games/
│   │   └── index.md           # 游戏展示页面
│   └── tools/
│       └── index.md           # 工具展示页面
├── themes/
│   └── next/                   # NexT 主题文件
├── _config.yml                 # Hexo 主配置文件
├── _config.next.yml           # NexT 主题配置文件
└── package.json               # 项目依赖
```

## 🚀 快速开始

### 环境要求

- Node.js 18.0 或更高版本
- npm 或 yarn
- Git

### 本地开发

1. **克隆仓库**
   ```bash
   git clone https://github.com/lovesuolove/lovesuolove.github.io.git
   cd lovesuolove.github.io
   ```

2. **安装依赖**
   ```bash
   npm install
   ```

3. **启动开发服务器**
   ```bash
   npm run server
   ```

4. **访问博客**
   打开浏览器访问 `http://localhost:4000`

### 创建新文章

```bash
# 创建新文章
hexo new "文章标题"

# 创建新页面
hexo new page "页面名称"
```

### 构建和部署

```bash
# 清理缓存并生成静态文件
npm run build

# 部署到 GitHub Pages（如果配置了 hexo-deployer-git）
npm run deploy
```

## 📝 内容管理

### 添加新项目

1. **游戏项目**: 编辑 `source/games/index.md`
2. **工具项目**: 编辑 `source/tools/index.md`
3. **综合项目**: 编辑 `source/projects/index.md`

### 文章写作

文章使用 Markdown 格式编写，支持：

- 代码高亮
- 数学公式（MathJax）
- 图片和视频嵌入
- 自定义 CSS 样式

### Front Matter 示例

```yaml
---
title: 文章标题
date: 2024-01-01 12:00:00
tags:
  - JavaScript
  - 游戏开发
categories:
  - 技术分享
description: 文章描述
---
```

## ⚙️ 配置说明

### 主要配置文件

- **`_config.yml`**: Hexo 核心配置
- **`_config.next.yml`**: NexT 主题配置

### 重要配置项

```yaml
# 站点信息
title: Suo的创意工坊
subtitle: 小工具与小游戏的创意世界
description: 专注于创建有趣且实用的小工具和小游戏
author: Suo
language: zh-CN

# URL 配置
url: https://lovesuolove.github.io
root: /

# 部署配置
deploy:
  type: git
  repo: https://github.com/lovesuolove/lovesuolove.github.io.git
  branch: main
```

## 🎨 主题定制

### 颜色方案

主题使用了现代化的配色方案：

- 主色调: 渐变蓝紫色 (#667eea → #764ba2)
- 辅助色: 渐变绿蓝色 (#84fab0 → #8fd3f4)
- 背景色: 浅灰色 (#f8f9fa)

### 自定义样式

每个页面都包含了自定义的 CSS 样式，提供：

- 响应式卡片布局
- 悬停动画效果
- 渐变背景
- 现代化图标

## 🚀 部署

### GitHub Pages 自动部署

项目配置了 GitHub Actions，当推送到 `main` 分支时会自动：

1. 安装依赖
2. 构建静态文件
3. 部署到 GitHub Pages

### 手动部署

```bash
# 生成静态文件
hexo generate

# 部署到 GitHub Pages
hexo deploy
```

## 📊 SEO 优化

- 自动生成 sitemap
- 优化的 meta 标签
- 结构化数据
- 社交媒体分享优化
- 搜索引擎友好的 URL

## 🔧 维护

### 更新依赖

```bash
# 检查过时的包
npm outdated

# 更新依赖
npm update
```

### 主题更新

```bash
# 更新 NexT 主题
cd themes/next
git pull
```

### 备份

定期备份以下重要文件：

- `_config.yml`
- `_config.next.yml`
- `source/` 目录
- `package.json`

## 📞 联系方式

- **邮箱**: lovesuolove@gmail.com
- **GitHub**: [@lovesuolove](https://github.com/lovesuolove)

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [Hexo](https://hexo.io/) - 强大的静态站点生成器
- [NexT](https://theme-next.js.org/) - 优雅的 Hexo 主题
- [GitHub Pages](https://pages.github.com/) - 免费的静态网站托管服务

---

**Happy Coding! 🎉**
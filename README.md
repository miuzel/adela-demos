# 伽利略变换 · 小学生公益开源课件

这是一个面向小学生、老师与家长的互动物理课件集合，用直观动画和可操作实验认识**参照物、相对速度与伽利略变换**。项目完全静态、无需安装依赖，公益开源，欢迎用于课堂、家庭学习和科普活动。

在线体验：<https://miuzel.github.io/galileo-transform-kids/>

## 课件特色

- **动手探索**：滑块、播放、视角切换和画布动画让公式变成可观察的现象。
- **循序渐进**：先用生活化动画建立直觉，再在实验室验证速度关系。
- **轻量开放**：原生 HTML/CSS/JavaScript，无构建步骤，可直接阅读和修改。
- **友好可访问**：响应式布局，支持手机与桌面浏览器。

## 目录结构

```text
.
├── index.html                    # 课件集合首页
├── demos/
│   ├── galileo-lab/              # 伽利略变换实验室
│   │   ├── index.html
│   │   ├── app.js
│   │   └── styles.css
│   └── relative-velocity/        # 相对速度动画小课堂
│       └── index.html
├── docs/demo-design-guideline.md # 视觉交互规范
├── .github/workflows/pages.yml   # GitHub Pages 部署
├── LICENSE
└── .gitignore
```

## 本地打开

无需 npm 或构建工具：直接用浏览器打开根目录 `index.html`，或在根目录启动任意静态文件服务器后访问。所有页面链接均为相对路径，适用于仓库子路径部署。

## 部署到 GitHub Pages

1. Fork 或复制本仓库并推送到 GitHub 的 `miuzel/galileo-transform-kids`（默认分支 `main`）。
2. 在仓库 **Settings → Pages** 中将 Source 设为 **GitHub Actions**。
3. 推送到 `main` 后，`.github/workflows/pages.yml` 会使用官方 Pages Actions 自动发布根目录。
4. 发布完成后访问：<https://miuzel.github.io/galileo-transform-kids/>。

## 贡献与致谢

欢迎提交 Issue、改进文案、修复交互或增加适合儿童的例子。请保持页面轻量、中文清晰、操作反馈明确，并遵循 [演示视觉交互规范](docs/demo-design-guideline.md)。感谢所有帮助孩子亲近科学的老师、家长与开源贡献者。

## 许可与公益声明

本项目采用 [MIT License](LICENSE)，Copyright (c) 2026 miuzel。你可以免费使用、修改和分享；如用于教学，欢迎保留项目来源。课件仅用于教育演示，不替代正式教材。

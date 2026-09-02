# adela-demos · 小学生公益课件集合

adela-demos 是面向小学生、老师与家长的公益开源互动课件集合，持续新增物理科学与小学奥数趣味课件。项目用直观动画和可操作实验化解抽象公式与思维难题，完全静态、无需安装依赖，欢迎用于课堂、家庭学习和科普活动。

在线体验：<https://miuzel.github.io/adela-demos/>

## 课件专题

- **物理探索 · 伽利略变换**：伽利略变换实验室、相对速度小课堂（单画布多坐标系叠加、平滑切换动画）。
- **小学奥数 · 行程问题**：流水行船问题（顺逆流与漂流参照系）、火车过桥与错车（过桥全程与双车错车相对速度）。
- **小学奥数 · 几何模型**：等积变形与拉伸（平行线顶点拖拽面积恒定）、梯形蝴蝶模型（四子三角形面积与等积实证）。
- **小学奥数 · 数论与计数**：鸡兔同笼与假设法（趣味金鸡独立/抬腿法动画）、抽屉原理与最不利原则（鸽巢定理动态高亮）。

## 目录结构

```text
.
├── index.html                    # 课件集合首页（搜索/分页/知识点归组）
├── viewer.html                   # 统一全屏播放壳（顶栏带返回首页）
├── demos/
│   ├── galilean-transform/       # 专题：伽利略变换
│   │   ├── galileo-lab/          # demo：伽利略变换实验室
│   │   └── relative-velocity/    # demo：相对速度小课堂
│   ├── boat-and-stream/          # demo：流水行船问题
│   ├── train-crossing/           # demo：火车过桥与错车
│   ├── equal-area/               # demo：等积变形与拉伸
│   ├── butterfly-model/          # demo：梯形蝴蝶模型
│   ├── chicken-rabbit/           # demo：鸡兔同笼与假设法
│   └── pigeonhole/               # demo：抽屉原理与最不利原则
├── docs/demo-design-guideline.md # 视觉交互规范
├── LICENSE                       # MIT License
└── .gitignore
```

## 本地打开与体验

无需 npm 或构建工具：直接用浏览器打开根目录 `index.html`，或在根目录启动任意静态文件服务器后访问。所有页面链接均为相对路径，适用于仓库子路径部署。

## 部署到 GitHub Pages

仓库默认分支为 `main`，将仓库推送至 GitHub 后，进入 **Settings → Pages**，把 Source 设为 **Deploy from a branch**，Branch 选 `main`、folder 选 `/ (root)`。推送到 `main` 后 GitHub 会自动发布根目录。发布完成后访问：<https://miuzel.github.io/adela-demos/>。

## 贡献与致谢

欢迎提交 Issue、改进文案、修复交互或增加适合儿童的例子。请保持页面轻量、中文清晰、操作反馈明确，并遵循 [演示视觉交互规范](docs/demo-design-guideline.md)。感谢所有帮助孩子亲近科学的老师、家长与开源贡献者。

## 许可与公益声明

本项目采用 [MIT License](LICENSE)，Copyright (c) 2026 miuzel。你可以免费使用、修改和分享；如用于教学，欢迎保留项目来源。课件仅用于教育演示，不替代正式教材。

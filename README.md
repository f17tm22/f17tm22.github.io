# f17tm22.github.io

Merino Mo 的个人主页 — 二次元技术宅的土木编程小站 🏗️🌸

## 站点结构

```
├── index.html          # 主页入口
├── assets/
│   ├── css/style.css   # 全局共享样式
│   └── images/         # 图片资源
└── pages/
    ├── resume.html     # 个人介绍
    ├── blog.html       # 个人记录
    ├── tools.html      # 小工具罗列
    ├── solver.html     # 方程求解器
    ├── concrete_grade_table.html  # 混凝土等级表
    ├── seismic_analysis.html      # 地震反应谱分析 (Vue + ECharts + Konva)
    ├── demo.html       # 项目演示 (Canvas)
    └── GSAP_demo.html  # GSAP 物理碰撞动画
```

## 技术栈

- 纯静态 HTML + CSS
- 部分页面使用 Vue 3、ECharts、GSAP、Konva.js
- 托管于 GitHub Pages

## 本地运行

```bash
# 使用 VS Code Live Server 或任何静态服务器
npx serve .
```

# 王妍琳 — 作品集（中文版）

个人作品集网站。单页、纯静态 HTML（内联 CSS/JS，无需构建）。

**定位：** 内容增长 × AI 生产 —— 面向科技公司的内容营销、社媒运营与 AIGC 工作流。

## 页面结构

首屏 · 关于 · 经历（可展开、公司 logo 墙）· 01 AIGC（自研 AI 内容 agent + 脚本工具、视频展示、真实内容数据看板）· 02 内容营销（IP 打造、活动营销、商业产品）· 03 社交媒体（果壳 & 36氪）· 技能 · 版权与插画（双排跑马灯、作品链接）· 联系方式

## 语言

- `index.html` —— 中文版（默认入口）
- `index.en.html` —— 英文版
- 两版右上角均有 `中文 / EN` 切换入口，互相跳转

## 部署

静态站点。以仓库根目录作为站点根，`index.html` 为入口页。可直接部署到 GitHub Pages / Cloudflare Pages。

## 资源目录

- `assets/works/` —— 插画与内容缩略图（链接到文章）
- `assets/cm/` —— 内容营销案例图
- `assets/sns/` —— 社媒手机样机图
- `assets/logos/` —— 公司 logo
- `assets/video/` —— 短视频与封面
- `assets/dashboard.jpg` —— 内容数据看板截图
- `assets/icon.png` —— 站点图标 / favicon

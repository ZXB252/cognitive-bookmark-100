# 100 本认知书签

一个适合 iPhone 添加到主屏幕的静态阅读打卡网页，内置 100 本提升认知的书目、核心观点、真实世界例子和每日打卡问题。

## 本地打开

直接打开 `index.html` 即可使用。阅读进度、笔记和打卡日期保存在当前浏览器的 `localStorage`。

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 上传本目录中的所有文件。
3. 进入仓库 `Settings` → `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main` 和 `/root`，保存。
6. 用 iPhone Safari 打开 Pages 地址，点分享按钮，选择“添加到主屏幕”。

## 文件

- `index.html`：页面结构和 iOS Web App 元信息。
- `styles.css`：移动端优先的界面样式。
- `app.js`：100 本书数据、搜索筛选、打卡和本地笔记。
- `manifest.json`：PWA 名称、主题色和图标。

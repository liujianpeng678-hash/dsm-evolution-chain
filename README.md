# DSM 进化链 · 题库地图网站

二次函数 / 导数等知识点的**进化链可视化网站**：从母题出发，按进化算子（条件显→隐、具体→参数、加分类讨论、加中间量、单知识点→组合…）生成问题进化链，配套题库目录树（正式库）、节点详情（题目+解析）、闯关模式与页面标注评论功能。

## 功能

- **目录树**：正式库 → 学科 → 学段 → 年级 → 章节 → 知识点 → 问题（问题叶子挂进化链）
- **进化链画布**：29 条链 / 11 个问题分组，母题 root 起步，边标注进化算子，节点可拖拽、滚轮缩放
- **节点详情**：点击节点查看完整题目 + 解析（question/analysis）
- **标注评论**：右下角「✏️ 标注」——框选/箭头/评论，导出 JSON 反馈给 AI 快速修改
- **闯关模式**：?game=1 进入

## 数据文件

- `evolution-chain-viz.html`：渲染引擎（逻辑）
- `data/catalog.js`：正式库目录树（问题叶子挂链）
- `data/chains.js`：进化链定义（nodes/edges）
- `data/nodeDetails.js`：节点题目与解析
- `data/problemGroups.js`：问题分组

## 本地使用

直接打开 `evolution-chain-viz.html` 即可（数据已外置为同目录 `data/*.js`，file:// 下可用，无需服务器）。

## 桌面端

- 本仓库发布为 GitHub Pages：`https://liujianpeng678-hash.github.io/dsm-evolution-chain/evolution-chain-viz.html`
- 桌面 APP（Pake 打包，独立窗口）：见 Release

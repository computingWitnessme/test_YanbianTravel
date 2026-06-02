# 延边之旅 · 项目说明

## 项目简介
延边长白山三日行程规划的静态网站。

## 技术栈
- 纯 HTML + CSS 单页应用
- 无构建工具 / 无依赖
- 字体：Google Fonts (Noto Sans SC)

## 目录结构
```
/
├── index.html    # 主页面（所有内容）
├── .gitignore    # Git 忽略规则
├── AGENTS.md     # 本文件
└── .git/         # Git 仓库
```

## 开发命令
- **本地预览**：直接用浏览器打开 `index.html`
- **部署方式**：推送到 GitHub 后通过 GitHub Pages 部署

## 编码约定
- 样式写在 `<style>` 标签内，不使用外部 CSS 文件
- 颜色使用 CSS 变量（`:root` 中定义）
- 中文文本使用简体中文
- 响应式设计优先，移动端适配

## Git 约定
- 分支命名前缀：`codex/`
- 提交信息格式：`类型: 简短描述`（如 `feat: 添加行程页面`）

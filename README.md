# plain

一个用于学习 Git 与 GitHub 的纯静态练习项目。

## 项目简介

本项目只有一个 `index.html`，包含个人介绍、课程清单和一个点赞按钮。它不需要 npm、不需要打包，直接双击用浏览器打开即可预览，因此非常适合用来练习 Git 的日常操作：

- 创建仓库并与远程关联
- 修改文件后提交（commit）
- 推送到 GitHub（push）
- 新建、合并、删除分支
- 在 GitHub 上开启 Pages 发布静态页面

## 目录结构

```
plain/
├── index.html   # 纯静态页面（内联样式与脚本，无外部依赖）
└── README.md    # 项目说明
```

## 本地预览

直接用浏览器打开 `index.html` 即可，无需安装任何依赖或启动服务。

## 发布到 GitHub Pages

仓库 → Settings → Pages → Branch 选择 `main` → `/ (root)` → Save。

## 更新记录

| 日期 | 说明 |
| --- | --- |
| 2026-11-02 | 仓库迁移至 plain，新增本 README |

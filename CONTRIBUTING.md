# 贡献指南（简明版）

欢迎贡献！（拼写更正、校对、注释、翻译、排版改进等）

仓库结构约定（请遵守以便自动生成目录和在线展示）：
- docs/
  - index.html  （网站入口）
  - _sidebar.md （侧边栏目录）
  - content/
    - 卷01-卷名/
      - 001.md
      - 002.md
    - 卷02-卷名/

文件命名与编码：
- 文件名请使用 UTF-8 编码，章节文件名以三位数字开头（例如 `001.md`、`002.md`），以保证排序正确。
- 每个章节文件建议以下面模板开始（YAML front-matter 是可选的）：

示例章节模板：
```
---
title: 第一章 标题
author: 作者姓名
volume: 1
chapter: 1
lang: zh
---

（在此处粘贴章节正文，UTF-8 编码）
```

如何贡献：
1. 在 GitHub 上直接编辑（适合少量改动）：打开对应文件，点编辑并提交。若修改较多建议创建新分支并发起 PR。
2. 使用 GitHub Desktop（推荐一次性上传多文件）：
   - 在 GitHub 页面点击 "Code" -> "Open with GitHub Desktop" 克隆仓库到本地。
   - 在本地将 `docs/content/` 目录替换为你整理好的 7 卷文件夹，然后在 GitHub Desktop 中 Commit 并 Push。
   - 在 GitHub 页面为你的分支创建 Pull Request，填写变更说明。

版权与许可：
- 本仓库文本采用 CC BY‑SA 4.0。提交贡献即表示你同意以兼容的方式授予本项目必要的许可（请不要提交存在版权问题的材料）。

感谢你的贡献！
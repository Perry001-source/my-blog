---
title: "第一篇文章：用 Hugo 发布博客"
date: 2026-06-01T10:45:00+08:00
draft: false
tags: ["Hugo", "Cloudflare Pages", "GitHub"]
---

这是这个静态博客的第一篇文章。

整个流程很直接：本地用 Markdown 写文章，Hugo 负责生成静态页面，代码推送到 GitHub 后，Cloudflare Pages 会自动拉取仓库并部署。

以后新增文章时，只需要在 `content/posts/` 目录里创建新的 Markdown 文件，然后提交并推送到 GitHub。

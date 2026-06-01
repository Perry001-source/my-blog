# 我的 Hugo 博客

这是一个使用 Hugo 生成、计划通过 Cloudflare Pages 部署的静态博客。

## 本地预览

```sh
hugo server
```

浏览器打开 Hugo 输出的本地地址，通常是 `http://localhost:1313/`。

## 构建

```sh
hugo --gc --minify
```

## Cloudflare Pages 设置

- Framework preset: `Hugo`
- Build command: `hugo --gc --minify`
- Build output directory: `public`
- Hugo version: `0.162.0`

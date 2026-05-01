# Orange-es 的个人博客

基于 [Hugo](https://gohugo.io/) 引擎与 [PaperMod](https://github.com/adityatelange/hugo-PaperMod) 主题搭建的个人博客。

## 🌐 访问地址
**[https://orange-es.github.io/](https://orange-es.github.io/)**

## 🚀 快速开始

### 1. 撰写新文章
在本地目录 `content/posts/` 下新建 Markdown 文件，例如 `my-post.md`：

```markdown
---
title: "文章标题"
date: 2024-05-01
draft: false
tags: ["标签1", "标签2"]
---
这里写正文内容...
```

### 2. 发布更新
在本地终端执行以下命令即可触发 GitHub Actions 自动部署：

```bash
git add .
git commit -m "新增文章: 文章标题"
git push origin main
```

## 🛠️ 技术架构
- **静态网站生成器**: Hugo
- **主题**: PaperMod
- **部署平台**: GitHub Pages
- **自动化工具**: GitHub Actions (自动克隆主题并构建)

---
*Powered by Orange-es*

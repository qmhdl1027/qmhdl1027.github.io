---
title: "Hello Hugo - 博客首篇文章"
date: 2026-09-02T08:40:00+08:00
tags: ["公告", "Hugo", "PaperMod"]
draft: false
---

欢迎来到我的新博客！这是使用 Hugo + PaperMod 主题搭建的第一篇文章。

## 关于本站

本博客基于以下技术栈：

- **Hugo** - 世界上最快的网站构建框架
- **PaperMod** - 简洁优雅的 Hugo 主题
- **GitHub Pages** - 免费托管
- **GitHub Actions** - 自动构建部署

## 工作流程

```
AI 写 Markdown → 上传到 GitHub → Actions 自动构建 → GitHub Pages 发布
```

1. 文章用 Markdown 格式书写
2. 文件放在 `content/posts/` 目录下
3. 提交到 GitHub 后自动触发部署
4. 1-2 分钟后访问 `qmhdl1027.github.io` 就能看到新文章

## Front-matter 示例

每篇文章开头需要这样的元信息块：

```yaml
---
title: "文章标题"
date: 2026-09-02T15:30:00+08:00
tags: ["标签1", "标签2"]
draft: false
---
```

- `title` - 文章标题
- `date` - 发布时间（ISO 8601 格式）
- `tags` - 标签数组
- `draft: false` - 设为 `true` 时为草稿，不会发布

## 后续计划

- 技术笔记
- 项目实践记录
- 生活随笔
- 工具推荐

敬请期待！

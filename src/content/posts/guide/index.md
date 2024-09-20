---
title: Fuwari 主题的简单指南
published: 2024-09-05
description: "如何使用这个博客模板"
image: "./cover.jpeg"
tags: [Markdown, 教程]
category: Fuwari
draft: false
---

> 封面图片来源: [C站](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208fc754-890d-4adb-9753-2c963332675d/width=2048/01651-1456859105-(colour_1.5),girl,_Blue,yellow,green,cyan,purple,red,pink,_best,8k,UHD,masterpiece,male%20focus,%201boy,gloves,%20ponytail,%20long%20hair,.jpeg)

这个博客模板是用 [Astro](https://astro.build/)构建的。对于本指南中未提及的内容，你可以在 [Astro 文档](https://docs.astro.build/zh-cn/getting-started/)中找到答案。

文章开头YAML模板

```yaml
---
title: Fuwari 主题的简单指南
published: 2024-09-05
description: "如何使用这个博客模板"
image: "./cover.jpeg"
tags: Markdown
category: Fuwari
draft: false
---
```

| 属性     | 说明                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 标题                                                                                                                                                                                      |
| `published`   | 帖子发布日期                                                                                                                                                                     |
| `description` | 帖子的简短描述，会显示在索引页面                                                                                                                                  |
| `image`       | 帖子的封面图片路径。<br/>1.以 `http: //` 或 `https: //` 开头：使用网页图片<br/>2.以 `/` 开头：用于 `public` 目录中的图片<br/>3.不带任何前缀：相对于此 Markdown 文件的路径 |
| `tags`        | 标签                                                                                                                                                                                       |
| `category`    | 分类                                                                                                                                                                                 |
| `draft`        | 决定此文章是否为草稿                                                                                                                                       |

## 文章文件的位置

你的文章文件应该放置在`src/content/posts/`目录中。你还可以创建子目录以更好地组织你的文章和资产。

```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.png
    └── index.md
```

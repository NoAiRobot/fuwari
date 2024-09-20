---
title: Markdown 扩展特性
published: 2024-09-05
description: Fuwari主题支持多种Markdown扩展请多多尝试
tags: [Markdown, 教程]
category: Fuwari
draft: false 
language: zh_CN
---

## GitHub 仓库卡片
您可以添加动态卡片，链接到GitHub仓库，在页面加载时，仓库信息从GitHub API中拉取。

使用语法格式 `::github{repo="<owner>/<repo>"}`.创建一个GitHub仓库卡片。

::github{repo="saicaca/fuwari"}

## 警告框

支持以下类型的警告框：

- `note`（注意）
-  `tip`（提示）
-  `important`（重要）
-  `warning`（警告）
-  `caution`（注意）

:::note
提醒用户在阅读时候应该注意的信息
:::

:::tip
给阅读中的用户提示有用信息
:::

:::important
用于告诉用户一些重要的内容
:::

:::warning
当执行有风险的操作时应警告用户不要误操作
:::

:::caution
！注意 ！注意 ！注意 该操作有可能会导致严重后果
:::

```markdown
:::note or tip or important or warning or caution
警告框正文
:::
```

警告框的标题可以自定义

:::tip[标题可以自定义]
这是一个自定义标题的警告框
:::

```markdown
:::note[MY CUSTOM TITLE]
This is a note with a custom title.
:::
```

> [!TIP]
> 支持[GitHub语法](https://github.com/orgs/community/discussions/16925) 

```markdown
> [!TIP]
> 支持GitHub语法
```
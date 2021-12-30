---
title: "在文章中嵌入视频效果"
date: 2021-12-29T22:54:29+08:00
lastmod: 2021-12-29T23:23:40+08:00
draft: false
description: "这篇文章展示了文章嵌入Youtube和Bilibili视频的语法。"
featuredImage: "featured-image.jpg"

tags: ["Markdown", "HTML", "视频", "video"]
categories: ["Markdown教程"]
---

**DoIt** 主题模板中嵌入Youtube和Bilibili视频的语法学习。

<!--more-->


### 在文章中插入youtube的视频

一个Youtube视频示例
```markdown
{{</*  youtube id="2GYuLgzfMag" autoplay="true" */>}}
或者
{{</*  youtube 2GYuLgzfMag */>}}
```
呈现的显示效果如下：
{{< youtube 2GYuLgzfMag >}}


### 在文章中插入Bilibili的视频

一个Bilibili视频示例
```markdown
{{</* bilibili BV17P4y1J7U7 */>}}
或者
{{</* bilibili id=BV17P4y1J7U7 */>}}
```
呈现的显示效果如下：
{{< bilibili BV17P4y1J7U7 >}}
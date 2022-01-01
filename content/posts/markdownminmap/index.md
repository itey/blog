---
title: "用Markdown几分钟生成思维导图"
date: 2022-01-01T10:40:24+08:00
lastmod: 2022-01-01T10:40:24+08:00
draft: false
description: "这篇文章展示了文章嵌入思维导图的语法。"
featuredImage: "featured-image.jpg"

tags: ["Markdown", "思维导图", "mindmap", "脑图"]
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
---
title: "在文章中嵌入互动式地图效果"
date: 2021-12-31T22:54:29+08:00
lastmod: 2021-12-31T23:23:40+08:00
draft: false
description: "这篇文章展示了互动式地图的语法。"
featuredImage: "featured-image.jpg"

tags: ["Markdown", "map", "地图"]
categories: ["在线教程"]
series: ["Markdown教程"]

---

**DoIt** 主题模板中嵌入互动式地图的语法学习。

<!--more-->

### 一个简单的互动式地图示例:

```markdown
{{</* mapbox 121.485 31.233 12 */>}}
或者
{{</* mapbox lng=121.485 lat=31.233 zoom=12 */>}}
```
呈现的输出效果如下:

{{< mapbox 121.485 31.233 10 >}}
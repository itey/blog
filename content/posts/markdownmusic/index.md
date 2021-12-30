---
title: "在文章中嵌入音乐和音乐列表效果"
date: 2021-12-29T22:54:29+08:00
lastmod: 2021-12-29T23:23:40+08:00
draft: false
description: "这篇文章展示了音乐和音乐列表的语法。"
featuredImage: "featured-image.jpg"

tags: ["Markdown", "music", "mp3", "QQ音乐", "网易音乐"]
categories: ["Markdown教程"]
---

**DoIt** 主题模板中嵌入音乐和音乐列表的语法学习。

<!--more-->

### 自定义本地音乐
一个使用自定义音乐 URL 的 `music` 示例:
```markdown
{{</* music url="/music/Wavelength.mp3" name=Wavelength artist=oldmanyoung cover="/images/Wavelength.webp" */>}}
```
呈现的输出效果如下:

{{< music url="/music/Wavelength.mp3" name=Wavelength artist=oldmanyoung cover="/images/Wavelength.webp" >}}

### 音乐平台的音乐URL自动识别
用来自动识别的音乐平台 URL, 支持网易音乐`netease`,QQ音乐`tencent`平台。

一个使用音乐平台 URL 的自动识别的 music 示例:

```markdown
{{</* music auto="https://music.163.com/#/playlist?id=60198" */>}}
或者
{{</* music "https://music.163.com/#/playlist?id=60198" */>}}
```
呈现的输出效果如下:
{{< music auto="https://music.163.com/#/playlist?id=60198" >}}

### 自定义音乐平台的音乐


一个使用自定义音乐平台的 `music` 示例:


`music` shortcode 有以下命名参数来使用自定义音乐平台:

* **server** *[必需]* (**第一个**位置参数)

    [网易音乐`netease`, QQ音乐`tencent`,]

    音乐平台.

* **type** *[必需]* (**第二个**位置参数)

    [`song`, `playlist`, `album`, `search`, `artist`]

    音乐类型.

* **id** *[必需]* (**第三个**位置参数)

    歌曲 ID, 或者播放列表 ID, 或者专辑 ID, 或者搜索关键词, 或者创作者 ID.

```markdown
{{</* music server="netease" type="song" id="1868553" */>}}
或者
{{</* music netease song 1868553 */>}}
```

#### 网易音乐呈现的输出效果如下:
```markdown
{{</*  music netease song 1868553 */>}}
```
呈现的输出效果如下:
{{< music netease song 1868553 >}}
#### QQ音乐呈现的输出效果如下:
```markdown
{{</*  music netease song 1868553 */>}}
```
呈现的输出效果如下:
{{< music tencent song 002COKKN3dl6dW >}}

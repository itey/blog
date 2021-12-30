---
title: "在文章中嵌入各种提示横幅"
date: 2021-12-29T22:54:29+08:00
lastmod: 2021-12-29T23:23:40+08:00
draft: false
description: "这篇文章展示了文章嵌入各种提示横幅的语法。"
featuredImage: "featured-image.jpg"

tags: ["Markdown", "HTML"]
categories: ["Markdown教程"]
---

在文章中嵌入包括引用、示例、注意、摘要、提醒、状态等提示性条幅显示效果。

<!--more-->


以下有 **12** 种 帮助你在页面中插入提示的横幅.

*支持 Markdown 或者 HTML 格式.*
### 【注意】横幅示例：

{{< admonition note "注意" open >}}
这里是关于 **注意** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition note "注意" open */>}}
这里是关于 **注意** 的说明文字
{{</* /admonition */>}}
```
### 【摘要】横幅示例：
{{< admonition abstract "摘要" open >}}
这里是关于 **摘要** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition abstract "摘要" open */>}}
这里是关于 **摘要** 的说明文字
{{</* /admonition */>}}
```
### 【信息】横幅示例：
{{< admonition info "信息" open >}}
这里是关于 **信息** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition info "信息" open */>}}
这里是关于 **信息** 的说明文字
{{</* /admonition */>}}
```
### 【技巧】横幅示例：
{{< admonition tip "技巧" open >}}
这里是关于 **技巧** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition tip "技巧" open */>}}
这里是关于 **技巧** 的说明文字
{{</* /admonition */>}}
```
### 【成功】横幅示例：
{{< admonition success "成功" open >}}
这里是关于 **成功** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition success "成功" open */>}}
这里是关于 **成功** 的说明文字
{{</* /admonition */>}}
```
### 【问题】横幅示例：
{{< admonition question "问题" open >}}
这里是关于 **问题** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition question "问题" open */>}}
这里是关于 **问题** 的说明文字
{{</* /admonition */>}}
```
### 【警告】横幅示例：
{{< admonition warning "警告" open >}}
这里是关于 **警告** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition warning "警告" open */>}}
这里是关于 **警告** 的说明文字
{{</* /admonition */>}}
```
### 【失败】横幅示例：
{{< admonition failure "失败" open >}}
这里是关于 **失败** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition failure "失败" open */>}}
这里是关于 **失败** 的说明文字
{{</* /admonition */>}}
```
### 【危险】横幅示例：
{{< admonition danger "危险" open >}}
这里是关于 **危险** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition danger "危险" open */>}}
这里是关于 **危险** 的说明文字
{{</* /admonition */>}}
```
### 【Bug】横幅示例：
{{< admonition bug "Bug" open >}}
这里是关于 **Bug** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition example "Bug" open */>}}
这里是关于 **Bug** 的说明文字
{{</* /admonition */>}}
```
### 【示例】横幅示例：
{{< admonition example "示例" open >}}
这里是关于 **示例** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition example "示例" open */>}}
这里是关于 **示例** 的说明文字
{{</* /admonition */>}}
```
### 【引用】横幅示例：
{{< admonition quote "引用" open >}}
这里是关于 **引用** 的说明文字
{{< /admonition >}}
```markdown
{{</* admonition quote "引用" open */>}}
这里是关于 **引用** 的说明文字
{{</* /admonition */>}}
```  

 ---
 
### 一个完整的提示横幅示例和参数说明:
```markdown
{{</* admonition type=tip title="This is a tip" open=false */>}}
一个 **技巧** 横幅
{{</* /admonition */>}}
或者
{{</* admonition tip "This is a tip" false */>}}
一个 **技巧** 横幅
{{</* /admonition */>}}
```

呈现的输出效果如下:

{{< admonition tip "This is a tip" false >}}
一个 **技巧** 横幅
{{< /admonition >}}


命名参数说明:

* **type** *[必需]* (**第一个**位置参数)

    横幅的类型, 默认值是 `note`.

* **title** *[可选]* (**第二个**位置参数)

    横幅的标题, 默认值是 **type** 参数的值.

* **open** *[可选]* (**第三个**位置参数) 

    横幅内容是否默认展开, 默认值是 `true`.
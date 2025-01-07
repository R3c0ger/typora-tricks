---
title: Typora 学习索引 - 杂项
urlname: typora-tricks-5
mermaid: true
cover: 2025/01/typora-tricks-5/cover.png
excerpt: '这里用来放置一些写不了太多、不方便归类到前面几个部分的内容。'
categories:
  - 技术文章
tags: [markdown, typora, learning, yaml, mermaid, typesetting]
date: 2025-01-07 16:43:31
---

# Typora 学习索引 - 杂项

为了便于阅览，我将该文章分成若干部分，汇总如下：

<!-- 知乎 -->
[Typora 有点儿深度使用的学习索引 - 知乎](https://zhuanlan.zhihu.com/p/596847931)

<!-- github -->
[Typora 有点儿深度使用的学习索引 - 前言、索引与目录 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-0/)

---

这里用来放置一些写不了太多、不方便归类到前面几个部分的内容。

（1）可用来装作首行缩进的全角空白符：
　　就在这一行的最前面捏，宽度为 1em，URL 编码是`%E3%80%80`

（2）参考链接（鼠标放上去会有个提示消息）：`[<text>][<tag>]`

This is [an example][id] reference-style link.

[id]: http://example.com/  "Optional Title Here"

```markdown
This is [an example][id] reference-style link.

[id]: http://example.com/  "Optional Title Here"
```

p.s. Typora 的链接包含：

- 行内链接：`[<text>](<URL>)` 
- 内链（锚点）：`[<text>](#<tag or title>)` 
- 参考链接
- URL
- 图片：`![<pic title>](<addr> "<Optional title>")`
- HTML 的 `<a>` 标签
- 引用外部文件

（3）绘图

参见 [Draw Diagrams With Markdown](https://support.typora.io/Draw-Diagrams-With-Markdown/)。

（4）[YAML Front Matter](https://jekyllrb.com/docs/front-matter/)

学习 YAML 语法：[YAML 入门教程](https://www.runoob.com/w3cnote/yaml-intro.html)

用于为文档添加元数据，可以对导出进行一定的设置，也可以用于 Hexo 等静态网站生成器。

## 彩蛋

![](img/cover.png)

- 彩蛋图片：
  - 作者：方方土 (user-id: 66422499)
  - 来源：pixiv ID: 118095113
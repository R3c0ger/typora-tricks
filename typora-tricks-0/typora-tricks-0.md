---
title: Typora 有点儿深度使用的学习索引 - 前言、索引与目录
urlname: typora-tricks-0
mermaid: true
cover: 2025/01/typora-tricks-0/cover.png
excerpt: '深度使用 Typora 和 Markdown 的一些奇技淫巧和心得。'
categories:
  - 技术文章
tags: [markdown, typora, learning, navigation]
date: 2025-01-03 11:43:56
---

# Typora 有点儿深度使用的学习索引 - 前言、索引与目录

## 前言

> 因为 Markdown 这个语言很尴尬，再往上一点，哎，$\LaTeX$，可能有点实力，还能操作一下；再往下，Microsoft Office Word，人家就纯属所见即所得的，自己也知道自己格式需要调整。但 Markdown？上不去又下不来。它觉得 Word 不配和自己放一块，但是呢，它想上去，它又上不去，想操作又操作不起来，卡在这儿了，掉下去了又不值得。 

以上一段文字纯属扯淡。事实上现在这三个玩意我都在用，我手上都有这三个家伙对应的（东拼西凑的）模板，唯一要考虑的就是针对不同的需求去挑选合适的工具罢了。你要问我这三个用哪个比较好？我的评价是：益研顶针，鉴定为有益于你的科研学习就行，反正我也说不出什么干货了，知乎上这种“跨作品比战力”的问题也是一抓一大把。

目前我撰写各类文档最大的困难，不是工具不好用，而是根本不会用。回过头来看我十几年玩电脑的历史，我尴尬地发现自己其实啥都不会。Word 么，知道一些操作，但是除了高中学过一点（已经忘了）之外我还是啥都不会；$\LaTeX$ 么，我只能说我连入门都不算。上不去下不来的其实是我（笑），于是暂时还是好好用一阵子 md 吧，毕竟优点还蛮多的，最主要的是学习成本可能是最小的。

以下很多内容其实只服务于我的强迫症，虽然我也没去医院看过这到底是不是强迫症，所以“强迫症”这三个字我也没写进标题里。为什么我要在开头提到“上不去又下不来”呢？就是因为我想满足我的强迫症，但 Markdown 本来又不是为了干这种破事的，本来简简单单写个文档就行了的，但是我又非要想用简单的语言来搞复杂的事情，让 Markdown 和 Typora 满足我那“上得去又下得来”的 hentai 想法，于是我就会百度到很多有点儿深度的用法。这些用法或技巧或曰“奇技淫巧”将会被记录于此，分享给大家。

为什么题目是“索引”呢？是因为我这里很多的用法很肤浅，而且文章中很多干货都是从网上搜索而来的，所以这篇文章里更多的还是罗列一些超链接，将一些有用的文章和实用的网站分享出来，所以只能算是个索引。

我所使用的编辑器是 Typora + VS Code，版本为 1.0.4，操作系统为 Windows 10。

源文件已上传至 Github：

<!-- github -->
[R3c0ger/typora-tricks: Typora 有点儿深度使用的学习索引](https://github.com/R3c0ger/typora-tricks)

为了便于阅览，我将该文章中我自己汇总的内容分成若干篇文章，链接都放在下面内容中了，这可不是水文章啊（笑）

## 学习网站

### Markdown 语法学习

- [Markdown 入门教程](https://www.imooc.com/wiki/markdownlesson)
- [markdown语法大全](https://www.cnblogs.com/miki-peng/p/12502985.html)：这篇文章不仅很全，而且记录了很多很多颜色和 Emoji。
- [MarkDown高阶语法手册](https://mp.weixin.qq.com/s/L9WI8zMlPWdqUsyh36vUhA)
- [Typora Support](https://support.typora.io/)：万法归宗，能使用魔法的还是尽量看官方的文档吧
- [GFM’s spec](https://github.github.com/gfm/)：~~Github 风味降价~~ 不是，GitHub 风格的 Markdown 语法规范文档，文档明确（unambiguously）指定 Markdown 语法，这也正是 Typora 严格模式所支持的语法。
- [Typora 完全使用详解](https://sspai.com/post/54912/)
- [Typora进阶学习](https://www.jianshu.com/p/28d321ffddac)

### Typora 支持 MathJax 公式书写

- [Math and Academic Functions](https://support.typora.io/Math/)：官方教程，得会科学上网
- [Supported TeX/LaTeX commands](https://docs.mathjax.org/en/latest/input/tex/macros/index.html)：MathJax 所支持的语法是 $\LaTeX$ 的子集，可以在这里查找得到。
- [MarkDown公式指导手册](https://www.jianshu.com/p/53cc67f6c832)
- [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference/15077#15077)
- [Typora中一些常用的latex公式](https://www.jianshu.com/p/8fed0e1a9692)
- [【Typora】超全数学公式全集（没错，你想要的就在这里）](https://zhuanlan.zhihu.com/p/165342174)
- [在MathJax中显示长除法符号的方法)\~\~\~\~\~\~](https://qa.1r1g.com/sf/ask/1600744981/)
- [TeX 的宏 \ 第一集](http://garfileo.is-programmer.com/2010/5/21/macro-of-tex.18296.html)
- [TeX 宏编程技巧之定界的宏参数](https://zhuanlan.zhihu.com/p/484092340)
- [知乎上的公式是怎么打出来的？](https://www.zhihu.com/question/31298277/answer/275151599)
- [mhchem](https://mhchem.github.io/MathJax-mhchem/)：Typora 所支持的 mhchem for MathJax 化学表达式手册

### Typora 同样支持 Mermaid

- [About Mermaid](https://mermaid.js.org/intro/)：Mermaid 官网，可以直接开始学习。
- [一款优雅的流程图利器-Mermaid 使用指南](https://blog.csdn.net/qq_42818403/article/details/122599306)：这个么，好像类似于官网的翻译。

### 有关 Typora 的样式修改

- [CSS 教程](https://www.w3school.com.cn/css/index.asp)：改样式的话，肯定得学一点前端三剑客的知识啦~
- [Write Custom Theme_zh](https://theme.typora.io/doc/zh/Write-Custom-Theme/)：官方教程
- [Typora任意更改样式](https://blog.csdn.net/weixin_45817496/article/details/115867361)
- [自定义Typora的样式(更新 1 2021-7-14)](https://wap.sciencenet.cn/home.php?mod=space&uid=1213210&do=blog&id=1295427)
- [Typora 伪装 LaTeX 中文样式主题](https://github.com/Keldos-Li/typora-latex-theme)
- [Typora自动编号功能——最强版](https://blog.csdn.net/qq_33159059/article/details/87910522)

### 规范化 Markdown 写作参考

- [《中文文案排版指北》](https://sspai.com/link?target=https%3A%2F%2Fgithub.com%2Fmzlogin%2Fchinese-copywriting-guidelines)、[少数派写作排版指南](https://sspai.com/post/37815)：写 MD 可以参照的较为通用的排版方式（加空格那种还是 Obsidian 加个插件方便一点）
- [中华人民共和国国家标准GB/T15834-2011标点符号用法](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=22EA6D162E4110E752259661E1A0D0A8)：为什么不参照国家的标准呢？（尽管我这篇文章也没遵循什么标准……）
- [教育部：夹用英文的中文文本的标点符号用法（草案）](http://www.moe.gov.cn/ewebeditor/uploadfile/2015/01/13/20150113092346124.pdf)
- [【译】Google Markdown书写风格指南](https://www.jianshu.com/p/3beac9fd6496)
- [《中文技术文档写作规范》](https://github.com/ruanyf/document-style-guide)
- [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)
- [Markdown 简体中文与西文混排要点](https://github.com/selfteaching/markdown-writing-with-mixed-cn-en)
- [W3C：中文排版需求](https://w3c.github.io/clreq/)

### 其他杂项

- [Typora快捷键汇总](https://zhuanlan.zhihu.com/p/592538886)
- [Typora快捷键设置](http://events.jianshu.io/p/4d8f04352dc8)
- [typora图片自动左（右）对齐](https://www.cnblogs.com/charlotteForever/p/15823838.html)
- [将图片内嵌入Markdown文档中](https://blog.csdn.net/u010158659/article/details/61197893)
- [markdown中对齐方式怎样设定？比如怎样将文字右对齐？](https://www.zhihu.com/question/21160553)
- [YAML 入门教程](https://www.runoob.com/w3cnote/yaml-intro.html)：学习 YAML 语法

## 工具网站

### 服务 Markdown 写作

- [Mermaid~v9.3.0~ Live Editor](https://mermaid.live/edit#pako:eNptkLFugzAQhl_FubUGGQwBe0hVqUNTqVO3isWCIyCBnTq2Wop49xpot3g6-b7v193NUJsGQcINPz3qGp97dbFqrDQJ72noa4xOp4dX02lJXnAYDFlrSjrzRZRFMhn_eBfesVrpFSEdKktG_EPXXhTQaHNCcL_blJw3Y6ODdriPn0mLOJCLReUOQGFEO6q-CVvMq1CB63DECmQoG2yVH1wFlV4Cqrwz75OuQTrrkYK_Nsr9Lw2yVcMt_GLTO2Pf9stsB6JwVRrkDN8gMxHnQpSZKBgTaVHwjMIEMhGxyIoyK_jxyDlnrFwo_BgTYpM4LQRLRCqynJVlzviW97E110GWX5I8d18)：在线编辑各种 Mermaid 图，好像还是得自己手动敲代码……
- [Create LaTeX tables online – TablesGenerator.com](https://www.tablesgenerator.com/)：画 $\LaTeX$、HTML 等的表格的；
- [Convert Excel to LaTeX Table](https://tableconvert.com/excel-to-latex)：把 Excel 转为 $\LaTeX$、HTML、SQL 等表格的。
- [quiver: a modern commutative diagram editor](https://q.uiver.app/)：画交换图的，Typora 里面好像还不能画曲线，只能画直箭头什么的……
- [在线LaTeX公式编辑器-编辑器](https://www.latexlive.com/##)
- [论文工具](https://laorange.github.io/paper-assistant/)：可以处理从 PDF 复制的文本，去除多余换行，中英文标点转换，规范中文排版，功能强大
- [Copy++](https://copyplusplus.tk)：提供一个软件，可以去除从 PDF、CAJ 复制的内容的换行与空格，还可以进行翻译，未来还有更多功能
- [carbon](https://carbon.now.sh/)：代码美化

### Markdown 其他应用

**1. 微信公众号等推文**

- [使用 Typora 一次性搞定公众号写作与排版](https://sspai.com/post/40524)
- [微信 Markdown 编辑器 | Doocs 开源社区](https://doocs.github.io/md/)
- [墨滴](https://product.mdnice.com/membership/product/)
- [Md2All](http://md.aclickall.com/)
- [Markdown Here](http://markdown-here.com/index.html)
- [Markdown 在线编辑器· 开发者工具箱](https://markdown.devtool.tech/app)
- [可能吧公众号排版器](https://knb.im/mp/)

**2. 写 PPT**

- https://marp.app/：VSCode 也有这个插件
- https://sli.dev/

**3. 写简历**

- [Markdown简历](https://resume.mdnice.com/)：简洁且开源
- [木及简历](https://www.mujicv.com/)：功能丰富，模板众多，年 VIP 不过两顿食堂午餐的价钱。
  [只用 Markdown 就写出好看的简历，在线简历应用闪亮登场！](https://mdnice.com/writing/2783144790f94c429f90379e7adf78d7#writing-title)

**4. 写博客**

- [hexo](https://hexo.io/zh-cn/)：Hexo 是一个快速、简洁且高效的博客框架
- [如何复现本博客？ | Recogeta's Blog](https://r3c0ger.github.io/2024/12/reproduce-hexo-blog/)：我本人的博客文章，记录了我的建站流程

## 插件

- [VLOOK™ - Markdown 编辑器 Typora 的主题包和增强插件](https://madmaxchow.github.io/VLOOK/index.html)
- [obgnail/typora_plugin: Typora plugin. Feature enhancement tool | Typora 插件，功能增强工具](https://github.com/obgnail/typora_plugin)
  [通过注入 js 代码，为 Typora 额外增加 4 个功能](https://www.appinn.com/typora-4-plugin/)
  这个是我一直在用的插件，功能太强大了。

---

## 本系列文章目录

<!-- 知乎 -->
[Typora 有点儿深度使用的学习索引 - 知乎](https://zhuanlan.zhihu.com/p/596847931)

<!-- github -->
[Typora 有点儿深度使用的学习索引 - 前言、索引与目录 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-0/)

### 样式篇

<!-- 知乎 -->
[Typora 学习索引 - 样式篇 - 知乎](https://zhuanlan.zhihu.com/p/642431857)

<!-- github -->
[Typora 学习索引 - 样式篇 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-1/)

### 快捷键和图片篇

<!-- 知乎 -->
[Typora 学习索引 - 快捷键和图片篇 - 知乎](https://zhuanlan.zhihu.com/p/642434340)

<!-- github -->
[Typora 学习索引 - 快捷键和图片篇 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-2/)

### 公式篇

<!-- 知乎 -->
[Typora 学习索引 - 公式篇 - 知乎](https://zhuanlan.zhihu.com/p/642706422)

<!-- github -->
[Typora 学习索引 - 公式篇 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-3/)

### HTML 篇

<!-- 知乎 -->
[Typora 学习索引 - HTML 篇 - 知乎](https://zhuanlan.zhihu.com/p/642771075)

<!-- github -->
[Typora 学习索引 - HTML 篇 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-4/)

### 杂项

<!-- 知乎 -->
[Typora 学习索引 - 杂项 - 知乎](https://zhuanlan.zhihu.com/p/643130383)

<!-- github -->
[Typora 学习索引 - 杂项 | Recogeta's Blog](https://r3c0ger.github.io/2025/01/typora-tricks-5/)

## 后记

本来我想将我的这篇文章写得更全面、更有深度，不过我个人也就只有“三分钟热度”，不到真正用上的场合就没有这个耐心去学下去。不过实际上我也永远不可能写全面，如果我要在这篇文章中追求 All-in-one，那就走上歧路了。且不说我回头看过来，这篇文章粗糙不堪（标题都很别扭啊），如果真要写得长篇大论，那以后肯定要改吐了；如果再要填充什么进去的话，以这篇文章的组织结构，恐怕就快要噎死了吧。

这篇文章有很多模糊不清的地方，也可能有诸多疏漏和错误，恳请大家多多指教！

## 彩蛋

![苗爷](img/103270896.jpg)

- 彩蛋图片：
  - 作者：かわやばぐ (user-id: 35279138)
  - 来源：pixiv ID: 103270896
- 封面是搞成一团浆糊的 Typora 界面，源文件在 Github 上：[typora-tricks/cover/cover.md at main · R3c0ger/typora-tricks](https://github.com/R3c0ger/typora-tricks/blob/main/cover/cover.md)
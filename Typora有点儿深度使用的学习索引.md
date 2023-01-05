---
typora-root-url: /assets/
---
# Typora有点儿深度使用的学习索引

[TOC]

## 前言

> 因为Markdown这个语言很尴尬，再往上一点，哎，$\LaTeX$，可能有点实力，还能操作一下；再往下，Microsoft Office *Word*，人家就纯属所见即所得的，自己也知道自己格式需要调整。但Markdown？上不去又下不来。它觉得Word不配和自己放一块，但是呢，它想上去，它又上不去，想操作又操作不起来，卡在这儿了，掉下去了又不值得。 

以上一段文字纯属扯淡。事实上现在这三个玩意我都在用，我手上都有这三个家伙对应的（东拼西凑的）模板，唯一要考虑的就是针对不同的需求去挑选合适的工具罢了。你要问我这三个用哪个比较好？我的评价是：益研顶针，鉴定为有益于你的科研就行，反正我也说不出什么干货了，知乎上这种“跨作品比战力”的问题也是一抓一大把。

目前我撰写各类文档最大的困难，不是工具不好用，而是根本不会用。回过头来看我十几年玩电脑的历史，我尴尬地发现自己其实啥都不会。Word么，知道一些操作，但是除了高中学过一点（已经忘了）之外我还是啥都不会；$\LaTeX$么，我只能说我连入门都不算。上不去下不来的其实是我（笑），于是暂时还是好好用一阵子md吧，毕竟优点还蛮多的，最主要的是学习成本可能是最小的。

以下很多内容其实只服务于我的强迫症，虽然我也没去医院看过这到底是不是强迫症，所以“强迫症”这三个字我也没写进标题里。为什么我要在开头提到“上不去又下不来”呢？就是因为我想满足我的强迫症，但Markdown本来又不是为了干这种破事的，本来简简单单写个文档就行了的，但是我又非要想用简单的语言来搞复杂的事情，让Markdown满足我那“上得去又下得来”的hentai想法，于是我就会百度到很多有点儿深度的用法（很遗憾我现在还在用百度来搜索捏）。这些用法或技巧或曰“奇技淫巧”将会被记录于此，分享给大家。

为什么题目是“索引”呢？是因为我这里很多的用法很肤浅（因为没学过），而且文章干货都是从网上搜索而来的，所以这篇文章里更多的还是罗列一些超链接，将一些有用的文章和实用的网站分享出来，所以只能算是个索引。

我所使用的编辑器是Typora，版本为1.0.4，操作系统为win10。

源文件已上传至Github：https://github.com/R3c0ger/A-learning-index-of-Typora-with-a-little-bit-using-depth

## Markdown相关网站

### 学习网站

#### Markdown语法介绍

[Markdown 入门教程](https://www.imooc.com/wiki/markdownlesson)

[markdown语法大全](https://www.cnblogs.com/miki-peng/p/12502985.html)：这篇文章不仅很全，而且记录了很多很多颜色和Emoji。

[MarkDown高阶语法手册](https://mp.weixin.qq.com/s/L9WI8zMlPWdqUsyh36vUhA)

[Typora 完全使用详解](https://sspai.com/post/54912/)

#### Typora支持MathJax公式书写

[MarkDown公式指导手册](https://www.jianshu.com/p/53cc67f6c832)

[MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference/15077#15077)

[Typora中一些常用的latex公式](https://www.jianshu.com/p/8fed0e1a9692)

[【Typora】超全数学公式全集（没错，你想要的就在这里）](https://zhuanlan.zhihu.com/p/165342174)

[在MathJax中显示长除法符号的方法)\~\~\~\~\~\~](https://qa.1r1g.com/sf/ask/1600744981/)

[TeX 的宏 \ 第一集](http://garfileo.is-programmer.com/2010/5/21/macro-of-tex.18296.html)

[TeX 宏编程技巧之定界的宏参数](https://zhuanlan.zhihu.com/p/484092340)

#### Typora同样支持Mermaid

[About Mermaid](https://mermaid.js.org/intro/)：Mermaid官网，可以直接开始学习。

[一款优雅的流程图利器-Mermaid 使用指南](https://blog.csdn.net/qq_42818403/article/details/122599306)：这个么，好像类似于官网的翻译。

#### 有关Typora的样式修改

[Typora任意更改样式](https://blog.csdn.net/weixin_45817496/article/details/115867361)

[自定义Typora的样式(更新1 2021-7-14)](https://wap.sciencenet.cn/home.php?mod=space&uid=1213210&do=blog&id=1295427)

[Typora 伪装 LaTeX 中文样式主题](https://github.com/Keldos-Li/typora-latex-theme)

#### 其他杂项

[Typora快捷键汇总](https://zhuanlan.zhihu.com/p/592538886)

[Typora快捷键设置](http://events.jianshu.io/p/4d8f04352dc8)

[typora图片自动左（右）对齐](https://www.cnblogs.com/charlotteForever/p/15823838.html)

[markdown中对齐方式怎样设定？比如怎样将文字右对齐？](https://www.zhihu.com/question/21160553)

[Typora自动编号功能——最强版](https://blog.csdn.net/qq_33159059/article/details/87910522)

### 工具网站

[Mermaid~v9.3.0~ Live Editor](https://mermaid.live/edit#pako:eNptkLFugzAQhl_FubUGGQwBe0hVqUNTqVO3isWCIyCBnTq2Wop49xpot3g6-b7v193NUJsGQcINPz3qGp97dbFqrDQJ72noa4xOp4dX02lJXnAYDFlrSjrzRZRFMhn_eBfesVrpFSEdKktG_EPXXhTQaHNCcL_blJw3Y6ODdriPn0mLOJCLReUOQGFEO6q-CVvMq1CB63DECmQoG2yVH1wFlV4Cqrwz75OuQTrrkYK_Nsr9Lw2yVcMt_GLTO2Pf9stsB6JwVRrkDN8gMxHnQpSZKBgTaVHwjMIEMhGxyIoyK_jxyDlnrFwo_BgTYpM4LQRLRCqynJVlzviW97E110GWX5I8d18)：在线编辑各种Mermaid图，好像还是得自己手动敲代码......

[Create LaTeX tables online – TablesGenerator.com](https://www.tablesgenerator.com/)：画表格的；

[Convert Excel to LaTeX Table](https://tableconvert.com/excel-to-latex)：把Excel转为$\LaTeX$表格的。

[quiver: a modern commutative diagram editor](https://q.uiver.app/)：画交换图的，Typora里面好像还不能画曲线什么的......

[在线LaTeX公式编辑器-编辑器](https://www.latexlive.com/##)

## 样式

我现在使用的是[Typora 伪装 LaTeX 中文样式主题](https://github.com/Keldos-Li/typora-latex-theme#typora-%E4%BC%AA%E8%A3%85-latex-%E4%B8%AD%E6%96%87%E6%A0%B7%E5%BC%8F%E4%B8%BB%E9%A2%98)的自己魔改的样式，这个样式目前小问题有点多，但是不耽误使用，而且还是很好看的，反正我已经star了。

接下来我要说的就是我的一些魔改的地方。这些魔改是在[个性化设置](https://github.com/Keldos-Li/typora-latex-theme/wiki/%E4%B8%AA%E6%80%A7%E5%8C%96%E8%AE%BE%E7%BD%AE)之外我自己摸索的。我妹学过css啥的，下面要么是抄的，要么是<kbd>shift</kbd>+<kbd>F12</kbd>找出来的。

### 列表

```css
#write.first-line-indent li {
  margin-left: 0em;
}
```

上面这个代码控制的（好像）是列表的缩进距离，我对这个主题的列表缩进距离不太满意，就加了这么一段。未添加这一段之前是这样的：（后续的样式我也改了一点，但是不影响这段代码的效果）

![2.1.0_1](/2.1.0_1.png)

添加了这一段之后：

![2.1.0_2](/2.1.0_2.png)

### 下划线

默认的下划线样式就好像一条舔狗，死死地咬着文本不放，所以我给改了。我偶然发现这么一篇文章：[自定义Typora的样式](https://wap.sciencenet.cn/home.php?mod=space&uid=1213210&do=blog&id=1295427)（这篇文章中还有其他有用的内容），照着里面的代码调了一下，修改下划线的代码在下面，效果在上面的图片里。

```css
u {/*处理下划线显示，对应快捷键Ctrl+U*/
  text-decoration: none;
  border-width: 0 0 1.5px 0; /*下划线线条粗细*/
  border-color: rgb(0, 0, 0);
  border-style: solid;
  padding: 0 0 0px 0; /*下划线与文字距离*/
}  
```

<u>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</u>

![2.2.0_1](2.2.0_1.png)

上图为`padding`那一行第三个数据调为0px和1px的区别，文字是对齐的。下划线的粗细设成1.5px是很对我的口味的。

有点铸币的是，我在写这一部分的时候，突然发现在Typora里超链接的下划线还是老样子，然后我又不会改......虽然我设置的是输出的PDF中显示链接的蓝色但不显示下划线，但我还是很不爽......

```css
@media print {
  #write a {
    /*color: inherit !important;*/
    text-decoration: none;
  } 
}/*PDF中超链接这块的代码，看不懂，不会用（）*/
```

## 快捷键

这里给出我常用的快捷键设置，打开“偏好设置”$\rightarrow$“通用”$\rightarrow$“高级设置”$\rightarrow$“打开高级设置”$\rightarrow$“conf.user.json”，找到`"keyBinding": `那一片儿，将如下代码复制进去即可：

```json
  "keyBinding": {
    // for example: 
    // "Always on Top": "Ctrl+Shift+P"
    // All other options are the menu items 'text label' displayed from each typora menu
    "代码块": "Ctrl+Shift+W",
    "公式块": "Ctrl+Shift+E",
    "插入本地图片…": "Ctrl+R",
    "代码": "Ctrl+Shift+T",
    "PDF": "Ctrl+Shift+F",
    "搜索": "Ctrl+Shift+5",
    "内容目录": "Ctrl+Shift+A",
    "选择段落或块": "Ctrl+Shift+D",
    "删除当前词": "Ctrl+D",
    "删除块": "Ctrl+Alt+D",
    "高亮": "F2",
    "源代码模式": "F12",
    "上标": "Ctrl+Shift+6",
    "下标": "Ctrl+Shift+7"
  },
```

前面的中文就是工具栏里的选项，后面的就是快捷键，注意按键的首字母大写，符号都是英文符号，最后一行不要加逗号（这句跟废话一样）。

ps. 2023-1-4：我<kbd>插入本地图片…</kbd>的快捷键咋用不了了？我明明设置好了的啊？2023-1-5更新：从<kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>R</kbd>改成了<kbd>Ctrl</kbd>+<kbd>R</kbd>，便可正常运行了，莫名其妙

## 图片

### 添加图片

（1）在偏好设置中我一般这么整：

![pic1](/pic1.png)

（2）YAML front matters 也能方便我们将图片放在md文件所在的同一文件夹下，这样我们添加图片的时候，直接写相对路径即可。

```markdown
---
typora-root-url:/assets/
---
![pic1](/pic1.png)
```

但是铸币的事情又发生了，打开md文档时图片老是崩，只有打开文档后动一下`typora-root-url`才行。

以下是我试过的可行的`typora-root-url`，我不明白这是啥原理：

```yaml
typora-root-url:assets
typora-root-url:assets/
typora-root-url:/assets
typora-root-url:/assets/
typora-root-url: assets
typora-root-url: assets/
typora-root-url: /assets
typora-root-url: ./assets
typora-root-url: ./assets/
```

（水文章是吧）

### 图片位置

参见：[typora图片自动左（右）对齐](https://www.cnblogs.com/charlotteForever/p/15823838.html)、[markdown中对齐方式怎样设定？比如怎样将文字右对齐？](https://www.zhihu.com/question/21160553)

## 公式

### 底色、边框

$$
\bbox[yellow,5px,border:black]{e^x=\lim_{n\to\infty} \left( 1+\frac{x}{n} \right)^n \tag{*} }
$$

$$
\bbox[#2f3542, 0.5em, border:2px solid #f1f2f6]{
    \color{#f1f2f6}{e^x=\lim_{n\to\infty} \left( 1+\frac{x}{n} \right)^n}
}
$$

```latex
$$
\bbox[yellow,5px,border:black]{e^x=\lim_{n\to\infty} \left( 1+\frac{x}{n} \right)^n \tag{*} }
$$

$$
\bbox[#2f3542, 0.5em, border:2px solid #f1f2f6]{
    \color{#f1f2f6}{e^x=\lim_{n\to\infty} \left( 1+\frac{x}{n} \right)^n}
}
$$
```

无法显示边框（悲）

### 引用


$$
\textbf{一得阁拉米}\tag{m}
$$
$a+y^3 \stackrel{\eqref{m}\ref{m}} = x^2$	这样整不太行。

```latex
$$
\textbf{一得阁拉米}\tag{m}
$$
$a+y^3 \stackrel{\eqref{m}\ref{m}} = x^2$
```


$$
\textbf{一得阁拉米娜}\tag{f}\label{f}
$$
$a+y^3 \stackrel{\eqref{f}\ref{f}} = x^2$	这样整行。可以定义个新命令统合一下。

更新：其实不太行，重新打开一遍该md文件就会崩掉，只有删掉`\label{}`再添加回来、再动一下引用该公式的内容才行，心累。知乎上也根本用不了这个。

```latex
$$
\textbf{一得阁拉米娜}\tag{f}\label{f}
$$
$a+y^3 \stackrel{\eqref{f}\ref{f}} = x^2$
```

### 宏定义

$\def\ds{\displaystyle}
\def\BOX#1{\fbox{$\ds #1$}}
\def\pt#1{\phantom{#1}} $定义在左边，光标一放就显示了。

```latex
$\def\ds{\displaystyle}
\def\BOX#1{\fbox{$\ds #1$}}
\def\pt#1{\phantom{#1}}
$
```

$\ds\cases{\pt{欧内的手，}好汉！\\欧内的手，好汉！}$$\ds\frac{aaaaaaa}{bbbbbbbbbbb}$$\frac{aaaaaaaa}{bbbbbbbbb}$

```latex
$\ds\cases{\pt{欧内的手，}好汉！\\欧内的手，好汉！}$
$\ds\frac{aaaaaaa}{bbbbbbbbbbb}$
$\frac{aaaaaaaa}{bbbbbbbbb}$
```

参见[TeX 的宏 \ 第一集](http://garfileo.is-programmer.com/2010/5/21/macro-of-tex.18296.html)、[TeX 宏编程技巧之定界的宏参数](https://zhuanlan.zhihu.com/p/484092340)。

### 定义新命令

`\newcommand`也能用，那就很好玩了。

$
\newcommand{\def}[2]{\textbf{Def #1.#2}\quad}
\newcommand{\pro}[2]{\textbf{Property #1.#2}\;\;}
\newcommand{\thm}[2]{\textbf{Thm #1.#2}\quad}
\newcommand{\cor}[2]{\textbf{Cor #1.#2}\quad}
\newcommand{\pf}{\textbf{Proof}\quad}
\newcommand{\zb}{\quad\Box}
\newcommand{\exp}[2]{\textbf{Example #1.#2}\;\;}
\newcommand{\nb}{\textbf{NB}\quad}
\newcommand{\rmk}{\textbf{Remark}\quad}
\newcommand{\ps}{\textbf{p.s.}\quad}
\newcommand{\eg}{\textbf{e.g.}\quad}
\newcommand{\ord}[2]{\textrm{ord}_{#1}(#2)}
\newcommand{\fr}[2]{\frac{#1}{#2}}
\newcommand{\bb}[1]{\mathbb{#1}}
\newcommand{\tt}[1]{\textbf{#1}}
\newcommand{\eq}{\equiv}
\newcommand{\en}[1]{\,#1}
\newcommand{\cd}{\,\cdots}
\newcommand{\Ra}{\,\Rightarrow\,}
\newcommand{\Lra}{\,\Leftrightarrow\,}
\newcommand{\ra}{\,\rightarrow\,}
\newcommand{\qone}{\mathbb{①}\,}
\newcommand{\qtwo}{\mathbb{②}\,}
\newcommand{\qthr}{\mathbb{③}\,}
\newcommand{\qfou}{\mathbb{④}\,}
\newcommand{\qfiv}{\mathbb{⑤}\,}
\newcommand{\qsix}{\mathbb{⑥}\,}
\newcommand{\qsev}{\mathbb{⑦}\,}
\newcommand{\bm}[1]{\rm{（#1）}\,}
\newcommand{\lra}{\,\leftrightarrow\,}
\newcommand{\ds}{\displaystyle}
\newcommand{\yw}{\because}
\newcommand{\sy}{\therefore}
\newcommand{\ol}[1]{\varphi (#1)}
\newcommand{\jkh}[1]{\!<\!#1\!>\,}
\newcommand{\ykh}[1]{(#1)}
$定义在左边，光标一放就显示了。

```latex
$
\newcommand{\def}[2]{\textbf{Def #1.#2}\quad}
\newcommand{\pro}[2]{\textbf{Property #1.#2}\;\;}
\newcommand{\thm}[2]{\textbf{Thm #1.#2}\quad}
\newcommand{\cor}[2]{\textbf{Cor #1.#2}\quad}
\newcommand{\pf}{\textbf{Proof}\quad}
\newcommand{\zb}{\quad\Box}
\newcommand{\exp}[2]{\textbf{Example #1.#2}\;\;}
\newcommand{\nb}{\textbf{NB}\quad}
\newcommand{\rmk}{\textbf{Remark}\quad}
\newcommand{\ps}{\textbf{p.s.}\quad}
\newcommand{\eg}{\textbf{e.g.}\quad}
\newcommand{\ord}[2]{\textrm{ord}_{#1}(#2)}
\newcommand{\fr}[2]{\frac{#1}{#2}}
\newcommand{\bb}[1]{\mathbb{#1}}
\newcommand{\tt}[1]{\textbf{#1}}
\newcommand{\eq}{\equiv}
\newcommand{\en}[1]{\,#1}
\newcommand{\cd}{\,\cdots}
\newcommand{\Ra}{\,\Rightarrow\,}
\newcommand{\Lra}{\,\Leftrightarrow\,}
\newcommand{\ra}{\,\rightarrow\,}
\newcommand{\qone}{\mathbb{①}\,}
\newcommand{\qtwo}{\mathbb{②}\,}
\newcommand{\qthr}{\mathbb{③}\,}
\newcommand{\qfou}{\mathbb{④}\,}
\newcommand{\qfiv}{\mathbb{⑤}\,}
\newcommand{\qsix}{\mathbb{⑥}\,}
\newcommand{\qsev}{\mathbb{⑦}\,}
\newcommand{\bm}[1]{\rm{（#1）}\,}
\newcommand{\lra}{\,\leftrightarrow\,}
\newcommand{\ds}{\displaystyle}
\newcommand{\yw}{\because}
\newcommand{\sy}{\therefore}
\newcommand{\ol}[1]{\varphi (#1)}
\newcommand{\jkh}[1]{\!<\!#1\!>\,}
\newcommand{\ykh}[1]{(#1)}
$
```

以上来自于我之前的数学笔记，搞得一团糟。

### 括号

$\set{\cfrac{asd}{asd}} \quad \{\cfrac{asd}{asd}\} \quad \left\{\cfrac{asd}{asd}\right\}$

```latex
$\set{\cfrac{asd}{asd}} \quad \{\cfrac{asd}{asd}\} \quad \left\{\cfrac{asd}{asd}\right\}$
```

### 盒子们

$$
\Box \BOX{sdadasd\frac{asd}{sad}} \bbox[yellow]{asdas} \fbox{adsw} \hbox{ when $x > 2$}
$$

```latex
$$
\Box \BOX{sdadasd\frac{asd}{sad}} \bbox[yellow]{asdas} \fbox{adsw} \hbox{ when $x > 2$}
$$
```

`\BOX{}`是前面定义过的。

### \require{}

$$
\require{cancel}
\begin{array}{rl}
    \verb|y+\cancel{x}| & y+\cancel{x} \\
    \verb|\cancel{y+x}| & \cancel{y+x} \\
    \verb|y+\bcancel{x}| & y+\bcancel{x} \\
    \verb|y+\xcancel{x}| & y+\xcancel{x} \\
    \verb|y+\cancelto{0}{x}| & y+\cancelto{0}{x} \\
    \verb+\frac{1\cancel9}{\cancel95} = \frac15+& \frac{1\cancel9}{\cancel95} = \frac15 \\
\end{array}
$$

```latex
\require{cancel}
\begin{array}{rl}
    \verb|y+\cancel{x}| & y+\cancel{x} \\
    \verb|\cancel{y+x}| & \cancel{y+x} \\
    \verb|y+\bcancel{x}| & y+\bcancel{x} \\
    \verb|y+\xcancel{x}| & y+\xcancel{x} \\
    \verb|y+\cancelto{0}{x}| & y+\cancelto{0}{x} \\
    \verb+\frac{1\cancel9}{\cancel95} = \frac15+& \frac{1\cancel9}{\cancel95} = \frac15 \\
\end{array}
```

$$
\require{enclose}
\enclose{box}{
    \begin{array}{c}
        f(\top),\, f^2(\top),\, f^3(\top) \,\cdots\, f^n(\top) \\
        f(\bot),\, f^2(\bot),\, f^3(\bot) \,\cdots\, f^n(\bot) \\
    \end{array}
}
$$

```latex
\require{enclose}
\enclose{box}{
    \begin{array}{c}
        f(\top),\, f^2(\top),\, f^3(\top) \,\cdots\, f^n(\top) \\
        f(\bot),\, f^2(\bot),\, f^3(\bot) \,\cdots\, f^n(\bot) \\
    \end{array}
}
```

$$
\require{enclose}
\begin{array}{rll}
    125 && \hbox{(Explanations)} \\[-3pt]
   4 \enclose{longdiv}{500}\kern-.2ex \\[-3pt]
      \underline{4\phantom{00}} && \hbox{($4 \times 1 = 4$)} \\[-3pt]
      10\phantom{0} && \hbox{($5 - 4 = 1$)} \\[-3pt]
      \underline{\phantom{0}8\phantom{0}} && \hbox{($4 \times 2 = 8$)} \\[-3pt]
      \pt{0} 20 && \hbox{($10 - 8 = 2$)} \\[-3pt]
      \underline{\phantom{0}20} && \hbox{($4 \times 5 = 20$)} \\[-3pt]
      \phantom{00}0
  \end{array}
$$

```latex
\require{enclose}
\begin{array}{rll}
    125 && \hbox{(Explanations)} \\[-3pt]
   4 \enclose{longdiv}{500}\kern-.2ex \\[-3pt]
      \underline{4\phantom{00}} && \hbox{($4 \times 1 = 4$)} \\[-3pt]
      10\phantom{0} && \hbox{($5 - 4 = 1$)} \\[-3pt]
      \underline{\phantom{0}8\phantom{0}} && \hbox{($4 \times 2 = 8$)} \\[-3pt]
      \pt{0} 20 && \hbox{($10 - 8 = 2$)} \\[-3pt]
      \underline{\phantom{0}20} && \hbox{($4 \times 5 = 20$)} \\[-3pt]
      \phantom{00}0
  \end{array}
```

$$
\require{AMScd}
\begin{CD}
    A @>a>> B \\
    @V b V V\# @VV c V \\
    C @>>d> D \\
\end{CD}
\quad
\begin{CD}
    A @>>> B @>very long label>> C \\
    @. @AAA @| \\
    D @= E @<<< F \\
\end{CD}
$$

```latex
\require{AMScd}
\begin{CD}
    A @>a>> B \\
    @V b V V\# @VV c V \\
    C @>>d> D \\
\end{CD}
\quad
\begin{CD}
    A @>>> B @>very long label>> C \\
    @. @AAA @| \\
    D @= E @<<< F \\
\end{CD}
```

$$
\require{AMDcd}
\begin{CD}
    \rm{RCOHR^{'}SO_3Na} @>{\large\text{Hydrolysis, $\Delta$, Dil.HCl}}>> \rm{(RCOR^{'})+NaCl+SO_2+ H_2O}
\end{CD}
$$

```latex
\require{AMDcd}
\begin{CD}
    \rm{RCOHR^{'}SO_3Na} @>{\large\text{Hydrolysis, $\Delta$, Dil.HCl}}>> \rm{(RCOR^{'})+NaCl+SO_2+ H_2O}
\end{CD}
```

以上来自于[MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference/15077#15077)、[在MathJax中显示长除法符号的方法)\~\~\~\~\~\~](https://qa.1r1g.com/sf/ask/1600744981/)。只能说，MathJax is *not* LaTeX，这效果一言难尽（知乎效果反而比Typora好......）。

## HTML

如何实现像$\LaTeX$里面的`\newpage`那样手动断页呢？

<div class="cover" style="page-break-after:always;">

```html
<div class="cover" style="page-break-after:always;">
```

上面这一行就可以搞定了。

居中：`<center>标题</center>`

左对齐（可以在Typora设置首行缩进时使用）：`<div style="text-align: left"> 敬礼！ </div>`

右对齐：`<div style="text-align: right"> 2023年1月5日 </div>`

## 杂项

装作首行缩进的字符：
　　就在这一行的最前面捏

-----

恳请大家多多指教！

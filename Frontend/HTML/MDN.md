# MDN

- [MDN](#mdn)
  - [介绍](#%e4%bb%8b%e7%bb%8d)
  - [目录](#%e7%9b%ae%e5%bd%95)
  - [知识点汇总](#%e7%9f%a5%e8%af%86%e7%82%b9%e6%b1%87%e6%80%bb)
    - [HTML 介绍](#html-%e4%bb%8b%e7%bb%8d)
      - [HTML 入门](#html-%e5%85%a5%e9%97%a8)
        - [剖析一个 HTML 元素](#%e5%89%96%e6%9e%90%e4%b8%80%e4%b8%aa-html-%e5%85%83%e7%b4%a0)
        - [剖析 HTML 文档](#%e5%89%96%e6%9e%90-html-%e6%96%87%e6%a1%a3)
        - [实体引用： 在 HTML 中包含特殊字符](#%e5%ae%9e%e4%bd%93%e5%bc%95%e7%94%a8-%e5%9c%a8-html-%e4%b8%ad%e5%8c%85%e5%90%ab%e7%89%b9%e6%ae%8a%e5%ad%97%e7%ac%a6)
        - [HTML 注释](#html-%e6%b3%a8%e9%87%8a)
      - [`<head>`标签里有什么?](#head%e6%a0%87%e7%ad%be%e9%87%8c%e6%9c%89%e4%bb%80%e4%b9%88)
        - [元素`<title>`](#%e5%85%83%e7%b4%a0title)
        - [元数据：`<meta>`元素](#%e5%85%83%e6%95%b0%e6%8d%aemeta%e5%85%83%e7%b4%a0)
        - [在你的站点增加自定义图标](#%e5%9c%a8%e4%bd%a0%e7%9a%84%e7%ab%99%e7%82%b9%e5%a2%9e%e5%8a%a0%e8%87%aa%e5%ae%9a%e4%b9%89%e5%9b%be%e6%a0%87)
        - [在 HTML 中应用 CSS 和 JavaScript](#%e5%9c%a8-html-%e4%b8%ad%e5%ba%94%e7%94%a8-css-%e5%92%8c-javascript)
        - [为文档设定主语言](#%e4%b8%ba%e6%96%87%e6%a1%a3%e8%ae%be%e5%ae%9a%e4%b8%bb%e8%af%ad%e8%a8%80)
      - [HTML 文字基础](#html-%e6%96%87%e5%ad%97%e5%9f%ba%e7%a1%80)
        - [基础: 标题和段落](#%e5%9f%ba%e7%a1%80-%e6%a0%87%e9%a2%98%e5%92%8c%e6%ae%b5%e8%90%bd)
        - [列表 Lists](#%e5%88%97%e8%a1%a8-lists)
        - [重点强调](#%e9%87%8d%e7%82%b9%e5%bc%ba%e8%b0%83)
      - [建立超链接](#%e5%bb%ba%e7%ab%8b%e8%b6%85%e9%93%be%e6%8e%a5)
        - [链接的解析](#%e9%93%be%e6%8e%a5%e7%9a%84%e8%a7%a3%e6%9e%90)
        - [统一资源定位符(URL)与路径(path)快速入门](#%e7%bb%9f%e4%b8%80%e8%b5%84%e6%ba%90%e5%ae%9a%e4%bd%8d%e7%ac%a6url%e4%b8%8e%e8%b7%af%e5%be%84path%e5%bf%ab%e9%80%9f%e5%85%a5%e9%97%a8)
        - [电子邮件链接](#%e7%94%b5%e5%ad%90%e9%82%ae%e4%bb%b6%e9%93%be%e6%8e%a5)
      - [高级文字格式](#%e9%ab%98%e7%ba%a7%e6%96%87%e5%ad%97%e6%a0%bc%e5%bc%8f)
        - [描述列表](#%e6%8f%8f%e8%bf%b0%e5%88%97%e8%a1%a8)
        - [引用](#%e5%bc%95%e7%94%a8)
        - [缩略语](#%e7%bc%a9%e7%95%a5%e8%af%ad)
        - [标记联系方式](#%e6%a0%87%e8%ae%b0%e8%81%94%e7%b3%bb%e6%96%b9%e5%bc%8f)
        - [上标和下标](#%e4%b8%8a%e6%a0%87%e5%92%8c%e4%b8%8b%e6%a0%87)
        - [展示计算机代码](#%e5%b1%95%e7%a4%ba%e8%ae%a1%e7%ae%97%e6%9c%ba%e4%bb%a3%e7%a0%81)
        - [标记时间和日期](#%e6%a0%87%e8%ae%b0%e6%97%b6%e9%97%b4%e5%92%8c%e6%97%a5%e6%9c%9f)
      - [文档与网站架构](#%e6%96%87%e6%a1%a3%e4%b8%8e%e7%bd%91%e7%ab%99%e6%9e%b6%e6%9e%84)
          - [文档的基本组成部分](#%e6%96%87%e6%a1%a3%e7%9a%84%e5%9f%ba%e6%9c%ac%e7%bb%84%e6%88%90%e9%83%a8%e5%88%86)
        - [用于构建内容的 HTML](#%e7%94%a8%e4%ba%8e%e6%9e%84%e5%bb%ba%e5%86%85%e5%ae%b9%e7%9a%84-html)
        - [HTML 布局元素细节](#html-%e5%b8%83%e5%b1%80%e5%85%83%e7%b4%a0%e7%bb%86%e8%8a%82)
      - [HTML 除错](#html-%e9%99%a4%e9%94%99)
        - [HTML 和调试](#html-%e5%92%8c%e8%b0%83%e8%af%95)
    - [多媒体与嵌入](#%e5%a4%9a%e5%aa%92%e4%bd%93%e4%b8%8e%e5%b5%8c%e5%85%a5)
      - [HTMl 中的图片](#html-%e4%b8%ad%e7%9a%84%e5%9b%be%e7%89%87)
        - [通过为图片搭配说明文字的方式来解说图片](#%e9%80%9a%e8%bf%87%e4%b8%ba%e5%9b%be%e7%89%87%e6%90%ad%e9%85%8d%e8%af%b4%e6%98%8e%e6%96%87%e5%ad%97%e7%9a%84%e6%96%b9%e5%bc%8f%e6%9d%a5%e8%a7%a3%e8%af%b4%e5%9b%be%e7%89%87)
        - [CSS 背景图片](#css-%e8%83%8c%e6%99%af%e5%9b%be%e7%89%87)
      - [视频和音频内容](#%e8%a7%86%e9%a2%91%e5%92%8c%e9%9f%b3%e9%a2%91%e5%86%85%e5%ae%b9)
        - [web 中的音频和视频](#web-%e4%b8%ad%e7%9a%84%e9%9f%b3%e9%a2%91%e5%92%8c%e8%a7%86%e9%a2%91)
        - [显示音轨文本](#%e6%98%be%e7%a4%ba%e9%9f%b3%e8%bd%a8%e6%96%87%e6%9c%ac)
      - [从对象到 iframe —— 其他嵌入技术](#%e4%bb%8e%e5%af%b9%e8%b1%a1%e5%88%b0-iframe--%e5%85%b6%e4%bb%96%e5%b5%8c%e5%85%a5%e6%8a%80%e6%9c%af)
        - [`<embed>`和`<object>`元素](#embed%e5%92%8cobject%e5%85%83%e7%b4%a0)
      - [为 Web 新增矢量图](#%e4%b8%ba-web-%e6%96%b0%e5%a2%9e%e7%9f%a2%e9%87%8f%e5%9b%be)
        - [SVG 是什么？](#svg-%e6%98%af%e4%bb%80%e4%b9%88)
        - [将 SVG 添加到页面](#%e5%b0%86-svg-%e6%b7%bb%e5%8a%a0%e5%88%b0%e9%a1%b5%e9%9d%a2)
      - [自适应图片](#%e8%87%aa%e9%80%82%e5%ba%94%e5%9b%be%e7%89%87)
        - [怎样创建自适应的图片?](#%e6%80%8e%e6%a0%b7%e5%88%9b%e5%bb%ba%e8%87%aa%e9%80%82%e5%ba%94%e7%9a%84%e5%9b%be%e7%89%87)
    - [HTML 表格](#html-%e8%a1%a8%e6%a0%bc)
      - [HTML 表格基础](#html-%e8%a1%a8%e6%a0%bc%e5%9f%ba%e7%a1%80)
        - [使用 <th> 元素添加标题](#%e4%bd%bf%e7%94%a8-th-%e5%85%83%e7%b4%a0%e6%b7%bb%e5%8a%a0%e6%a0%87%e9%a2%98)
        - [允许单元格跨越多行和列](#%e5%85%81%e8%ae%b8%e5%8d%95%e5%85%83%e6%a0%bc%e8%b7%a8%e8%b6%8a%e5%a4%9a%e8%a1%8c%e5%92%8c%e5%88%97)
        - [为表格中的列提供共同的样式](#%e4%b8%ba%e8%a1%a8%e6%a0%bc%e4%b8%ad%e7%9a%84%e5%88%97%e6%8f%90%e4%be%9b%e5%85%b1%e5%90%8c%e7%9a%84%e6%a0%b7%e5%bc%8f)
      - [HTML 高级表格特性和可访问性](#html-%e9%ab%98%e7%ba%a7%e8%a1%a8%e6%a0%bc%e7%89%b9%e6%80%a7%e5%92%8c%e5%8f%af%e8%ae%bf%e9%97%ae%e6%80%a7)
        - [使用 `<caption>` 为你的表格增加一个标题](#%e4%bd%bf%e7%94%a8-caption-%e4%b8%ba%e4%bd%a0%e7%9a%84%e8%a1%a8%e6%a0%bc%e5%a2%9e%e5%8a%a0%e4%b8%80%e4%b8%aa%e6%a0%87%e9%a2%98)
        - [添加 `<thead>`, `<tfoot>`, 和 `<tbody>` 结构](#%e6%b7%bb%e5%8a%a0-thead-tfoot-%e5%92%8c-tbody-%e7%bb%93%e6%9e%84)
        - [嵌套表格](#%e5%b5%8c%e5%a5%97%e8%a1%a8%e6%a0%bc)
        - [对于视力受损的用户的表格](#%e5%af%b9%e4%ba%8e%e8%a7%86%e5%8a%9b%e5%8f%97%e6%8d%9f%e7%9a%84%e7%94%a8%e6%88%b7%e7%9a%84%e8%a1%a8%e6%a0%bc)
    - [HTML 表单](#html-%e8%a1%a8%e5%8d%95)
      - [如何构建 HTML 表单](#%e5%a6%82%e4%bd%95%e6%9e%84%e5%bb%ba-html-%e8%a1%a8%e5%8d%95)
        - [`<form>` 元素](#form-%e5%85%83%e7%b4%a0)
        - [`<fieldset>` 和 `<legend>` 元素](#fieldset-%e5%92%8c-legend-%e5%85%83%e7%b4%a0)
        - [`<label>`元素](#label%e5%85%83%e7%b4%a0)
      - [原生表单挂件](#%e5%8e%9f%e7%94%9f%e8%a1%a8%e5%8d%95%e6%8c%82%e4%bb%b6)
        - [通用属性](#%e9%80%9a%e7%94%a8%e5%b1%9e%e6%80%a7)
        - [文本输入框](#%e6%96%87%e6%9c%ac%e8%be%93%e5%85%a5%e6%a1%86)
        - [下拉内容](#%e4%b8%8b%e6%8b%89%e5%86%85%e5%ae%b9)
        - [可选中项](#%e5%8f%af%e9%80%89%e4%b8%ad%e9%a1%b9)
        - [按钮](#%e6%8c%89%e9%92%ae)
        - [高级表单部件](#%e9%ab%98%e7%ba%a7%e8%a1%a8%e5%8d%95%e9%83%a8%e4%bb%b6)
        - [其他小部件](#%e5%85%b6%e4%bb%96%e5%b0%8f%e9%83%a8%e4%bb%b6)
      - [发送表单数据](#%e5%8f%91%e9%80%81%e8%a1%a8%e5%8d%95%e6%95%b0%e6%8d%ae)
        - [数据都去哪儿了？](#%e6%95%b0%e6%8d%ae%e9%83%bd%e5%8e%bb%e5%93%aa%e5%84%bf%e4%ba%86)
        - [特殊案例:发送文件](#%e7%89%b9%e6%ae%8a%e6%a1%88%e4%be%8b%e5%8f%91%e9%80%81%e6%96%87%e4%bb%b6)
        - [常见的安全问题](#%e5%b8%b8%e8%a7%81%e7%9a%84%e5%ae%89%e5%85%a8%e9%97%ae%e9%a2%98)
      - [表单验证](#%e8%a1%a8%e5%8d%95%e9%aa%8c%e8%af%81)
        - [使用内置表单数据校验](#%e4%bd%bf%e7%94%a8%e5%86%85%e7%bd%ae%e8%a1%a8%e5%8d%95%e6%95%b0%e6%8d%ae%e6%a0%a1%e9%aa%8c)
      - [使用 JavaScript 校验表单](#%e4%bd%bf%e7%94%a8-javascript-%e6%a0%a1%e9%aa%8c%e8%a1%a8%e5%8d%95)
      - [如何构建自定义表单挂件](#%e5%a6%82%e4%bd%95%e6%9e%84%e5%bb%ba%e8%87%aa%e5%ae%9a%e4%b9%89%e8%a1%a8%e5%8d%95%e6%8c%82%e4%bb%b6)
      - [使用 JavaScript 发送表单](#%e4%bd%bf%e7%94%a8-javascript-%e5%8f%91%e9%80%81%e8%a1%a8%e5%8d%95)
        - [处理二进制数据](#%e5%a4%84%e7%90%86%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0%e6%8d%ae)
      - [过时浏览器的 HTML 表单](#%e8%bf%87%e6%97%b6%e6%b5%8f%e8%a7%88%e5%99%a8%e7%9a%84-html-%e8%a1%a8%e5%8d%95)
        - [功能检测和模拟(polyfills)](#%e5%8a%9f%e8%83%bd%e6%a3%80%e6%b5%8b%e5%92%8c%e6%a8%a1%e6%8b%9fpolyfills)
      - [样式化 HTML 表单](#%e6%a0%b7%e5%bc%8f%e5%8c%96-html-%e8%a1%a8%e5%8d%95)
        - [基本样式美化](#%e5%9f%ba%e6%9c%ac%e6%a0%b7%e5%bc%8f%e7%be%8e%e5%8c%96)
      - [表单样式兼容表格](#%e8%a1%a8%e5%8d%95%e6%a0%b7%e5%bc%8f%e5%85%bc%e5%ae%b9%e8%a1%a8%e6%a0%bc)

## 介绍

[MDN](https://developer.mozilla.org/zh-CN/docs/Learn/HTML) HTML 网站基础学习重点知识点总结

## 目录

## 知识点汇总

### HTML 介绍

#### HTML 入门

##### 剖析一个 HTML 元素

![标签元素](https://mdn.mozillademos.org/files/16475/element.png)  
这个元素的主要部分有：

1. 开始标签（Opening tag）：包含元素的名称（本例为 p），被左、右角括号所包围。表示元素从这里开始或者开始起作用 —— 在本例中即段落由此开始。
2. 结束标签（Closing tag）：与开始标签相似，只是其在元素名之前包含了一个斜杠。这表示着元素的结尾 —— 在本例中即段落在此结束。初学者常常会犯忘记包含结束标签的错误，这可能会产生一些奇怪的结果。
3. 内容（Content）：元素的内容，本例中就是所输入的文本本身。
4. 元素（Element）：开始标签、结束标签与内容相结合，便是一个完整的元素。

**块级元素和内联元素：**  
在 HTML 中有两种你需要知道的重要元素类别，块级元素和内联元素。

- 块级元素在页面中以块的形式展现 —— 相对于其前面的内容它会出现在新的一行，其后的内容也会被挤到下一行展现。块级元素通常用于展示页面上结构化的内容，例如段落、列表、导航菜单、页脚等等。一个以 block 形式展现的块级元素不会被嵌套进内联元素中，但可以嵌套在其它块级元素中。
- 内联元素通常出现在块级元素中并环绕文档内容的一小部分，而不是一整个段落或者一组内容。内联元素不会导致文本换行：它通常出现在一堆文字之间例如超链接元素`<a>`或者强调元素`<em>`和 `<strong>`。

**空元素：**  
不是所有元素都拥有开始标签，内容，结束标签。一些元素只有一个标签，通常用来在此元素所在位置插入/嵌入一些东西。例如：元素<img>是用来在元素<img>所在位置插入一张指定的图片。例子如下：

```html
<img
  src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"
/>
```

**属性：**  
元素也可以拥有属性，如下：

![带属性的标签元素](https://mdn.mozillademos.org/files/16476/attribute.png)

属性包含元素的额外信息，这些信息不会出现在实际的内容中。在上述例子中，这个 class 属性给元素赋了一个识别的名字（id），这个名字此后可以被用来识别此元素的样式信息和其他信息。
一个属性必须包含如下内容：

1. 一个空格，在属性和元素名称之间。(如果已经有一个或多个属性，就与前一个属性之间有一个空格。)
2. 属性名称，后面跟着一个等于号。
3. 一个属性值，由一对引号“ ”引起来。

##### 剖析 HTML 文档

学习了一些 HTML 元素的基础知识，这些元素单独一个是没有意义的。现在我们来学习这些特定元素是怎么被结合起来，从而形成一个完整的 HTML 页面的：

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>我的测试站点</title>
  </head>
  <body>
    <p>这是我的页面</p>
  </body>
</html>
```

分析如下：

1. `<!DOCTYPE html>`: 声明文档类型. 很久以前，早期的 HTML(大约 1991 年 2 月)，文档类型声明类似于链接，规定了 HTML 页面必须遵从的良好规则，能自动检测错误和其他有用的东西。使用如下：
   ```html
   <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
   ```
   然而现在没有人再这样写，需要包含这些东西才能正常工作已成为历史。你只需要知道`<!DOCTYPE html>`是最短的有效的文档声明。
2. `<html></html>`: `<html>`元素。这个元素包裹了整个完整的页面，是一个根元素。
3. `<head></head>`: `<head>`元素. 这个元素是一个容器，它包含了所有你想包含在 HTML 页面中但不想在 HTML 页面中显示的内容。这些内容包括你想在搜索结果中出现的关键字和页面描述，CSS 样式，字符集声明等等。以后的章节能学到更多关于`<head>`元素的内容。
4. `<meta charset="utf-8">`: 这个元素设置文档使用 utf-8 字符集编码，utf-8 字符集包含了人类大部分的文字。基本上他能识别你放上去的所有文本内容。毫无疑问要使用它，并且它能在以后避免很多其他问题。
5. `<title></title>`: 设置页面标题，出现在浏览器标签上，当你标记/收藏页面时它可用来描述页面。
6. `<body></body>`: `<body>`元素。 包含了你访问页面时所有显示在页面上的内容，文本，图片，音频，游戏等等。

**HTML 中的空白：**  
无论你用了多少空白(包括空白字符，包括换行), 当渲染这些代码的时候，HTML 解释器会将连续出现的空白字符减少为一个单独的空格符。那么为什么我们会使用那么多的空白呢? 答案就是为了可读性 —— 如果你的代码被很好地进行格式化，那么就很容易理解你的代码是怎么回事, 反之就只有聚做一团的混乱. 在我们的 HTML 代码中，我们让每一个嵌套的元素以两个空格缩进。 你使用什么风格来格式化你的代码取决于你 (比如所对于每层缩进使用多少个空格),但是你应该坚持使用某种风格。下面的两个代码片段是等价的：

```html
<p>狗 狗 很 呆 萌。</p>

<p>狗 狗 很 呆 萌。</p>
```

##### 实体引用： 在 HTML 中包含特殊字符

在 HTML 中，字符 <, >,",' 和 & 是特殊字符. 它们是 HTML 语法自身的一部分，如果需要表示我们必须使用字符引用—— 表示字符的特殊编码, 它们可以在那些情况下使用. 每个字符引用以符号&开始, 以分号(;)结束。

```html
<p>HTML 中用</p>
<p>来定义段落元素。</p>

<p>HTML 中用 &lt;p&gt; 来定义段落元素</p>
```

实时输出中，你会看到第一段是错误的，因为浏览器会认为第二个<p>是开始一个新的段落！ 第二段是正确的，因为我们用字符引用来代替了角括号（'<'和'>'符号）。

##### HTML 注释

如同大部分的编程语言一样，在 HTML 中有一种可用的机制来在代码中书写注释 —— 注释是被浏览器忽略的，而且是对用户不可见的，它们的目的是允许你描述你的代码是如何工作的和不同部分的代码做了什么等等。  
为了将一段 HTML 中的内容置为注释，你需要将其用特殊的记号<!--和-->包括起来， 比如：

```html
<p>我在注释外！</p>

<!-- <p>我在注释内！</p> -->
```

第一段出现在了实时输出中，但是第二段却没有。

#### `<head>`标签里有什么?

##### 元素`<title>`

用来给 html 文档添加一个标题。用来表示整个 HTML 文档标题的元数据（不是文档的内容）。

##### 元数据：`<meta>`元素

元数据就是描述数据的数据，而 HTML 有一个“官方的”方式来为一个文档添加元数据—— <meta> 元素。

**指定你的文档中字符的编码：**

```html
<meta charset="utf-8" />
```

**添加作者和描述：**

```html
<meta name="author" content="Chris Mills" />
<meta
  name="description"
  content="The MDN Learning Area aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications."
/>
```

指定包含关于页面内容的关键字的页面内容的描述是很有用的，因为它可能或让你的页面在搜索引擎的相关的搜索出现得更多

##### 在你的站点增加自定义图标

页面添加图标的方式有：

1. 将其保存在与网站的索引页面相同的目录中，以.ico 格式保存（大多数浏览器将支持更通用的格式，如.gif 或.png，但使用 ICO 格式将确保它能在如 Internet Explorer 6 一样久远的浏览器显示）
2. 将以下行添加到 HTML <head>中以引用它：
   ```html
   <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
   ```

##### 在 HTML 中应用 CSS 和 JavaScript

- `<link>` 元素经常位于文档的头部。这个 link 元素有 2 个属性，rel="stylesheet"表明这是文档的样式表，而 href 包含了样式表文件的路径：
  ```html
  <link rel="stylesheet" href="my-css-file.css" />
  ```
- `<script>` 部分没必要非要放在文档头部；实际上，把它放在文档的尾部（在 `</body>`标签之前）是一个更好的选择，这样可以确保在加载脚本之前浏览器已经解析了 HTML 内容（如果脚本加载某个不存在的元素，浏览器会报错）。

##### 为文档设定主语言

```html
<html lang="en-US"></html>
```

这在很多方面都很有用。如果你的 HTML 文档的语言设置好了，那么你的 HTML 文档就会被搜索引擎更有效地索引 (例如，允许它在特定于语言的结果中正确显示)，对于那些使用屏幕阅读器的视障人士也很有用(比如， 法语和英语中都有“six”这个单词，但是发音却完全不同)。

#### HTML 文字基础

##### 基础: 标题和段落

六个标题元素标签 —— `<h1>`、`<h2>`、`<h3>`、`<h4>`、`<h5>`、`<h6>`。每个元素代表文档中不同级别的内容; `<h1>` 表示主标题（the main heading），`<h2>` 表示二级子标题（subheadings），`<h3>` 表示三级子标题（sub-subheadings），等等。

**结构层次最佳实践：**

- 您应该最好只对每个页面使用一次`<h1>` — 这是顶级标题，所有其他标题位于层次结构中的下方。
- 请确保在层次结构中以正确的顺序使用标题。不要使用`<h3>`来表示副标题，后面跟`<h2>`来表示副副标题 - 这是没有意义的，会导致奇怪的结果。
- 在可用的六个标题级别中，您应该旨在每页使用不超过三个，除非您认为有必要使用更多。具有许多级别的文档（即，较深的标题层次结构）变得难以操作并且难以导航。在这种情况下，如果可能，建议将内容分散在多个页面上。

##### 列表 Lists

**无序 Unordered：**

```html
<ul>
  <li>豆浆</li>
  <li>油条</li>
  <li>豆汁</li>
  <li>焦圈</li>
</ul>
```

**有序 Ordered：**

```html
<ol>
  <li>沿着条路走到头</li>
  <li>右转</li>
  <li>直行穿过第一个十字路口</li>
  <li>在第三个十字路口处左转</li>
  <li>继续走 300 米，学校就在你的右手边</li>
</ol>
```

**嵌套列表 Nesting lists：**

```html
<ol>
  <li>
    先用蛋白一个、盐半茶匙及淀粉两大匙搅拌均匀，调成“腌料”，鸡胸肉切成约一厘米见方的碎丁并用“腌料”搅拌均匀，腌渍半小时。
  </li>
  <li>
    用酱油一大匙、淀粉水一大匙、糖半茶匙、盐四分之一茶匙、白醋一茶匙、蒜末半茶匙调拌均匀，调成“综合调味料”。
  </li>
  <li>
    鸡丁腌好以后，色拉油下锅烧热，先将鸡丁倒入锅内，用大火快炸半分钟，炸到变色之后，捞出来沥干油汁备用。
  </li>
  <li>
    在锅里留下约两大匙油，烧热后将切好的干辣椒下锅，用小火炒香后，再放入花椒粒和葱段一起爆香。随后鸡丁重新下锅，用大火快炒片刻后，再倒入“综合调味料”继续快炒。
    <ul>
      <li>
        如果你采用正宗川菜做法，最后只需加入花生米，炒拌几下就可以起锅了。
      </li>
      <li>如果你在北方，可加入黄瓜丁、胡萝卜丁和花生米，翻炒后起锅。</li>
    </ul>
  </li>
</ol>
```

##### 重点强调

**强调：**  
`<em>`（emphasis）元素来标记这样的情况。这样做既可以让文档读起来更有趣，也可以被屏幕阅读器识别出来，并以不同的语调发出。

**非常重要：**  
`<strong>` (strong importance) 元素来标记这样的请况。这样做既可以让文档更加地有用，也可以被屏幕阅读器识别出来，并以不同的语调发出。

**斜体字、粗体字、下划线...**  
HTML5 用新的语义规则重新定义了`<b>`,`<i>`和`<u>`,稍微有点混乱。
这里是最好的经验法则：使用`<b>`,`<i>`,`<u>` 来传达传统意义上的粗体，斜体或下划线是合适的，没有其他元素更适合这样用了。

- `<i>` 被用来传达传统上用斜体表达的意义：外国文字，分类名称，技术术语，一种思想……
- `<b>` 被用来传达传统上用粗体表达的意义：关键字，产品名称，引导句……
- `<u>` 被用来传达传统上用下划线表达的意义：专有名词，拼写错误……

#### 建立超链接

##### 链接的解析

通过将文本（或其他内容，见块级链接)转换为`<a>`元素内的链接来创建基本链接， 给它一个 href 属性（也称为目标），它将包含您希望链接指向的网址。

```html
<p>
  I'm creating a link to
  <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
</p>
```

**使用 title 属性添加支持信息：**  
当鼠标指针悬停在链接上时，title 将作为提示信息出现

**块级链接：**  
你可以将一些内容转换为链接，甚至是块级元素。例如你想要将一个图像转换为链接，你只需把图像元素放到`<a></a>`标签中间。

##### 统一资源定位符(URL)与路径(path)快速入门

统一资源定位符（英文：Uniform Resource Locator，简写：URL）是一个定义了在网络上的位置的一个文本字符串。例如 Mozilla 的英文主页定位在https://www.mozilla.org/en-US/.

**文档片段：**  
超链接除了可以链接到文档外，也可以链接到 HTML 文档的特定部分（被称为文档片段）。  
要做到这一点，你必须首先给要链接到的元素分配一个 id 属性。

```html
<h2 id="Mailing_address">Mailing address</h2>
```

然后链接到那个特定的 id，您可以在 URL 的结尾使用一个井号指向它，例如：

```html
<p>
  Want to write us a letter? Use our
  <a href="contacts.html#Mailing_address">mailing address</a>.
</p>
```

你甚至可以在同一份文档下，通过链接文档片段，来链接到同一份文档的另一部分：

```html
<p>
  The <a href="#Mailing_address">company mailing address</a> can be found at the
  bottom of this page.
</p>
```

**绝对 URL 和相对 URL：**

- 绝对 URL： 指向由其在 Web 上的绝对位置定义的位置，包括 protocol(协议) and domain name（域名）.。像下面的例子,如果 index.html 页面上传到 projects 这一个目录 。并且 projects 目录位于 web 服务站点的根目录, web 站点的域名为http://www.example.com, 那么这个页面就可以通过http://www.example.com/projects/index.html访问 ( 或者通过http://www.example.com/projects/来访问, 因为在没有指定特定的 URL 的情况下，大多数 web 服务会默认访问加载 index.html 这类页面)
  不管绝对 URL 在哪里使用，它总是指向确定的相同位置。
- 指向与您链接的文件相关的位置，更像我们在前面一节中所看到的位置。例如，如果我们想从示例文件链接http://www.example.com/projects/index.html转到相同目录下的一个PDF文件, URL 就是文件名 URL — 例如 project-brief.pdf —没有其他的信息要求. 如果 PDF 文件能够在 projects 的子目录 pdfs 中访问到, 相对路径就是 pdfs/project-brief.pdf (`对应的绝对URL就是http://www.example.com/projects/pdfs/project-brief.pdf.`)

**尽可能使用相对链接：**

- 首先，检查代码要容易得多——相对 URL 通常比绝对 URL 短得多，这使得阅读代码更容易。
- 其次，在可能的情况下使用相对 URL 更有效。当使用绝对 URL 时，浏览器首先通过 DNS（见万维网是如何工作的）查找服务器的真实位置，然后再转到该服务器并查找所请求的文件。另一方面，相对 URL，浏览器只在同一服务器上查找被请求的文件。因此，如果你使用绝对 URL 而不是相对 URL，你就会不断地让你的浏览器做额外的工作，这意味着它的效率会降低。

**在下载链接时使用 download 属性：**  
当您链接到要下载的资源而不是在浏览器中打开时，您可以使用 download 属性来提供一个默认的保存文件名（译注：此属性仅适用于同源 URL）

```html
<a
  href="https://download.mozilla.org/?product=firefox-latest-ssl&os=win64&lang=en-US"
  download="firefox-latest-64bit-installer.exe"
>
  Download Latest Firefox for Windows (64-bit) (English, US)
</a>
```

##### 电子邮件链接

其最基本和最常用的使用形式为一个 mailto:link （链接）

```html
<a href="mailto:nowhere@mozilla.org">Send email to nowhere</a>
```

其中最常用的是主题(subject)、抄送(cc)和主体(body) (这不是一个真正的头字段，但允许您为新邮件指定一个短内容消息)。

```html
<a
  href="mailto:nowhere@mozilla.org?cc=name2@rapidtables.com&bcc=name3@rapidtables.com&subject=The%20subject%20of%20the%20email&body=The%20body%20of%20the%20email"
>
  Send mail with cc, bcc, subject and body
</a>
```

#### 高级文字格式

##### 描述列表

描述列表使用与其他列表类型不同的闭合标签— `<dl>`; 此外，每一项都用 `<dt>` (description term) 元素闭合。每个描述都用 `<dd>` (description description) 元素闭合。让我们来完成下面的标记例子：

```html
<dl>
  <dt>内心独白</dt>
  <dd>
    戏剧中，某个角色对自己的内心活动或感受进行念白表演，这些台词只面向观众，而其他角色不会听到。
  </dd>
  <dt>语言独白</dt>
  <dd>
    戏剧中，某个角色把自己的想法直接进行念白表演，观众和其他角色都可以听到。
  </dd>
  <dt>旁白</dt>
  <dd>
    戏剧中，为渲染幽默或戏剧性效果而进行的场景之外的补充注释念白，只面向观众，内容一般都是角色的感受、想法、以及一些背景信息等。
  </dd>
</dl>
```

一个术语 `<dt>` 可以同时有多个描述 `<dd>`

##### 引用

**块引用：**  
如果一个块级内容（一个段落、多个段落、一个列表等）从其他地方被引用，你应该把它用`<blockquote>`元素包裹起来表示，并且在 cite 属性里用 URL 来指向引用的资源。

```html
<blockquote
  cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote"
>
  <p>
    The <strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (or
    <em>HTML Block Quotation Element</em>) indicates that the enclosed text is
    an extended quotation.
  </p>
</blockquote>
```

浏览器在渲染块引用时默认会增加缩进，作为引用的一个指示符;

**行内引用：**
行内元素用同样的方式工作，使用<q>元素。例如，下面的标记包含了从 MDN<q>页面的引用

```html
<p>
  The quote element — <code>&lt;q&gt;</code> — is
  <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q"
    >intended for short quotations that don't require paragraph breaks.</q
  >
</p>
```

浏览器默认将其作为普通文本放入引号内表示引用。

**引文：**  
cite 属性内容不会被浏览器显示、屏幕阅读器阅读，需使用 JavaScript 或 CSS，浏览器才会显示 cite 的内容。如果你想要确保引用的来源在页面上是可显示的，更好的方法使用`<cite>`。引文默认的字体样式为斜体。

##### 缩略语

另一个你在 web 上看到的相当常见的元素是<abbr>——它常被用来包裹一个缩略语或缩写，并且提供缩写的解释（包含在 title 属性中）

```html
<p>
  我们使用
  <abbr title="超文本标记语言（Hypertext Markup Language）">HTML</abbr>
  来组织网页文档。
</p>

<p>
  第 33 届 <abbr title="夏季奥林匹克运动会">奥运会</abbr> 将于 2024 年 8
  月在法国巴黎举行。
</p>
```

##### 标记联系方式

HTML 有个用于标记联系方式的元素——`<address>`。它仅仅包含你的联系方式，例如：

```html
<address>
  <p>Chris Mills, Manchester, The Grim North, UK</p>
</address>
```

`<address>`元素是为了标记编写 HTML 文档的人的联系方式，而不是任何其他的内容。

##### 上标和下标

当你使用日期、化学方程式、和数学方程式时会偶尔使用上标和下标。 `<sup>`和`<sub>`元素可以解决这样的问题。

```html
<p>
  咖啡因的化学方程式是 C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>。
</p>
<p>如果 x<sup>2</sup> 的值为 9，那么 x 的值必为 3 或 -3。</p>
```

##### 展示计算机代码

有大量的 HTML 元素可以来标记计算机代码：

- `<code>`: 用于标记计算机通用代码。
- `<pre>`: 用于保留空白字符（通常用于代码块）——如果您在文本中使用缩进或多余的空白，浏览器将忽略它，您将不会在呈现的页面上看到它。但是，如果您将文本包含在`<pre></pre>`标签中，那么空白将会以与你在文本编辑器中看到的相同的方式渲染出来。
- `<var>`: 用于标记具体变量名。
- `<kbd>`: 用于标记输入电脑的键盘（或其他类型）输入。
- `<samp>`: 用于标记计算机程序的输出。

##### 标记时间和日期

HTML 还支持将时间和日期标记为可供机器识别的格式的 `<time>` 元素。例如：

```html
<time datetime="2016-01-20">2016年1月20日</time>
```

有许多种书写日期的格式，这些不同的格式不容易被电脑识别，元素允许你附上清晰的、可被机器识别的 时间/日期来实现这种需求。

#### 文档与网站架构

###### 文档的基本组成部分

- 页眉：通常横跨于整个页面顶部有一个大标题 和/或 一个标志。 这是网站的主要一般信息，通常存在于所有网页。
- 导航栏：指向网站各个主要区段的超链接。通常用菜单按钮、链接或标签页表示。类似于标题栏，导航栏通常应在所有网页之间保持一致，否则会让用户感到疑惑，甚至无所适从。许多 web 设计人员认为导航栏是标题栏的一部分，而不是独立的组件，但这并非绝对；还有人认为，两者独立可以提供更好的 无障碍访问特性，因为屏幕阅读器可以更清晰地分辨二者。
- 主内容：中心的大部分区域是当前网页大多数的独有内容，例如视频、文章、地图、新闻等。这些内容是网站的一部分，且会因页面而异。
- 侧边栏：一些外围信息、链接、引用、广告等。通常与主内容相关（例如一个新闻页面上，侧边栏可能包含作者信息或相关文章链接），还可能存在其他的重复元素，如辅助导航系统。
- 页脚：横跨页面底部的狭长区域。和标题一样，页脚是放置公共信息（比如版权声明或联系方式）的，一般使用较小字体，且通常为次要内容。 还可以通过提供快速访问链接来进行 SEO。

一个“典型的网站”可能会这样布局：
![典型的网站](https://media.prod.mdn.mozit.cloud/attachments/2019/02/14/16497/f9785a592b2ce51e212e1e73ed9b71a2/snapshot.png)

##### 用于构建内容的 HTML

- `<header>`：页眉。
- `<nav>`：导航栏。
- `<main>`：主内容。主内容中还可以有各种子内容区段，可用`<article>`、`<section>` 和 `<div>` 等元素表示。
- `<aside>`：侧边栏，经常嵌套在 `<main>` 中。
- `<footer>`：页脚。

##### HTML 布局元素细节

理解所有 HTML 区段元素具体含义是很有益处的，这一点将随着个人 web 开发经验的逐渐丰富日趋显现。

- `<main>` 存放每个页面独有的内容。每个页面上只能用一次 `<main>`，且直接位于 `<body>` 中。最好不要把它嵌套进其它元素。
- `<article>` 包围的内容即一篇文章，与页面其它部分无关（比如一篇博文）。
- `<section>` 与 `<article>` 类似，但 `<section>` 更适用于组织页面使其按功能（比如迷你地图、一组文章标题和摘要）分块。一般的最佳用法是：以 标题 作为开头；也可以把一篇 `<article>` 分成若干部分并分别置于不同的 `<section>` 中，也可以把一个区段 `<section>` 分成若干部分并分别置于不同的 `<article>` 中，取决于上下文。
- `<aside>` 包含一些间接信息（术语条目、作者简介、相关链接，等等）。
- `<header>` 是简介形式的内容。如果它是 `<body>` 的子元素，那么就是网站的全局页眉。如果它是 `<article>` 或 `<section>` 的子元素，那么它是这些部分特有的页眉（此 `<header>` 非彼 标题）。
- `<nav>` 包含页面主导航功能。其中不应包含二级链接等内容。
- `<footer>` 包含了页面的页脚部分。

**无语义元素：#**  
HTML 提供了 `<div>` 和 `<span>` 元素。  
`<span>` 是一个内联的（inline）无语义元素。最好只用于无法找到更好的语义元素来包含内容时，或者不想增加特定的含义时。  
`<div>` 是一个块级无语义元素，应仅用于找不到更好的块级元素时，或者不想增加特定的意义时。

**换行与水平分割线：**  
`<br>` 可在段落中进行换行；`<br>` 是唯一能够生成多个短行结构（例如邮寄地址或诗歌）的元素。比如：

```html
<p>
  从前有个人叫小高<br />
  他说写 HTML 感觉最好<br />
  但他写的代码结构语义一团糟<br />
  他写的标签谁也懂不了。
</p>
```

`<hr>` 元素在文档中生成一条水平分割线，表示文本中主题的变化（例如话题或场景的改变）。一般就是一条水平的直线。例如：

```html
<p>
  原来这唐僧是个慈悯的圣僧。他见行者哀告，却也回心转意道：“既如此说，且饶你这一次。再休无礼。如若仍前作恶，这咒语颠倒就念二十遍！”行者道：“三十遍也由你，只是我不打人了。”却才伏侍唐僧上马，又将摘来桃子奉上。唐僧在马上也吃了几个，权且充饥。
</p>
<hr />
<p>
  却说那妖精，脱命升空。原来行者那一棒不曾打杀妖精，妖精出神去了。他在那云端里，咬牙切齿，暗恨行者道：“几年只闻得讲他手段，今日果然话不虚传。那唐僧已此不认得我，将要吃饭。若低头闻一闻儿，我就一把捞住，却不是我的人了。不期被他走来，弄破我这勾当，又几乎被他打了一棒。若饶了这个和尚，诚然是劳而无功也。我还下去戏他一戏。”
</p>
```

HTML5 语义化参考[使用 HTML 章节与大纲](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Sections_and_Outlines_of_an_HTML5_document)

#### HTML 除错

##### HTML 和调试

- 语法错误：由于拼写错误导致程序无法运行，通常熟悉语法并理解错误信息后很容易修复。
- 逻辑错误：不存在语法错误，但代码无法按预期运行。通常逻辑错误比语法错误更难修复，因为无法得到指向错误源头的信息。

HTML 本身不容易出现语法错误，因为浏览器是以宽松模式运行的，这意味着即使出现语法错误浏览器依然会继续运行。

**HTML 验证：**
最好的方法就是让你的 HTML 页面通过 Markup Validation Service。由 W3C（制定 HTML、CSS 和其他网络技术标准的组织） 创立并维护的标记验证服务。把一个 HTML 文档加载至本网页并运行 ，网页会返回一个错误报告。
![错误报告](https://media.prod.mdn.mozit.cloud/attachments/2016/02/08/12441/7389d3a6d543673dbedba7e2beddaa33/validator.png)

### 多媒体与嵌入

#### HTMl 中的图片

**备选文本：**  
 alt 它的值应该是对图片的文字描述，用于在图片无法显示或不能被看到的情况。例如：

```html
<img
  src="images/dinosaur.jpg"
  alt="The head and torso of a dinosaur skeleton;
         it has a large head with long sharp teeth"
/>
```

alt 的使用好处：

- 用户有视力障碍，通过屏幕阅读器来浏览网页 。事实上，给图片一个备选的描述文本对大多数用户都是很有用的。
- 把图片的路径或文件名拼错。
- 浏览器不支持该图片类型。某些用户仍在使用纯文本的浏览器，例如 Lynx，这些浏览器会把图片替换为描述文本。
- 你会想提供一些文字描述来给搜索引擎使用，例如搜索引擎可能会将图片的文字描述和查询条件进行匹配。
- 用户关闭的图片显示以减少数据的传输，这在手机上是十分普遍的，并且在一些国家带宽有限且昂贵。

**宽度和高度：**  
你可以用宽度和高度属性来指定你的图片的高度和宽度（你可以用多种方式找到你的图片的宽度和高度

```html
<img
  src="images/dinosaur.jpg"
  alt="一只恐龙头部和躯干的骨架，它有一个巨大的头，长着锋利的牙齿。"
  width="400"
  height="341"
/>
```

你不应该使用 HTML 属性来改变图片的大小。如果你把尺寸设定的太大，最终图片看起来会模糊；如果太小，会在下载远远大于你需要的图片时浪费带宽。如果你没有保持正确的宽高比，图片可能看起来会扭曲。在把图片放到你的网站页面之前，你应该使用图形编辑器使图片的尺寸正确。

**Image titles 图片标题：**  
类似于超链接，你可以给图片增加 title 属性来提供需要更进一步的支持信息。在我们的例子中，可以这样做：

```html
<img
  src="images/dinosaur.jpg"
  alt="一只恐龙头部和躯干的骨架，它有一个巨大的头，长着锋利的牙齿。"
  width="400"
  height="341"
  title="曼彻斯特大学博物馆展出的一只霸王龙的化石"
/>
```

这会给我们一个鼠标悬停提示，看起来就像链接标题。title 有很多易访问性问题，主要是基于这样一个事实，即屏幕阅读器的支持是不可预测的，大多数浏览器都不会显示它，除非您在鼠标悬停时（例如：title 无法访问键盘用户）。

##### 通过为图片搭配说明文字的方式来解说图片

使用 HTML5 的 `<figure>` 和 `<figcaption>` 元素，它正是为此而被创造出来的：为图片提供一个语义容器，在标题和图片之间建立清晰的关联。我们之前的例子可以重写为:

```html
<figure>
  <img
    src="https://raw.githubusercontent.com/mdn/learning-area/master/html/multimedia-and-embedding/images-in-html/dinosaur_small.jpg"
    alt="一只恐龙头部和躯干的骨架，它有一个巨大的头，长着锋利的牙齿。"
    width="400"
    height="341"
  />
  <figcaption>曼彻斯特大学博物馆展出的一只霸王龙的化石</figcaption>
</figure>
```

这个 `<figcaption>` 元素 告诉浏览器和其他辅助的技术工具这段说明文字描述了 `<figure>` 元素的内容。
注意 `<figure>` 里不一定要是一张图片，只要是一个这样的独立内容单元：

- 用简洁、易懂的方式表达意图。
- 可以置于页面线性流的某处。
- 为主要内容提供重要的补充说明。

`<figure>` 可以是几张图片、一段代码、音视频、方程、表格或别的。

##### CSS 背景图片

你也可以使用 CSS 把图片嵌入网站中（JavaScript 也行，不过那是另外一个故事了），这个 CSS 属性 background-image 和另其他 background-\* 属性是用来放置背景图片的。比如，为页面中的所有段落设置一个背景图片，你可以这样做：

```css
p {
  background-image: url('images/dinosaur.jpg');
}
```

#### 视频和音频内容

##### web 中的音频和视频

**`<video>` 标签：**

```html
<video src="rabbit320.webm" controls>
  <p>
    你的浏览器不支持 HTML5 视频。可点击<a href="rabbit320.mp4">此链接</a>观看
  </p>
</video>
```

- src
  同 `<img>` 标签使用方式相同，src 属性指向你想要嵌入网页当中的视频资源，他们的使用方式完全相同。
- controls
  用户必须能够控制视频和音频的回放功能。你可以使用浏览器提供的控制接口，同时你也可以使用合适的 JavaScript API 构建控制接口。至少，这些媒体应该包括开始和停止，以及调整音量的功能。
- `<video>` 标签内的段落
  这个叫做后备内容 — 当浏览器不支持 `<video>` 标签的时候，它将会显示出来，它使我们能够对旧的浏览器做一些兼容处理。你可以添加任何后备内容，在这个例子中我们提供了一个指向这个视频文件的链接，从而使用户可以至少访问到这个文件，而不会局限于浏览器的支持。

```html
<video controls>
  <source src="rabbit320.mp4" type="video/mp4" />
  <source src="rabbit320.webm" type="video/webm" />
  <p>
    你的浏览器不支持 HTML5 视频。可点击<a href="rabbit320.mp4">此链接</a>观看
  </p>
</video>
```

现在我们将 src 属性从 `<video>` 标签中移除，转而将它放在几个单独的标签 `<source>` 当中。在这个例子当中，浏览器将会检查 `<source>` 标签，并且播放第一个与其自身 codec 相匹配的媒体。你的视频应当包括 WebM 和 MP4 两种格式，这两种在目前已经足够支持大多数平台和浏览器。  
每个 `<source>` 标签页含有一个 type 属性，这个属性是可选的，但是建议你添加上这个属性 — 它包含了视频文件的 [MIME types](https://developer.mozilla.org/zh-CN/docs/Glossary/MIME_type)

**其他 `<video>` 特性：**

- width 和 height
  你可以用属性控制视频的尺寸，也可以用 CSS 来控制视频尺寸。 无论使用哪种方式，视频都会保持它原始的长宽比 — 也叫做纵横比。如果你设置的尺寸没有保持视频原始长宽比，那么视频边框将会拉伸，而未被视频内容填充的部分，将会显示默认的背景颜色。
- autoplay
  这个属性会使音频和视频内容立即播放，即使页面的其他部分还没有加载完全。建议不要应用这个属性在你的网站上，因为用户们会比较反感自动播放的媒体文件。
- loop
  这个属性可以让音频或者视频文件循环播放。同样不建议使用，除非有必要。
- muted
  这个属性会导致媒体播放时，默认关闭声音。
- poster
  这个属性指向了一个图像的 URL，这个图像会在视频播放前显示。通常用于粗略的预览或者广告。
- preload
  这个属性被用来缓冲较大的文件，有 3 个值可选：
  - "none" ：不缓冲
  - "auto" ：页面加载后缓存媒体文件
  - "metadata" ：仅缓冲文件的元数据

**`<audio>` 标签：**

```html
<audio controls>
  <source src="viper.mp3" type="audio/mp3" />
  <source src="viper.ogg" type="audio/ogg" />
  <p>你的浏览器不支持 HTML5 音频，可点击<a href="viper.mp3">此链接</a>收听。</p>
</audio>
```

音频播放器所占用的空间比视频播放器要小，由于它没有视觉部件 — 你只需要显示出能控制音频播放的控件。一些与 HTML5 `<video>` 的差异如下：

- `<audio>` 标签不支持 width/height 属性 — 由于其并没有视觉部件，也就没有可以设置 width/height 的内容。
- 同时也不支持 poster 属性 — 同样，没有视觉部件。

`<audio>` 标签支持所有 `<video>` 标签拥有的特性 — 你可以回顾上面了解更多的有关信息

##### 显示音轨文本

给那些听不懂音频语言的人们提供一个音频内容的副本岂不是一件很棒的事情吗？所以，感谢 HTML5 `<video>`使之成为可能，有了 WebVTT 格式，你可以使用`<track>` 标签。  
让其与 HTML 媒体一起显示，你需要做如下工作：

以 .vtt 后缀名保存文件。
用 `<track>` 标签链接 .vtt 文件， `<track>` 标签需放在 `<audio>` 或 `<video>` 标签当中，同时需要放在所有 `<source>` 标签之后。使用 kind 属性来指明是哪一种类型，如 subtitles 、 captions 、 descriptions。然后，使用 srclang 来告诉浏览器你是用什么语言来编写的 subtitles。

```html
<video controls>
  <source src="example.mp4" type="video/mp4" />
  <source src="example.webm" type="video/webm" />
  <track kind="subtitles" src="subtitles_en.vtt" srclang="en" />
</video>
```

kind 你可以根据不同的需求来显示不同的样式，最常见的如下：

- subtitles
  通过添加翻译字幕，来帮助那些听不懂外国语言的人们理解音频当中的内容。
- captions
  同步翻译对白，或是描述一些有重要信息的声音，来帮助那些不能听音频的人们理解音频中的内容。
- timed descriptions
  将文字转换为音频，用于服务那些有视觉障碍的人。

#### 从对象到 iframe —— 其他嵌入技术

```html
<iframe
  src="https://developer.mozilla.org/en-US/docs/Glossary"
  width="100%"
  height="500"
  frameborder="0"
  allowfullscreen
  sandbox
>
  <p>
    <a href="https://developer.mozilla.org/en-US/docs/Glossary">
      Fallback link for browsers that don't support iframes
    </a>
  </p>
</iframe>
```

此示例包括使用以下所需的`<iframe>`基本要素：

- allowfullscreen
  如果设置，`<iframe>`则可以通过全屏 API 设置为全屏模式（稍微超出本文的范围）。
- frameborder
  如果设置为 1，则会告诉浏览器在此框架和其他框架之间绘制边框，这是默认行为。0 删除边框。不推荐这样设置，因为在 CSS 中可以更好地实现相同的效果。border: none;
- src
  该属性与`<video>`/`<img>`一样包含指向要嵌入文档的 URL 路径。
- width 和 height
  这些属性指定您想要的 iframe 的宽度和高度。
- 备选内容
  与`<video>`等其他类似元素相同，您可以在`<iframe></iframe>`标签之间包含备选内容，如果浏览器不支持`<iframe>`，将会显示备选内容，这种情况下，我们已经添加了一个到该页面的链接。现在您几乎不可能遇到任何不支持`<iframe>`的浏览器。
- sandbox
  该属性需要在已经支持其他`<iframe>`功能（例如 IE 10 及更高版本）但稍微更现代的浏览器上才能工作，该属性可以提高安全性设置; 我们将在下一节中更加详细地谈到。

**安全隐患：**

- 使用 HTTPS
  - HTTPS 减少了远程内容在传输过程中被篡改的机会，
  - HTTPS 防止嵌入式内容访问您的父文档中的内容，反之亦然。
- 始终使用 sandbox 属性
  您可以逐个添加权限（sandbox=""属性值内） - 请参阅[sandbox](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/iframe)所有可用选项的参考条目。其中重要的一点是，你永远不应该同时添加 allow-scripts 和 allow-same-origin 到你的 sandbox 属性中-在这种情况下，嵌入式内容可以绕过阻止站点执行脚本的同源安全策略，并使用 JavaScript 完全关闭沙盒。
- 配置 CSP 指令
  CSP 代表[内容安全策略](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/CSP)，它提供一组 HTTP 标头（由 web 服务器发送时与元数据一起发送的元数据），旨在提高 HTML 文档的安全性。在`<iframe>`安全性方面，您可以[将服务器配置为发送适当的 X-Frame-Options 标题。](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/X-Frame-Options)这样做可以防止其他网站在其网页中嵌入您的内容（这将导致点击和一系列其他攻击），正如我们之前看到的那样，MDN 开发人员已经做了这些工作。

##### `<embed>`和`<object>`元素

`<embed>`和`<object>`元素的功能不同于`<iframe>`—— 这些元素是用来嵌入多种类型的外部内容的通用嵌入工具，其中包括像 Java 小程序和 Flash，PDF（可在浏览器中显示为一个 PDF 插件）这样的插件技术，甚至像视频，SVG 和图像的内容！

```html
<embed
  src="whoosh.swf"
  quality="medium"
  bgcolor="#ffffff"
  width="550"
  height="400"
  name="whoosh"
  align="middle"
  allowScriptAccess="sameDomain"
  allowFullScreen="false"
  type="application/x-shockwave-flash"
  pluginspage="http://www.macromedia.com/go/getflashplayer"
/>
```

```html
<object
  data="mypdf.pdf"
  type="application/pdf"
  width="800"
  height="1200"
  typemustmatch
>
  <p>
    You don't have a PDF plugin, but you can
    <a href="myfile.pdf">download the PDF file.</a>
  </p>
</object>
```

然而，您不太可能使用这些元素 - Applet 几年来一直没有被使用；由于许多原因，Flash 不再受欢迎（见下面的插件案例）；PDF 更倾向于被链接而不是被嵌入；其他内容，如图像和视频都有更优秀、更容易元素来处理。插件和这些嵌入方法真的是一种传统技术，我们提及它们主要是为了以防您在某些情况下遇到问题，比如内部网或企业项目等。

#### 为 Web 新增矢量图

- 位图使用像素网格来定义 — 一个位图文件精确得包含了每个像素的位置和它的色彩信息。流行的位图格式包括 Bitmap (.bmp), PNG (.png), JPEG (.jpg), and GIF (.gif.)
- 矢量图使用算法来定义 — 一个矢量图文件包含了图形和路径的定义，电脑可以根据这些定义计算出当它们在屏幕上渲染时应该呈现的样子。 SVG 格式可以让我们创造用于 Web 的精彩的矢量图形。

##### SVG 是什么？

SVG 是用于描述矢量图像的 XML 语言。 它基本上是像 HTML 一样的标记，只是你有许多不同的元素来定义要显示在图像中的形状，以及要应用于这些形状的效果。 SVG 用于标记图形，而不是内容。

```html
<svg
  version="1.1"
  baseProfile="full"
  width="300"
  height="200"
  xmlns="http://www.w3.org/2000/svg"
>
  <rect width="100%" height="100%" fill="black" />
  <circle cx="150" cy="100" r="90" fill="blue" />
</svg>
```

优点

- 矢量图像中的文本仍然可访问（这也有利于 SEO)）。
- SVG 可以很好地适应样式/脚本，因为图像的每个组件都是可以通过 CSS 或通过 JavaScript 编写的样式的元素。

缺点

- SVG 非常容易变得复杂，这意味着文件大小会增加; 复杂的- SVG 也会在浏览器中占用很长的处理时间。
- SVG 可能比栅格图像更难创建，具体取决于您尝试创建哪种图像。
- 旧版浏览器不支持 SVG，因此如果您需要在网站上支持旧版本的 IE，则可能不适合（SVG 从 IE9 开始得到支持）

##### 将 SVG 添加到页面

**快捷方式`<img>`：**  
要通过 `<img>`元素嵌入 SVG，你只需要按照预期的方式在 src 属性中引用它。

```html
<img
  src="equilateral.svg"
  alt="triangle with all three sides equal"
  height="87px"
  width="100px"
/>
```

优点

- 快速，熟悉的图像语法与 alt 属性中提供的内置文本等效。
- 可以通过在`<a>`元素嵌套`<img>`，使图像轻松地成为超链接。

缺点

- 无法使用 JavaScript 操作图像。
- 如果要使用 CSS 控制 SVG 内容，则必须在 SVG 代码中包含内联 CSS 样式。 （从 SVG 文件调用的外部样式表不起作用）
- 不能用 CSS 伪类来重设图像样式（如:focus）。

**疑难解答和跨浏览器支持：**

对于不支持 SVG（IE 8 及更低版本，Android 2.3 及更低版本）的浏览器，您可以从 src 属性引用 PNG 或 JPG，并使用 srcset 属性 只有最近的浏览器才能识别）来引用 SVG。

```html
<img
  src="equilateral.png"
  alt="triangle with equal sides"
  srcset="equilateral.svg"
/>
```

您还可以使用 SVG 作为 CSS 背景图像，如下所示。 在下面的代码中，旧版浏览器会坚持他们理解的 PNG，而较新的浏览器将加载 SVG：

```css
.test {
  background: url('fallback.png') no-repeat center;
  background-image: url('image.svg');
  background-size: contain;
}
```

**如何在 HTML 中引入 SVG 代码：**

你还可以在文本编辑器中打开 SVG 文件，复制 SVG 代码，并将其粘贴到 HTML 文档中 - 这有时称为将 SVG 内联或内联 SVG。确保您的 SVG 代码在`<svg></svg>`标签中（不要在外面添加任何内容）

```html
<svg width="300" height="200">
  <rect width="100%" height="100%" fill="green" />
</svg>
```

优点

- 将 SVG 内联减少 HTTP 请求，可以减少加载时间。
- 您可以为 SVG 元素分配 class 和 id，并使用 CSS 修改样式，无论是在 SVG 中，还是 HTML 文档中的 CSS 样式规则。 实际上，您可以使用任何 SVG 外观属性 作为 CSS 属性。
- 内联 SVG 是唯一可以让您在 SVG 图像上使用 CSS 交互（如:focus）和 CSS 动画的方法（即使在常规样式表中）。
- 您可以通过将 SVG 标记包在`<a>`元素中，使其成为超链接。

缺点

- 这种方法只适用于在一个地方使用的 SVG。多次使用会导致资源密集型维护（resource-intensive maintenance）。
- 额外的 SVG 代码会增加 HTML 文件的大小。
- 浏览器不能像缓存普通图片一样缓存内联 SVG。
- 您可能会在`<foreignObject>` 元素中包含回退，但支持 SVG 的浏览器仍然会下载任何后备图像。你需要考虑仅仅为支持过时的浏览器，而增加额外开销是否真的值得。

**如何使用 `<iframe>` 嵌入 SVG：**

您可以在浏览器中打开 SVG 图像，就像网页一样。 因此，使用`<iframe>`嵌入 SVG 文档就像我们在 从对象到 iframe - 其他嵌入技术 中进行研究一样

```html
<iframe src="triangle.svg" width="500" height="500" sandbox>
  <img src="triangle.png" alt="Triangle with three unequal sides" />
</iframe>
```

这绝对不是最好的方法：

缺点

- 如你所知， iframe 有一个回退机制，如果浏览器不支持 iframe，则只会显示回退。
- 此外，除非 SVG 和您当前的网页具有相同的 origin，否则你不能在主页面上使用 JavaScript 来操纵 SVG。

#### 自适应图片

##### 怎样创建自适应的图片?

**分辨率切换——不同的尺寸：**

我们可以使用两个新的属性——srcset 和 sizes——来提供更多额外的资源图像和提示，帮助浏览器选择正确的一个资源。

```html
<img
  srcset="
    elva-fairy-320w.jpg 320w,
    elva-fairy-480w.jpg 480w,
    elva-fairy-800w.jpg 800w
  "
  sizes="(max-width: 320px) 280px,
            (max-width: 480px) 440px,
            800px"
  src="elva-fairy-800w.jpg"
  alt="Elva dressed as a fairy"
/>
```

srcset 定义了我们允许浏览器选择的图像集，以及每个图像的大小。在每个逗号之前，我们写：

1. 一个文件名 (elva-fairy-480w.jpg.)
2. 一个空格
3. 图像的固有宽度（以像素为单位）（480w）——注意到这里使用 w 单位，而不是你预计的 px。这是图像的真实大小，可以通过检查你电脑上的图片文件找到（例如，在 Mac 上，你可以在 Finder 上选择这个图像，然后按 Cmd + I 来显示信息）。

sizes 定义了一组媒体条件（例如屏幕宽度）并且指明当某些媒体条件为真时，什么样的图片尺寸是最佳选择—我们在之前已经讨论了一些提示。在这种情况下，在每个逗号之前，我们写：

1. 一个媒体条件（(max-width:480px)）——在这里，我们说“当可视窗口的宽度是 480 像素或更少”。
2. 一个空格
3. 当媒体条件为真时，图像将填充的槽的宽度（440px）

所以，有了这些属性，浏览器会：

1. 查看设备宽度
2. 检查 sizes 列表中哪个媒体条件是第一个为真
3. 查看给予该媒体查询的槽大小
4. 加载 srcset 列表中引用的最接近所选的槽大小的图像

老旧的浏览器不支持这些特性，它会忽略这些特征。并继续正常加载 src 属性引用的图像文件。

**一些有用的开发工具：**

这里有一些在浏览器中的非常实用的开发者工具用来帮助制定重要的槽宽度，以及其他你可能会用到的场景。当我在设置槽宽度的时候，我先加载了示例中的无响应的版本（not-responsive.html），然后进入 响应设计视图 （Tools > Web Developer > Responsive Design View），这个工具允许你在不同设备的屏幕宽度场景下查看网页的布局。

**分辨率切换——相同的尺寸, 不同的分辨率：**

如果你支持多种分辨率显示，但希望每个人在屏幕上看到的图片的实际尺寸是相同的，你可以让浏览器通过 srcset 和 x 语法结合——一种更简单的语法——而不用 sizes，来选择适当分辨率的图片。

```html
<img
  srcset="elva-fairy-320w.jpg, elva-fairy-480w.jpg 1.5x, elva-fairy-640w.jpg 2x"
  src="elva-fairy-640w.jpg"
  alt="Elva dressed as a fairy"
/>
```

在这种情况下，sizes 并不需要——浏览器只是计算出正在显示的显示器的分辨率，然后提供 srcset 引用的最适合的图像。因此，如果访问页面的设备具有标准/低分辨率显示，一个设备像素表示一个 CSS 像素，elva-fairy-320w.jpg 会被加载（1x 是默认值，所以你不需要写出来）。如果设备有高分辨率，两个或更多的设备像素表示一个 CSS 像素，elva-fairy-640w.jpg 会被加载。640px 的图像大小为 93KB，320px 的图像的大小仅仅有 39KB。

**美术设计：**

美术设计问题涉及要更改显示的图像以适应不同的图像显示尺寸。例如，如果在桌面浏览器上的一个网站上显示一张大的、横向的照片，照片中央有个人，然后当在移动端浏览器上浏览这个网站时，照片会缩小，这时照片上的人会变得非常小，看起来会很糟糕。这种情况可能在移动端显示一个更小的肖像图会更好，这样人物的大小看起来更合适。

让我们改用 `<picture>`！就像`<video>`和`<audio>`，`<picture>`素包含了一些`<source>`元素，它使浏览器在不同资源间做出选择，紧跟着的是最重要的`<img>`元素。

```html
<picture>
  <source media="(max-width: 799px)" srcset="elva-480w-close-portrait.jpg" />
  <source media="(min-width: 800px)" srcset="elva-800w.jpg" />
  <img src="elva-800w.jpg" alt="Chris standing up holding his daughter Elva" />
</picture>
```

- `<source>`元素包含一个 media 属性，这一属性包含一个媒体条件——就像第一个 srcset 例子，这些条件来决定哪张图片会显示——第一个条件返回真，那么就会显示这张图片。在这种情况下，如果视窗的宽度为 799px 或更少，第一个`<source>`元素的图片就会显示。如果视窗的宽度是 800px 或更大，就显示第二张图片。
- srcset 属性包含要显示图片的路径。请注意，正如我们在`<img>`上面看到的那样，`<source>`可以使用引用多个图像的- srcset 属性，还有 sizes 属性。所以你可以通过一个 `<picture>`元素提供多个图片，不过也可以给每个图片提供多分辨率的图片。实际上，你可能不想经常做这样的事情。
- 在任何情况下，你都必须在 `</picture>`之前正确提供一个`<img>`元素以及它的 src 和 alt 属性，否则不会有图片显示。当媒体条件都不返回真的时候（你可以在这个例子中删除第二个`<source>` 元素），它会提供图片；如果浏览器不支持 `<picture>`元素时，它可以作为后备方案。

这样的代码允许我们在宽屏和窄屏上都能显示合适的图片，像下面展示的一样：
![PC自适应图片](https://mdn.mozillademos.org/files/12940/picture-element-wide.png)
![移动端自适应图片](https://mdn.mozillademos.org/files/12938/picture-element-narrow.png)

**大胆的使用现代图像格式：**

`<picture>`让我们能继续满足老式浏览器的需要。你可以在 type 属性中提供 MIME 类型，这样浏览器就能立即拒绝其不支持的文件类型：

```html
<picture>
  <source type="image/svg+xml" srcset="pyramid.svg" />
  <source type="image/webp" srcset="pyramid.webp" />
  <img
    src="pyramid.png"
    alt="regular pyramid built from four equilateral triangles"
  />
</picture>
```

- 不要使用 media 属性，除非你也需要美术设计。
- 在`<source>` 元素中，你只可以引用在 type 中声明的文件类型。
- 像之前一样，如果必要，你可以在 srcset 和 sizes 中使用逗号分割的列表。

### HTML 表格

#### HTML 表格基础

**什么时候你不应该使用 HTML 表格?**  
HTML 表格 应该用于表格数据 ，这正是 HTML 表格设计出来的用途. 不幸的是, 许多人习惯用 HTML 表格来实现网页布局。

- 表格布局减少了视觉受损的用户的可访问性: 屏幕阅读器, 被盲人所使用, 解析存在于 HTML 页面上的标签，然后为用户读出其中的内容。因为对于布局来说，表格不是一个正确的工具， 使用的标记比使用 CSS 布局技术更复杂, 所以屏幕阅读器的输出会让他们的用户感到困惑。
- 表格会产生很多标签: 正如刚才提到的, 表格布局通常会比正确的布局技术涉及更复杂的标签结构，这会导致代码变得更难于编写、维护、调试.
- 表格不能自动响应: 当你使用正确的布局容器 (比如 `<header>`, `<section>`, `<article>`, 或是 `<div>`), 它们的默认宽度是父元素的 100%. 而表格的的默认大小是根据其内容而定的。因此，需要采取额外的措施来获取表格布局样式，以便有效地在各种设备上工作。

##### 使用 <th> 元素添加标题

[标题表格](https://mdn.github.io/learning-area/html/tables/basic/dogs-table-fixed.html)

```html
<table>
  <tr>
    <th colspan="2">Animals</th>
  </tr>
  <tr>
    <th colspan="2">Hippopotamus</th>
  </tr>
  <tr>
    <th rowspan="2">Horse</th>
    <td>Mare</td>
  </tr>
  <tr>
    <td>Stallion</td>
  </tr>
  <tr>
    <th colspan="2">Crocodile</th>
  </tr>
  <tr>
    <th rowspan="2">Chicken</th>
    <td>Hen</td>
  </tr>
  <tr>
    <td>Rooster</td>
  </tr>
</table>
```

**为什么标题是有用的?**

当标题明显突出的时候，你可以更加简单地找到你想找的数据，设计上也会看起来更好。  
表格标题也有额外的好处，随着 scope 属性 (我们将在下一篇文章中了解到)，这个属性允许你让表格变得更加无障碍，每个标题与相同行或列中的所有数据相关联。屏幕阅读设备能一次读出一列或一行的数据，这是非常有帮助的。

##### 允许单元格跨越多行和列

有时我们希望单元格跨越多行或多列。让我们使用 colspan 和 rowspan 来改进现有的表格。
[单元格跨越表格](https://mdn.github.io/learning-area/html/tables/basic/animals-table-fixed.html)

```html
<table>
  <tr>
    <th colspan="2">Animals</th>
  </tr>
  <tr>
    <th colspan="2">Hippopotamus</th>
  </tr>
  <tr>
    <th rowspan="2">Horse</th>
    <td>Mare</td>
  </tr>
  <tr>
    <td>Stallion</td>
  </tr>
  <tr>
    <th colspan="2">Crocodile</th>
  </tr>
  <tr>
    <th rowspan="2">Chicken</th>
    <td>Hen</td>
  </tr>
  <tr>
    <td>Rooster</td>
  </tr>
</table>
```

##### 为表格中的列提供共同的样式

在我们继续介绍之前，我们将介绍本文中的最后一个功能。HTML 有一种方法可以定义整列数据的样式信息：就是 `<col>` 和 `<colgroup>` 元素。 它们存在是因为如果你想让一列中的每个数据的样式都一样，那么你就要为每个数据都添加一个样式，这样的做法是令人厌烦和低效的。你通常需要在列中的每个 <td> 或 <th> 上定义样式，或者使用一个复杂的选择器，比如 :nth-child()。

```html
<table>
  <tr>
    <th>Data 1</th>
    <th style="background-color: yellow">Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td style="background-color: yellow">Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td style="background-color: yellow">Jazz</td>
  </tr>
</table>
```

这样不太理想，因为我们不得不在列中的每个单元格中重复那些样式信息 (在真实的项目中，我们或许会设置一个 class 包含那三个单元格 ，然后在一个单独的样式表中定义样式). 为了舍弃这种做法，我们可以只定义一次，在 `<col>` 元素中。`<col>` 元素被规定包含在 `<colgroup>` 容器中，而 `<colgroup>`就在 `<table>` 标签的下方。我们可以通过如下的做法来创建与上面相同的效果:

```html
<table>
  <colgroup>
    <col />
    <col style="background-color: yellow" />
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>
```

如果你想把这种样式信息应用到每一列，我们可以只使用一个 `<col>` 元素，不过需要包含 span 属性，像这样：

```html
<colgroup>
  <col style="background-color: yellow" span="2" />
</colgroup>
```

一个复杂点的例子：

```html
<table>
  <colgroup>
    <col span="2" />
    <col style="background-color:#97DB9A;" />
    <col style="width:42px;" />
    <col style="background-color:#97DB9A;" />
    <col style="background-color:#DCC48E; border:4px solid #C1437A;" />
    <col span="2" style="width:42px;" />
  </colgroup>
  <tr>
    <td>&nbsp;</td>
    <th>Mon</th>
    <th>Tues</th>
    <th>Wed</th>
    <th>Thurs</th>
    <th>Fri</th>
    <th>Sat</th>
    <th>Sun</th>
  </tr>
  <tr>
    <th>1st period</th>
    <td>English</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
    <td>German</td>
    <td>Dutch</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <th>2nd period</th>
    <td>English</td>
    <td>English</td>
    <td>&nbsp;</td>
    <td>German</td>
    <td>Dutch</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <th>3rd period</th>
    <td>&nbsp;</td>
    <td>German</td>
    <td>&nbsp;</td>
    <td>German</td>
    <td>Dutch</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <th>4th period</th>
    <td>&nbsp;</td>
    <td>English</td>
    <td>&nbsp;</td>
    <td>English</td>
    <td>Dutch</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
</table>
```

[表格效果](https://mdn.github.io/learning-area/html/tables/basic/timetable-fixed.html)

#### HTML 高级表格特性和可访问性

##### 使用 `<caption>` 为你的表格增加一个标题

你可以为你的表格增加一个标题，通过 `<caption>` 元素，再把 `<caption>` 元素放入 `<table>` 元素中. 你应该把它放在`<table>` 标签的下面。

```html
<table>
  <caption>
    Dinosaurs in the Jurassic period
  </caption>

  ...
</table>
```

##### 添加 `<thead>`, `<tfoot>`, 和 `<tbody>` 结构

- `<thead>` 需要嵌套在 table 元素中，放置在头部的位置，因为它通常代表第一行，第一行中往往都是每列的标题，但是不是每种情况都是这样的。如果你使用了 `<col>`/`<colgroup>` 元素，那么 `<thead>`元素就需要放在它们的下面。
- `<tfoot>` 需要嵌套在 table 元素中，放置在底部 (页脚)的位置，一般是最后一行，往往是对前面所有行的总结，比如，你可以按照预想的方式将`<tfoot>`放在表格的底部，或者就放在 `<thead>` 的下面。(浏览器仍将它呈现在表格的底部)
- `<tbody>` 需要嵌套在 table 元素中，放置在 `<thead>`的下面或者是 `<tfoot>` 的下面，这取决于你如何设计你的结构。(`<tfoot>`放在`<thead>`下面也可以生效.)

```html
<table>
  <caption>
    How I chose to spend my money
  </caption>
  <thead>
    <tr>
      <th>Purchase</th>
      <th>Location</th>
      <th>Date</th>
      <th>Evaluation</th>
      <th>Cost (€)</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td colspan="4">SUM</td>
      <td>118</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Haircut</td>
      <td>Hairdresser</td>
      <td>12/09</td>
      <td>Great idea</td>
      <td>30</td>
    </tr>
    <tr>
      <td>Lasagna</td>
      <td>Restaurant</td>
      <td>12/09</td>
      <td>Regrets</td>
      <td>18</td>
    </tr>
    <tr>
      <td>Shoes</td>
      <td>Shoeshop</td>
      <td>13/09</td>
      <td>Big regrets</td>
      <td>65</td>
    </tr>
    <tr>
      <td>Toothpaste</td>
      <td>Supermarket</td>
      <td>13/09</td>
      <td>Good</td>
      <td>5</td>
    </tr>
  </tbody>
</table>
```

[table 效果](https://mdn.github.io/learning-area/html/tables/advanced/spending-record-finished.html)

##### 嵌套表格

这样通常是不建议的，因为这种做法会使标记看上去很难理解，对使用屏幕阅读的用户来说，可访问性也降低了。

```html
<table id="table1">
  <tr>
    <th>title1</th>
    <th>title2</th>
    <th>title3</th>
  </tr>
  <tr>
    <td id="nested">
      <table id="table2">
        <tr>
          <td>cell1</td>
          <td>cell2</td>
          <td>cell3</td>
        </tr>
      </table>
    </td>
    <td>cell2</td>
    <td>cell3</td>
  </tr>
  <tr>
    <td>cell4</td>
    <td>cell5</td>
    <td>cell6</td>
  </tr>
</table>
```

[内嵌 table 效果](https://mdn.github.io/learning-area/html/tables/advanced/nested-tables.html)

##### 对于视力受损的用户的表格

**scope 属性：**

可以添加在`<th>` 元素中，用来帮助屏幕阅读设备更好地理解那些标题单元格。

```html
<thead>
  <tr>
    <th scope="col">Purchase</th>
    <th scope="col">Location</th>
    <th scope="col">Date</th>
    <th scope="col">Evaluation</th>
    <th scope="col">Cost (€)</th>
  </tr>
</thead>
```

以及每一行都可以这样定义一个行标题 (如果我们已经使用了 th 和 td 元素)：

```html
<tr>
  <th scope="row">Haircut</th>
  <td>Hairdresser</td>
  <td>12/09</td>
  <td>Great idea</td>
  <td>30</td>
</tr>
```

scope 还有两个可选的值 ： colgroup 和 rowgroup。这些用于位于多个列或行的顶部的标题。

**id 和标题属性：**

如果要替代 scope 属性，可以使用 id 和 headers 属性来创造标题与单元格之间的联系。使用方法如下:

1. 为每个`<th>` 元素添加一个唯一的 id 。
2. 为每个 `<td>` 元素添加一个 headers 属性。每个单元格的 headers 属性需要包含它从属于的所有标题的 id，之间用空格分隔开。

```html
<thead>
  <tr>
    <th id="purchase">Purchase</th>
    <th id="location">Location</th>
    <th id="date">Date</th>
    <th id="evaluation">Evaluation</th>
    <th id="cost">Cost (€)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th id="haircut">Haircut</th>
    <td headers="location haircut">Hairdresser</td>
    <td headers="date haircut">12/09</td>
    <td headers="evaluation haircut">Great idea</td>
    <td headers="cost haircut">30</td>
  </tr>

  ...
</tbody>
```

### HTML 表单

#### 如何构建 HTML 表单

##### `<form>` 元素

所有 HTML 表单都以一个`<form>`元素开始：

```html
<form action="/my-handling-form-page" method="post"></form>
```

- action 属性定义了在提交表单时,应该把所收集的数据送给谁(/那个模块)(URL)去处理。.
- method 属性定义了发送数据的 HTTP 方法(它可以是“get”或“post”).

##### `<fieldset>` 和 `<legend>` 元素

你可以在`<fieldset>`开口标签后加上一个 `<legend>`元素来给`<fieldset>` 标上标签。 `<legend>`的文本内容正式地描述了`<fieldset>`里所含有部件的用途。

```html
<form>
  <fieldset>
    <legend>Fruit juice size</legend>
    <p>
      <input type="radio" name="size" id="size_1" value="small" />
      <label for="size_1">Small</label>
    </p>
    <p>
      <input type="radio" name="size" id="size_2" value="medium" />
      <label for="size_2">Medium</label>
    </p>
    <p>
      <input type="radio" name="size" id="size_3" value="large" />
      <label for="size_3">Large</label>
    </p>
  </fieldset>
</form>
```

[form 预览](https://mdn.github.io/learning-area/html/forms/html-form-structure/fieldset-legend.html)

当阅读上述表单时，屏幕阅读器将会读第一个小部件“Fruit juice size small”，“Fruit juice size medium”为第二个，“Fruit juice size large”为第三个。

##### `<label>`元素

```html
<label for="name">Name:</label> <input type="text" id="name" name="user_name" />
```

`<label>` 标签与 `<input>` 通过他们各自的 for 属性和 id 属性正确相关联（label 的 for 属性和它对应的小部件的 id 属性），这样，屏幕阅读器会读出诸如“Name, edit text”之类的东西。

**标签也可点击!**

正确设置标签的另一个好处是可以在所有浏览器中单击标签来激活相应的小部件。

**多个标签：**

在多个标签的情况下，您应该将一个小部件和它的标签嵌套在一个`<label>`元素中。

```html
<p>Required fields are followed by <abbr title="required">*</abbr>.</p>

<!--这样写：-->
<div>
  <label for="username">Name:</label>
  <input type="text" name="username" />
  <label for="username"><abbr title="required">*</abbr></label>
</div>

<!--但是这样写会更好：-->
<div>
  <label for="username">
    <span>Name:</span>
    <input id="username" type="text" name="username" />
    <abbr title="required">*</abbr>
  </label>
</div>

<!--但最好的可能是这样：-->
<div>
  <label for="username">Name: <abbr title="required">*</abbr></label>
  <input id="username" type="text" name="username" />
</div>
```

- 在第一个例子中，标签根本没有和 input 一起被念出来——读出来的只是“edit the blank”，和单独被念出的标签。多个`<label>`元素会使屏幕阅读器迷惑。
- 在第二个例子中，事情变得清晰一点了——标签和输入一起，读出的是“name star name edit text”，但标签仍然是单独读出的。这还是有点令人困惑，但这次还是稍微好一点了，因为 input 和 label 联系起来了。
- 第三个例子是最好的——标签是一起读出的，标签和输入读出的是“name star edit text”。

#### 原生表单挂件

##### 通用属性

| 属性名称  | 默认值  | 描述                                                                                                                                                                            |
| --------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| autofocus | (false) | 这个布尔属性允许您指定当页面加载时元素应该自动具有输入焦点，除非用户覆盖它，例如通过键入不同的控件。文档中只有一个与表单相关的元素可以指定这个属性。                            |
| disabled  | (false) | 这个布尔属性表示用户不能与元素交互。如果没有指定这个属性，元素将从包含它的元素继承设置，例如`<fieldset>`;如果没有包含在设定了 disabled 属性的元素里，那么这个元素就是可用的。   |
| form      |         | 小部件与之相关联的表单元素。属性值必需是同个文档中的`<form>` 元素的 id 属性。理论上，它允许您在`<form>`元素之外设置一个表单小部件。然而，在实践中，没有任何支持该特性的浏览器。 |
| name      |         | 元素的名称;这是跟表单数据一起提交的。                                                                                                                                           |
| value     |         | 元素的初始值。                                                                                                                                                                  |

##### 文本输入框

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/single-line-text-fields.html)

所有文本框都有一些通用规范：

- 它们可以被标记为 readonly (用户不能修改输入值)甚至是 disabled (输入值永远不会与表单数据的其余部分一起发送)。
- 它们可以有一个 placeholder; 这是文本输入框中出现的文本，用来简略描述输入框的目的。
- 它们可以被限制在 size 可以输入的最大字符数。

**单行文本框：**

使用 type 属性值被设置为 text 的`<input>`元素创建一个单行文本框

```html
<input type="text" id="comment" name="comment" value="I'm a text field" />
```

单行文本框只有一个真正的约束：如果您输入带有换行符的文本，浏览器会在发送数据之前删除这些换行符。

**E-mail 地址框：**

该类型的框将 type 属性设置为 email 值

```html
<input type="email" id="email" name="email" multiple />
```

当使用 type 时， 用户需要在框中输入有效的电子邮件地址；任何其他内容都会导致浏览器在提交表单时显示错误。  
通过包括 multiple 属性，它还可以让用户将多个电子邮件地址输入相同的输入(以逗号分隔)。

**密码框：**

通过设置 type 属性值为 password 来设置该类型框：

```html
<input type="password" id="pwd" name="pwd" />
```

它不会为输入的文本添加任何特殊的约束，但是它会模糊输入到字段中的值(例如，用点或小行星)，这样它就不能被其他人读取。
保护用户不受窃取你的密码、信用卡信息等影响的最佳方式是在安全连接上托管任何涉及表单的页面(例如:https://……地址)，使得数据在发送之前就已加密。

**搜索框：**

通过设置 type 属性值为 search 来设置该类型框：

```html
<input type="search" id="search" name="search" />
```

给定一个“x”叉号来清除输入的值，它们的值也可以被自动保存用来在同一站点上的多个页面上自动补全。

**电话号码栏：**

通过 type 属性的 tel 值设置该类型框：

```html
<input type="tel" id="tel" name="tel" />
```

由于世界范围内各种各样的电话号码格式，这种类型的字段不会对用户输入的值执行任何限制。这主要是在语义上的区分，可能会出现一个不同的虚拟键盘，更适合输入电话号码。

**URL 栏：**

通过 type 属性的 url 值设置该类型框：

```html
<input type="url" id="url" name="url" />
```

它为字段添加了特殊的验证约束，如果输入无效的 url，浏览器就会报告错误。

**多行文本框：**

多行文本框专指使用 `<textarea>`元素，而不是使用`<input>` 元素。

```html
<textarea cols="30" rows="10"></textarea>
```

textarea 和常规的单行文本字段之间的主要区别是，允许用户输入包含硬换行符(即按回车)的文本。

`<textarea>` 元素属性

| 属性名 | 默认值 | 描述                                                                                                                                     |
| ------ | ------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| cols   | 20     | 文本控件的可见宽度，平均字符宽度。                                                                                                       |
| rows   |        | 控制的可见文本行数。                                                                                                                     |
| wrap   | soft   | 指定文本换行的方式，可能的值：hard 或 soft。hard：在文本到达元素最大宽度的时候换行，soft：在到达元素最大宽度的时候，不会自动插入换行符。 |

这里有两个关键点需要注意：

- 如果您想为`<input>`元素定义一个默认值，那么您必须使用 value 属性;另一方面，对于`<textarea>`元素，只需要将默认的文本放在起始标记和`<textarea>`的结束标记之间。
- 因为它的本质， `<textarea>`元素只接受文本内容；这意味着将任何 HTML 内容放入`<textarea>`中都呈现为纯文本内容。

##### 下拉内容

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/drop-down-content.html)

**选择框：**

一个选择框是用`<select>`元素创建的，其中有一个或多个`<option>`元素作为子元素，每个元素都指定了其中一个可能的值。

```html
<select id="simple" name="simple">
  <option>Banana</option>
  <option>Cherry</option>
  <option>Lemon</option>
</select>
```

selected 属性在所需的`<option>`元素上设置选择框的默认值  
`<option>`元素也可以嵌套在`<optgroup>`元素中，以创建视觉关联的组值：

```html
<select id="groups" name="groups">
  <optgroup label="fruits">
    <option>Banana</option>
    <option selected>Cherry</option>
    <option>Lemon</option>
  </optgroup>
  <optgroup label="vegetables">
    <option>Carrot</option>
    <option>Eggplant</option>
    <option>Potato</option>
  </optgroup>
</select>
```

- `<option>`元素设置了 value 属性则提交表的会发送，否则发送`<option>`元素内容
- `<optgroup>`元素中，label 属性显示的文本无法选择

**多选选择框：**

通过将 multiple 属性添加到`<select>`元素，可选择多个值 (如， 同时按下 Cmd/Ctrl 并点击多个值)。
多选模式下选择框不显示为下拉内容

```html
<select multiple id="multi" name="multi">
  <option>Banana</option>
  <option>Cherry</option>
  <option>Lemon</option>
</select>
```

**自动补全输入框：**

您可以使用`<datalist>`元素来为表单小部件提供建议的、自动完成的值，并使用一些`<option>`子元素来指定要显示的值。
使用 list 属性将数据列表绑定到一个文本框

```html
<label for="myFruit">What's your favorite fruit?</label>
<input type="text" name="myFruit" id="myFruit" list="mySuggestion" />
<datalist id="mySuggestion">
  <option>Apple</option>
  <option>Banana</option>
  <option>Blackberry</option>
  <option>Blueberry</option>
  <option>Lemon</option>
  <option>Lychee</option>
  <option>Peach</option>
  <option>Pear</option>
</datalist>
```

`<datalist>`元素是 HTML 表单的最新补充，老浏览器支持差。数据列表兼容处理：

```html
<label for="myFruit">What is your favorite fruit? (With fallback)</label>
<input type="text" id="myFruit" name="fruit" list="fruitList" />

<datalist id="fruitList">
  <label for="suggestion">or pick a fruit</label>
  <select id="suggestion" name="altFruit">
    <option>Apple</option>
    <option>Banana</option>
    <option>Blackberry</option>
    <option>Blueberry</option>
    <option>Lemon</option>
    <option>Lychee</option>
    <option>Peach</option>
    <option>Pear</option>
  </select>
</datalist>
```

支持`<datalist>`元素的浏览器将忽略所有不是`<option>`元素的元素，并按照预期工作。  
支持显示：  
![自动补全支持](https://developer.mozilla.org/files/4581/datalist-firefox-macos.png)  
不支持显示：
![自动补全不支持](https://developer.mozilla.org/files/4583/datalist-safari.png)

##### 可选中项

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/checkable-items.html)

复选框和单选按钮。两者都使用 checked 属性，选中或未选中。  
`<fieldset>`中包围每个相关项目的列表，并使用`<legend>`提供对列表的全面描述。每个单独的`<label>`/`<input>`元素都应该包含在它自己的列表项中,增加可用性和可访问性。

**复选框：**

使用 type 属性值为 checkbox 的 `<input>`元素来创建一个复选框。

```html
<input type="checkbox" checked id="carrots" name="carrots" value="carrots" />
```

**单选按钮：**

使用 type 属性值为 radio 的 `<input>`元素来创建一个单选按钮。

```html
<input type="radio" checked id="soup" name="meal" />
```

如果它们的 name 属性共享相同的值，那么它们将被认为属于同一组的按钮。

```html
<fieldset>
  <legend>What is your favorite meal?</legend>
  <ul>
    <li>
      <label for="soup">Soup</label>
      <input type="radio" checked id="soup" name="meal" value="soup" />
    </li>
    <li>
      <label for="curry">Curry</label>
      <input type="radio" id="curry" name="meal" value="curry" />
    </li>
    <li>
      <label for="pizza">Pizza</label>
      <input type="radio" id="pizza" name="meal" value="pizza" />
    </li>
  </ul>
</fieldset>
```

##### 按钮

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/button-examples.html)

**submit：**

```html
<button type="submit">This a <br /><strong>submit button</strong></button>

<input type="submit" value="This is a submit button" />
```

**reset：**

```html
<button type="reset">This a <br /><strong>reset button</strong></button>

<input type="reset" value="This is a reset button" />
```

**button：**

```html
<button type="button">This an <br /><strong>anonymous button</strong></button>

<input type="button" value="This is an anonymous button" />
```

不管您使用的是`<button>`元素还是`<input>`元素，按钮的行为都是一样的。然而，有一些显著的不同之处：

- 从示例中可以看到，`<button>`元素允许您在它们的标签中使用 HTML 内容，这些内容被插入到打开和关闭`<button>` 标签中。另一方面，`<input>`元素是空元素;它们的标签插入在 value 属性中，因此只接受纯文本内容。
- 使用`<button>`元素，可以有一个不同于按钮标签的值(通过设置 value 中的属性值)。这在 IE 8 之前的版本中是不可靠的。

在`<input>`元素中，标签只能是字符数据，而在`<button>`元素中，标签可以是 HTML，因此可以相应地进行样式化。

##### 高级表单部件

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/advanced-examples.html)

**数字：**

- 通过设置 min 和 max 属性来约束该值。
- 通过设置 step 属性来指定增加和减少按钮更改小部件的步进值大小。

```html
<input type="number" name="age" id="age" min="1" max="10" step="2" />
```

在 10 以下的 Internet Explorer 版本中不支持 number 输入。

**滑块：**

属性值与数字输入框一样 min、max、step

```html
<input type="range" name="beans" id="beans" min="0" max="500" step="10" />
```

滑块不提供任何形式的视觉反馈，不知道当前值是什么。您需要使用 JavaScript 来添加这一点，添加 span 标签显示当前值

```html
<label for="beans">How many beans can you eat?</label>
<input type="range" name="beans" id="beans" min="0" max="500" step="10" />
<span class="beancount"></span>
```

JavaScript 实现

```javascript
var beans = document.querySelector('#beans');
var count = document.querySelector('.beancount');

count.textContent = beans.value;

beans.oninput = function () {
  count.textContent = beans.value;
};
```

我们设置了一个 oninput 事件处理程序，以便每次移动范围滑块时，都会将 span textContent 更新为新的输入值。

在 10 以下的 Internet Explorer 版本中不支持 range 。

**日期时间选择器：**

- 本地时间  
  这将创建一个小部件来显示和选择一个日期，但是没有任何特定的时区信息。
  ```html
  <input type="datetime-local" name="datetime" id="datetime" />
  ```
- 月  
  这就创建了一个小部件来显示和挑选一个月。
  ```html
  <input type="month" name="month" id="month" />
  ```
- 时间  
  这将创建一个小部件来显示并选择一个时间值。
  ```html
  <input type="time" name="time" id="time" />
  ```
- 星期
  这将创建一个小部件来显示并挑选一个星期号和它的年份。
  ```html
  <input type="week" name="week" id="week" />
  ```

所有日期和时间控制都可以使用 min 和 max 属性来约束。

```html
<label for="myDate">When are you available this summer?</label>
<input
  type="date"
  name="myDate"
  min="2013-06-01"
  max="2013-08-31"
  id="myDate"
/>
```

警告——日期和时间窗口小部件仍然很不受支持,兼容性差。

**拾色器：**

一个颜色小部件是使用 type 属性设置为值 color`<input>`的元素创建的。

```html
<input type="color" name="color" id="color" />
```

警告——并不是所有浏览器都支持拾色器。

##### 其他小部件

[小部件预览](https://mdn.github.io/learning-area/html/forms/native-form-widgets/other-examples.html)

**文件选择器：**

使用`<input>`元素，将它的 type 属性设置为 file。被接受的文件类型可以使用 accept 属性来约束。用户选择多个文件，那么可以通过添加 multiple 属性来实现。

```html
<input type="file" name="file" id="file" accept="image/*" multiple />
```

**隐藏内容：**

有些数据是用表单发送的，但不显示给用户。需要使用`<input>`将它的 type 属性设置为 hidden 值。

```html
<input type="hidden" id="timestamp" name="timestamp" value="1286705410" />
```

**图像按钮：**

图像按钮是使用 type 属性值设置为 image`<input>`的元素创建的。  
这个元素支持与`<img>`元素相同的属性，和其他表单按钮支持的所有属性。

```html
<input type="image" alt="Click me!" src="my-img.png" width="80" height="30" />
```

使用图像按钮来提交表单，这个小部件不会提交它的值；提交的是在图像上单击处的 X 和 Y 坐标(坐标是相对于图像的，这意味着图像的左上角表示坐标 0，0)，坐标被发送为两个键/值对：

- X 值键是 name 属性的值，后面是字符串“.x”。
- Y 值键是 name 属性的值，后面是字符串“.y”。

当您点击这个小部件的图像时，您将被发送到一个 URL，如下所显示的

```url
http://foo.com?pos.x=123&pos.y=456
```

**仪表和进度条：**

- 进度条  
  这个值由 max 属性指定。这样的一个 bar 是使用`<progress>`元素创建的。
  ```html
  <progress max="100" value="75">75/100</progress>
  ```
- 仪表
  一个仪表表示一个固定值，这个值由一个 min 和一个 max 值所界定。

  - low 和 high 值范围划分为三个部分：
    - 该范围的较低部分是在 min 和 low 值(包括那些值)之间。
    - 该范围的中间部分是在 low 和 high 值之间(不包括那些值)。
    - 该范围的较高部分是在 high 和 max 值(包括那些值)之间。
  - optimum 值定义了`<meter>`元素的最优值。在与 htmlattrxref(“low”、“meter”)和 high 值的联合中，它定义了该范围的哪个部分是优先的：
    - 如果 optimum 值在较低的范围内，则较低的范围被认为是首选项，中等范围被认为是一般的，而较高的范围被认为是最坏的部分。
    - 如果 optimum 值在该范围的中等部分，则较低的范围被认为是一个一般的，中等范围被认为是优先的部分，而较高的范围也被认为是平均值。
    - 如果 optimum 值在较高的范围内，则较低的范围被认为是最坏的部分，中等范围被认为是一般的部分，较高的范围被认为是优先的部分。

所有实现`<meter>`元素的浏览器都使用这些值来改变米尺的颜色。

- 如果当前值位于该范围的优先部分，则该条是绿色的。
- 如果当前值位于该范围的平均部分，则该条是黄色的。
- 如果当前值处于最糟糕的范围，则该条是红色的。

```html
<meter min="0" max="100" value="75" low="33" high="66" optimum="50">75</meter>
```

对进度条和仪表的支持是相当不错的，在 Internet Explorer 中没有支持。

#### 发送表单数据

##### 数据都去哪儿了？

在客户端，HTML 表单只不过是一种方便的用户友好的方式，可以配置 HTTP 请求将数据发送到服务器。

![客户端服务器](https://developer.mozilla.org/files/4291/client-server.png)

**在客户端:定义如何发送数据**

`<form>`元素定义了如何发送数据。它的所有属性都是为了让您配置当用户点击提交按钮时发送的请求。两个最重要的属性是 action 和 method。

- action 属性

  ```html
  <!-- 绝对url -->
  <form action="http://foo.com">
    <!-- 相对url -->
    <form action="/somewhere_else">
      <!-- 无 action 数据被发送到表单出现的相同页面上 -->
      <form>
        <!-- 数据应该被发送到包含表单的相同页面上,直到HTML5action属性都需要该符号。现在，这不再需要了。 -->
        <form action="#"></form>
      </form>
    </form>
  </form>
  ```

- method 属性

  - GET 方法  
    当你提交表单的时候，会看到类似`www.foo.com/?say=Hi&to=Mom`这样的 URL,在 URL web 地址结束之后，我们得到一个问号(?)，后面跟着由一个与符号(&)互相分隔开的名称/值对。  
    HTTP 请求如下：

  ```
  GET /?say=Hi&to=Mom HTTP/2.0
  Host: foo.com
  ```

  - POST 方法  
    没有数据会附加到 URL，而数据存在在请求主题内：

  ```
  POST / HTTP/2.0
  Host: foo.com
  Content-Type: application/x-www-form-urlencoded
  Content-Length: 13

  say=Hi&to=Mom
  ```

  Content-Length 数据头表示主体的大小，Content-Type 数据头表示发送到服务器的资源类型。

##### 特殊案例:发送文件

**enctype 属性：**
该属性允许您指定在提交表单时所生成的请求中的 Content-Type 的 HTTP 数据头的值。  
默认情况下，它的值是`application/x-www-form-urlencoded`。

如果你想要发送文件，你需要额外的三个步骤：

- 将 method 属性设置为 POST，因为文件内容不能放入 URL 参数中。
- 将 enctype 的值设置为 multipart/form-data，因为数据将被分成多个部分，每个文件单独占用一个部分，表单正文中包含的文本数据（如果文本也输入到表单中）占用一个部分。
- 包含一个或多个 File picker 小部件，允许用户选择将要上传的文件。

```html
<form method="post" enctype="multipart/form-data">
  <div>
    <label for="file">Choose a file</label>
    <input type="file" id="file" name="myFile" />
  </div>
  <div>
    <button>Send the file</button>
  </div>
</form>
```

##### 常见的安全问题

每次向服务器发送数据时，都需要考虑安全性。HTML 表单是最常见的攻击路径(可能发生攻击的地方)。

**XSS 和 CSRF：**

XSS 允许攻击者将客户端脚本注入到其他用户查看的 Web 页面中。攻击者可以使用跨站点脚本攻击的漏洞来绕过诸如同源策略之类的访问控制。这些攻击的影响可能从一个小麻烦到一个重大的安全风险。

CSRF 攻击类似于 XSS 攻击，因为它们以相同的方式开始攻击——向 Web 页面中注入客户端脚本——但它们的目标是不同的。CSRF 攻击者试图将权限升级到特权用户(比如站点管理员)的级别，以执行他们不应该执行的操作(例如，将数据发送给一个不受信任的用户)。

**SQL 注入：**

SQL 注入是一种试图在目标 web 站点使用的数据库上执行操作的攻击类型。这通常包括发送一个 SQL 请求，希望服务器能够执行它（通常发生在应用服务器试图存储由用户发送的数据时）。

**HTTP 数据头注入和电子邮件注入：**

这种类型的攻击出现在当您的应用程序基于表单上用户的数据输入构建 HTTP 头部或电子邮件时。这些不会直接损害您的服务器或影响您的用户，但它们会引发一个更深入的问题，例如会话劫持或网络钓鱼攻击。

**偏执:永远不要相信你的用户**

所有到达服务器的数据都必须经过检查和消毒。总是这样。没有例外。

- 远离有潜在危险的字符转义。应该如何谨慎使用的特定字符取决于所使用的数据的上下文和所使用的服务器平台，但是所有的服务器端语言都有相应的功能。
- 限制输入的数据量，只允许有必要的数据。
- 沙箱上传文件(将它们存储在不同的服务器上，只允许通过不同的子域访问文件，或者通过完全不同的域名访问文件更好)。

#### 表单验证

坚持进行表单的数据校验好处

- 我们希望以正确的格式获取到正确的数据 —— 如果我们的用户数据以不正确的格式存储，或者他们没有输入正确的信息/完全省略信息，我们的应用程序将无法正常运行。
- 我们希望保护我们的用户 ——强制用户输入安全的密码，有利于保护他们的账户信息。
- 我们希望保护我们自己 —— 恶意用户有很多通过滥用应用中缺乏保护的表单破坏应用的方法

**不同类型的表单数据校验：**

- 客户端校验发生在浏览器端，表单数据被提交到服务器之前，这种方式相较于服务器端校验来说，用户体验更好，它能实时的反馈用户的输入校验结果，这种类型的校验可以进一步细分成下面这些方式：
  - JavaScript 校验，这是可以完全自定义的实现方式；
  - HTML5 内置校验，这不需要 JavaScript ，而且性能更好，但是不能像 JavaScript 那样可自定义。
- 服务器端校验则是发生在浏览器提交数据并被服务器端程序接收之后 —— 通常服务器端校验都是发生在将数据写入数据库之前，如果数据没通过校验，则会直接从服务器端返回错误消息，并且告诉浏览器端发生错误的具体位置和原因，服务器端校验不像客户端校验那样有好的用户体验，因为它直到整个表单都提交后才能返回错误信息。

##### 使用内置表单数据校验

HTML5 一个特别有用的新功能就是，可以在不写一行脚本代码的情况下，即对用户的输入进行数据校验

当一个元素校验通过时：

- 该元素将可以通过 CSS 伪类 :valid 进行特殊的样式化；
- 如果用户尝试提交表单，如果没有其它的控制来阻止该操作（比如 JavaScript 即可阻止提交），那么该表单的数据会被提交。

如果一个元素未校验通过：

- 该元素将可以通过 CSS 伪类 :invalid 进行特殊的样式化；
- 如果用户尝试提交表单，浏览器会展示出错误消息，并停止表单的提交。

**required 属性：**

最简单的 HTML5 校验功能是 required 属性 — 输入成为必需

```html
<form>
  <label for="choose">Would you prefer a banana or cherry?</label>
  <input id="choose" name="i_like" required />
  <button>Submit</button>
</form>
```

**使用正则表达式校验：**

pattern 属性以正则表达式进行效验

```html
<form>
  <label for="choose">Would you prefer a banana or a cherry?</label>
  <input id="choose" name="i_like" required pattern="banana|cherry" />
  <button>Submit</button>
</form>
```

该 <input> 元素接受两个值中的一个: 字符串 "banana" 或者字符串"cherry".

**限制输入的长度：**

所有文本框 (`<input>` 或 `<textarea>`) 都可以使用 minlength 和 maxlength 属性来限制长度.  
在数字条目中 (i.e. `<input type="number">`), 该 min 和 max 属性同样提供校验约束

```html
<form>
  <div>
    <label for="choose">Would you prefer a banana or a cherry?</label>
    <input id="choose" name="i_like" required minlength="6" maxlength="6" />
  </div>
  <div>
    <label for="number">How many would you like?</label>
    <input type="number" id="number" name="amount" value="1" min="1" max="10" />
  </div>
  <div>
    <button>Submit</button>
  </div>
</form>
```

- 这里我们看到 text 条目的属性 minlength 和 maxlength 都为 6 — 这 banana 和 cherry 的长度都为 6. 输入少于这个长度的字符显示无效, 大多浏览器不能输入超过该限制的长度的字符.
- 我们同时也能让 number 条目数值限制在 min 为 1 和 一个 max 为 10 中 — 输入超出范围则显示无效, 并且您将无法使用递增/递减箭头将该值改变到此范围之外。

**自定义错误信息：**

这些自动生成的错误信息有两个缺点:

- 没有标准可以让 CSS 来改变他们的界面外观.
- 这依赖于他们使用的浏览器环境, 意味着你可能在这种语言的页面里得到另一种语言的错误提示.

HTML5 提供 [constraint validation API](http://www.w3.org/TR/html5/forms.html#the-constraint-validation-api) 来检测和自定义表单元素的状态.

#### 使用 JavaScript 校验表单

如果你想控制原生错误信息的界面外观，或者你想处理不支持 HTML 内置表单校验的浏览器，则必须使用 Javascript。

**约束校验的 API：**

可在特定的表单元素接口上调用：

- HTMLButtonElement
- HTMLFieldSetElement
- HTMLInputElement
- HTMLOutputElement
- HTMLSelectElement
- HTMLTextAreaElement

约束校验的 API 及属性

| 属性                     | 描述                                                                                                                                                |
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| validationMessage        | 一个本地化消息，描述元素不满足校验条件时（如果有的话）的文本信息。如果元素无需校验（willValidate 为 false），或元素的值满足校验条件时，为空字符串。 |
| validity                 | 一个 ValidityState 对象，描述元素的验证状态。详见有关可能的验证状态的文章。                                                                         |
| validity.customError     | 如果元素设置了自定义错误，返回 true ；否则返回 false。                                                                                              |
| validity.patternMismatch | 如果元素的值不匹配所设置的正则表达式，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                 |
| validity.rangeOverflow   | 如果元素的值高于所设置的最大值，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                       |
| validity.rangeUnderflow  | 如果元素的值低于所设置的最小值，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                       |
| validity.stepMismatch    | 如果元素的值不符合 step 属性的规则，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                   |
| validity.tooLong         | 如果元素的值超过所设置的最大长度，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                     |
| validity.typeMismatch    | 如果元素的值出现语法错误，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                             |
| validity.valid           | 如果元素的值不存在校验问题，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :valid CSS 伪类，否则命中 :invalid CSS 伪类。                 |
| validity.valueMissing    | 如果元素设置了 required 属性且值为空，返回 true，否则返回 false。当此属性为 true 时，元素将命中 :invalid CSS 伪类。                                 |
| willValidate             | 如果元素在表单提交时将被校验，返回 true，否则返回 false。                                                                                           |

约束校验 API 的方法

| 方法                             | 描述                                                                                                                                                                                                                      |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| checkValidity()                  | 如果元素的值不存在校验问题，返回 true，否则返回 false。如果元素校验失败，此方法会触发 invalid 事件。                                                                                                                      |
| HTMLFormElement.reportValidity() | 如果元素或它的子元素控件符合校验的限制，返回 true . 当返回为 false 时, 对每个无效元素可撤销 invalid 事件会被唤起并且校验错误会报告给用户 。                                                                               |
| setCustomValidity(message)       | 为元素添加一个自定义的错误消息；如果设置了自定义错误消息，该元素被认为是无效的，则显示指定的错误。这允许你使用 JavaScript 代码来建立校验失败，而不是用标准约束校验 API 所提供的。这些自定义信息将在向用户报告错误时显示。 |

如果参数为空，则清空自定义错误。

远程校验

当用户输入的数据与存储在应用程序服务器端的附加数据绑定时，这种校验是必要的。

执行这样的校验需要采取一些预防措施：

- 它要求公开 API 和一些数据；您需要确保它不是敏感数据。
- 网络滞后需要执行异步校验。这需要一些用户界面的工作，以确保如果校验没有适当的执行，用户不会被阻止。

#### [如何构建自定义表单挂件](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Forms/How_to_build_custom_form_widgets)

#### 使用 JavaScript 发送表单

**构建 XMLHttpRequest：**

```html
<button type="button" onclick="sendData({test:'ok'})">点击我！</button>
```

```javascript
function sendData(data) {
  var XHR = new XMLHttpRequest();
  var urlEncodedData = '';
  var urlEncodedDataPairs = [];
  var name;

  // 将数据对象转换为URL编码的键/值对数组。
  for (name in data) {
    urlEncodedDataPairs.push(
      encodeURIComponent(name) + '=' + encodeURIComponent(data[name])
    );
  }

  // 将配对合并为单个字符串，并将所有%编码的空格替换为
  // “+”字符；匹配浏览器表单提交的行为。
  urlEncodedData = urlEncodedDataPairs.join('&').replace(/%20/g, '+');

  // 定义成功数据提交时发生的情况
  XHR.addEventListener('load', function (event) {
    alert('耶! 已发送数据并加载响应。');
  });

  // 定义错误提示
  XHR.addEventListener('error', function (event) {
    alert('哎呀！出问题了。');
  });

  // 建立我们的请求
  XHR.open('POST', 'https://example.com/cors.php');

  // 为表单数据POST请求添加所需的HTTP头
  XHR.setRequestHeader('Content-Type', 'application/x-www-form-urlencoded');

  // 最后，发送我们的数据。
  XHR.send(urlEncodedData);
}
```

**使用 XMLHttpRequest 和 the FormData object（表单数据对象）：**

利用[FormData](https://developer.mozilla.org/zh-CN/docs/Web/API/FormData)对象来处理表单数据请求

```html
<button type="button" onclick="sendData({test:'ok'})">点我！</button>
```

```javascript
function sendData(data) {
  var XHR = new XMLHttpRequest();
  var FD = new FormData();

  // 把我们的数据添加到这个FormData对象中
  for (name in data) {
    FD.append(name, data[name]);
  }

  // 定义数据成功发送并返回后执行的操作
  XHR.addEventListener('load', function (event) {
    alert('Yeah! 已发送数据并加载响应。');
  });

  // 定义发生错误时执行的操作
  XHR.addEventListener('error', function (event) {
    alert('Oops! 出错了。');
  });

  // 设置请求地址和方法
  XHR.open('POST', 'https://example.com/cors.php');

  // 发送这个formData对象,HTTP请求头会自动设置
  XHR.send(FD);
}
```

使用绑定到表单元素上的 FormData 无需对表单值进行 append

```javascript
// 我们需要获取表单元素
var form = document.getElementById('myForm');
// 我们把这个 FormData 和表单元素绑定在一起。
var FD = new FormData(form);
```

##### 处理二进制数据

在 formData 的帮助下，发送二进制数据非常简单，使用 append() 方法就可以了。如果你必须手动进行，那确实会有一些棘手。

我们使用了 FileReader API 来访问二进制数据，然后手动构建多重表单数据请求：

```html
<form id="myForm">
  <p>
    <label for="i1">文本数据：</label>
    <input id="i1" name="myText" value="一些文本数据" />
  </p>
  <p>
    <label for="i2">文件数据：</label>
    <input id="i2" name="myFile" type="file" />
  </p>
  <button>提交！</button>
</form>
```

```javascript
window.addEventListener('load', function () {
  // 这些变量用于存储表单数据
  var text = document.getElementById('i1');
  var file = {
    dom: document.getElementById('i2'),
    binary: null,
  };

  // 使用 FileReader API 获取文件内容
  var reader = new FileReader();

  // 因为 FileReader 是异步的, 会在完成读取文件时存储结果
  reader.addEventListener('load', function () {
    file.binary = reader.result;
  });

  // 页面加载时, 如果一个文件已经被选择, 那么读取该文件.
  if (file.dom.files[0]) {
    reader.readAsBinaryString(file.dom.files[0]);
  }

  // 如果没有被选择，一旦用户选择了它，就读取文件。
  file.dom.addEventListener('change', function () {
    if (reader.readyState === FileReader.LOADING) {
      reader.abort();
    }

    reader.readAsBinaryString(file.dom.files[0]);
  });

  // 发送数据是我们需要的主要功能
  function sendData() {
    // 如果存在被选择的文件，等待它读取完成
    // 如果没有, 延迟函数的执行
    if (!file.binary && file.dom.files.length > 0) {
      setTimeout(sendData, 10);
      return;
    }

    // 要构建我们的多重表单数据请求,
    // 我们需要一个XMLHttpRequest 实例
    var XHR = new XMLHttpRequest();

    // 我们需要一个分隔符来定义请求的每一部分。
    var boundary = 'blob';

    // 将我们的主体请求存储于一个字符串中
    var data = '';

    // 所以，如果用户已经选择了一个文件
    if (file.dom.files[0]) {
      // 在请求体中开始新的一部分
      data += '--' + boundary + '\r\n';

      // 把它描述成表单数据
      data +=
        'content-disposition: form-data; ' +
        // 定义表单数据的名称
        'name="' +
        file.dom.name +
        '"; ' +
        // 提供文件的真实名字
        'filename="' +
        file.dom.files[0].name +
        '"\r\n';
      // 和文件的MIME类型
      data += 'Content-Type: ' + file.dom.files[0].type + '\r\n';

      // 元数据和数据之间有一条空行。
      data += '\r\n';

      // 将二进制数据添加到主体请求中
      data += file.binary + '\r\n';
    }

    // 文本数据更简单一些
    // 在主体请求中开始一个新的部分
    data += '--' + boundary + '\r\n';

    // 声明它是表单数据，并命名它
    data += 'content-disposition: form-data; name="' + text.name + '"\r\n';
    // 元数据和数据之间有一条空行。
    data += '\r\n';

    // 添加文本数据到主体请求中
    data += text.value + '\r\n';

    // 一旦完成，“关闭”主体请求
    data += '--' + boundary + '--';

    // 定义成功提交数据执行的语句
    XHR.addEventListener('load', function (event) {
      alert('✌！数据已发送且响应已加载。');
    });

    // 定义发生错误时做的事
    XHR.addEventListener('error', function (event) {
      alert('哎呀！出现了一些问题。');
    });

    // 建立请求
    XHR.open('POST', 'https://example.com/cors.php');

    // 添加需要的HTTP头部来处理多重表单数据POST请求
    XHR.setRequestHeader(
      'Content-Type',
      'multipart/form-data; boundary=' + boundary
    );

    // 最后，发送数据。
    XHR.send(data);
  }

  // 访问表单…
  var form = document.getElementById('myForm');

  // …接管提交事件
  form.addEventListener('submit', function (event) {
    event.preventDefault();
    sendData();
  });
});
```

#### 过时浏览器的 HTML 表单

优雅地降级(Graceful degradation)是 web 开发者最好的朋友。当你为现代浏览器构建内容时，你想确保它能在旧式浏览器中以某种方式工作，这就是优雅地降级。

**HTML input 类型：**

如果一个浏览器不能理解 `<input>`元素的 type 属性, 它将会后退到 text 一样的行为。

```html
<label for="myColor">
  Pick a color
  <input type="color" id="myColor" name="color" />
</label>
```

| Chrome 24                                                                           | Firefox 18                                                                         |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| ![颜色选择表单](https://developer.mozilla.org/files/4575/color-fallback-chrome.png) | ![输入框表单](https://developer.mozilla.org/files/4577/color-fallback-firefox.png) |

**CSS 属性选择器：**

CSS 属性选择器 在 HTML Forms 中十分有用，然而旧式浏览器不支持。

```html
<input type="number" class="number" />
```

```css
input[type='number'],
input.number {
  /* 在某些浏览器中，这可能会失败，因为如果他们不理解其中任何一个选择器，则跳过整个规则 */
}
```

**表单按钮：**

`<button>` 元素有两个问题令人困扰:

- 在某些旧版本的 IE 浏览器中有 bug。当用户点击按钮时，它不是发送 value 属性中的内容，而是发送 `<button>` 的开闭标签之间的 HTML 内容. 如果我们想发送值时，这是一个问题，例如发送的处理数据依赖于用户点击不同的按钮时.
- 一些旧浏览器不使用 submit 作为 type 属性的默认值, 所以建议总是在`<button>` 元素上设置设置 type 属性.

```html
<!-- 某些情形下，点击按钮将发送 "<em>Do A</em>" 而不是值"A" -->
<button type="submit" name="IWantTo" value="A">
  <em>Do A</em>
</button>
```

给予你的工程限制来选择上述任一种解决方案。

##### 功能检测和模拟(polyfills)

尽管 JavaScript 在现代浏览中是非常棒的技术，但在旧式浏览器中可能存在很多的问题。

**Modernizr 库：**

好的"polyfill"能通过提供缺少的 API 以提供帮助。  
最好的 polyfill 缺失 API 的方式是使用[Modernizr](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills) 库

```html
Modernizr.load({ // 这会测试您的浏览器是否支持HTML5表单验证API test :
Modernizr.formvalidation, // 如果浏览器不支持它，则会加载以下polyfill nope :
form-validation-API-polyfill.js, // 无论如何，你的核心App文件依赖于该API被加载
both : app.js, // 一旦加载了这两个文件，就会调用该函数来初始化应用程序 complete
: function () { app.init(); } });
```

**注意性能：**

尽管像 Modernizr 这样的脚本对性能非常敏感，但加载 200 千字节的 polyfill 仍然会影响程序的性能。这对旧式浏览器来说尤其重要，这些浏览器有处理速度非常慢的 JavaScript 引擎，让 polyfills 的执行对于用户来说变得很痛苦。有时，放弃某些功能会带来更好的用户体验，而不是在所有浏览器中具有完全相同的功能。

#### 样式化 HTML 表单

##### 基本样式美化

**Search 字段：**

搜索框是唯一一种应用 CSS 样式有点棘手的文本字段。  
在基于 WebKit 的浏览器（Chrome，Safari 等）上，您必须使用-webkit-appearance 专有属性来调整它。

```css
input[type='search'] {
  border: 1px dotted #999;
  border-radius: 0;

  -webkit-appearance: none;
}
```

![效果](https://developer.mozilla.org/files/4153/search-chrome-macos.png)

第一个没有使用-webkit-appearance 渲染，而第二个使用。

**字体和文本：**

一些组件不会从它们的父元素继承 font-family 和 font-size 。导致字体样式不一致，我们用以下样式来让组件字体样式保持一致。

```css
button,
input,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
}
```

**盒子模型：**

每个小部件都有自己的边框，填充和边距的规则。 所以如果你想给几个不同的小部件相同的大小，你必须使用 box-sizing 属性：

```css
input,
textarea,
select,
button {
  width: 150px;
  margin: 0;

  -webkit-box-sizing: border-box; /* For legacy WebKit based browsers */
  -moz-box-sizing: border-box; /* For legacy (Firefox <29) Gecko based browsers */
  box-sizing: border-box;
}
```

![效果图](https://developer.mozilla.org/files/4161/size-chrome-win7.png)

在上面的屏幕截图中，左侧的列没有 box-sizing，而右侧的列使用了这个属性和 border-box。

**定位（Positioning）：**

HTML 表单部件的定位通常不是问题; 但是，您应该特别注意两点：

- legend：
  由于`<legend>`元素对可访问性非常重要，因为它能被无障碍技术作为每个 fieldset 中的表单元素的标签读出来，它通常与标题配对，并且在无障碍中被隐藏 。
  ```html
  <fieldset>
    <legend>Hi!</legend>
    <h1>Hello</h1>
  </fieldset>
  ```
  ```css
  legend {
    width: 1px;
    height: 1px;
    overflow: hidden;
  }
  ```
- textarea：
  所有浏览器都认为`<textarea>` 元素是 inline block，与文本底线对齐。 这很少是我们真正想看到的。如果你想以 inline 方式使用它，通常改变垂直对齐方式：
  ```css
  textarea {
    vertical-align: top;
  }
  ```

#### [表单样式兼容表格](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Forms/Property_compatibility_table_for_form_widgets)

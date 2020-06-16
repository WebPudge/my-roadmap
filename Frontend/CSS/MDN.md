# MDN

- [MDN](#mdn)
  - [介绍](#介绍)
  - [知识点汇总](#知识点汇总)
    - [CSS 学习第一步](#css-学习第一步)
      - [CSS 什么是 CSS](#css-什么是-css)
        - [CSS 语法](#css-语法)
        - [CSS 模块](#css-模块)
        - [浏览器支持](#浏览器支持)
      - [CSS 的学习之旅](#css-的学习之旅)
        - [改变元素的默认行为](#改变元素的默认行为)
        - [使用类名](#使用类名)
        - [根据元素在文档中的位置确定样式](#根据元素在文档中的位置确定样式)
        - [根据状态确定样式](#根据状态确定样式)
        - [将选择子和关系选择器组合起来](#将选择子和关系选择器组合起来)
      - [如何构建 CSS](#如何构建-css)
        - [选择器](#选择器)
        - [属性和值](#属性和值)
        - [@规则](#规则)
        - [速记属性](#速记属性)
        - [注释](#注释)
        - [空白](#空白)
      - [CSS 如何运行](#css-如何运行)
        - [关于 DOM](#关于-dom)
        - [当浏览器遇到无法解析的 CSS 代码会发生什么](#当浏览器遇到无法解析的-css-代码会发生什么)
    - [CSS 构建](#css-构建)
      - [层叠与继承](#层叠与继承)
        - [冲突规则](#冲突规则)
        - [理解继承](#理解继承)
        - [理解层叠](#理解层叠)
        - [CSS 位置的影响](#css-位置的影响)
      - [CSS 选择器](#css-选择器)
        - [选择器列表](#选择器列表)
        - [选择器的种类](#选择器的种类)
      - [盒模型](#盒模型)
        - [块级盒子（Block box） 和 内联盒子（Inline box）](#块级盒子block-box-和-内联盒子inline-box)
        - [什么是 CSS 盒模型?](#什么是-css-盒模型)
        - [外边距，内边距，边框](#外边距内边距边框)
        - [盒子模型和内联盒子结合（行内块）](#盒子模型和内联盒子结合行内块)
      - [背景与边框](#背景与边框)
        - [CSS 的背景样式](#css-的背景样式)
        - [边框](#边框)
      - [处理不同方向的文本](#处理不同方向的文本)
        - [什么是书写模式](#什么是书写模式)
        - [书写模式、块级布局和内联布局](#书写模式块级布局和内联布局)
        - [逻辑属性和逻辑值](#逻辑属性和逻辑值)
        - [逻辑外边距、边框和内边距属性](#逻辑外边距边框和内边距属性)
      - [溢出的内容](#溢出的内容)
        - [溢出建立了块级格式化上下文(BFC)](#溢出建立了块级格式化上下文bfc)
      - [CSS 的值与单位](#css-的值与单位)
        - [数字，长度和百分比](#数字长度和百分比)
        - [颜色](#颜色)
        - [图片](#图片)
        - [位置](#位置)
        - [字符串和标识符](#字符串和标识符)
        - [函数](#函数)
      - [在 CSS 中调整大小](#在-css-中调整大小)
      - [图像、媒体和表单元素](#图像媒体和表单元素)
      - [组织 CSS](#组织-css)
        - [保持你的 CSS 整洁的技巧](#保持你的-css-整洁的技巧)
        - [CSS 方法论](#css-方法论)
        - [CSS 的构建体系](#css-的构建体系)
    - [文字样式](#文字样式)
      - [基本文本和字体样式](#基本文本和字体样式)
      - [列表样式](#列表样式)
        - [列表特定样式](#列表特定样式)
        - [管理列表计数](#管理列表计数)
      - [链接样式](#链接样式)
      - [Web 字体](#web-字体)
    - [CSS 排版](#css-排版)
      - [正常布局流](#正常布局流)
      - [弹性盒子](#弹性盒子)
        - [flex 模型说明](#flex-模型说明)
        - [flex 属性](#flex-属性)
      - [网格](#网格)
      - [浮动](#浮动)
      - [定位](#定位)
      - [多列布局](#多列布局)
      - [媒体查询](#媒体查询)

## 介绍

[MDN](https://developer.mozilla.org/zh-CN/docs/Learn/CSS) CSS 网站基础学习知识点总结

## 知识点汇总

### CSS 学习第一步

#### CSS 什么是 CSS

CSS 可以用于给文档添加样式 —— 比如改变标题和链接的颜色及大小或用于创建布局。甚至还可以用来做一些特效，比如动画。

##### CSS 语法

```css
h1 {
  color: red;
  font-size: 5em;
}
```

语法由一个选择器(selector)起头。上面选择(selects)了`<h1>` HTML 元素。  
接着输入一对大括号{ }。大括号内部定义一个或多个形式为 属性(property):值(value); 的样式声明(declarations)。每个声明都指定了我们所选择元素的样式属性。而冒号之后则是这个属性的值。

##### CSS 模块

CSS 由许多模块(modules) 构成。模块则是设置特定的一种种类的样式，如设置背景，背景就有许多属性。

**CSS 规范：**

所有的标准 Web 技术(HTML, CSS, JavaScript 等) 都被定义在一个巨大的文档中，称作 规范 specifications (或者简称为 "specs")，由 (像是 W3C, WHATWG, ECMA 或 Khronos) 这些规范化组织所发布的，其中还定义了各种技术是如何工作的。

##### 浏览器支持

当一个浏览器支持 CSS 后，我们就可以用它来进行 Web 开发了。让所有的浏览器都同时支持一个 CSS 新特性是不现实的，通常都会一个空档期 — 一些浏览器已经支持而另一些仍未支持。

#### CSS 的学习之旅

html 例子

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>开始学习CSS</title>
  </head>

  <body>
    <h1>我是一级标题</h1>

    <p>
      这是一个段落文本. 在文本中有一个 <span>span element</span> 并且还有一个
      <a href="http://example.com">链接</a>.
    </p>

    <p>这是第二段. 包含了一个 <em>强调</em> 元素.</p>

    <ul>
      <li>项目1</li>
      <li>项目2</li>
      <li>项目 <em>三</em></li>
    </ul>
  </body>
</html>
```

为了把 styles.css 和 index.html 联结起来，可以在 HTML 文档中，`<head>`语句模块里面加上下面的代码：

```html
<link rel="stylesheet" href="styles.css" />
```

##### 改变元素的默认行为

浏览器的默认样式有差异，并且如果对默认样式不满意可进行修改。  
例如：`<ul>` 下面样式移除了无需列表的开头符号。

```css
li {
  list-style-type: none;
}
```

##### 使用类名

我们可以通过 HTML 元素名的选择器来添加自己的样式，还可以用 class 类名选择器来选择

```html
<ul>
  <li>项目一</li>
  <li class="special">项目二</li>
  <li>项目 <em>三</em></li>
</ul>
```

要选中这个 special 类，只需在选择器的开头加个西文句点（.）。元素紧跟一个类选择器也会得到同样的效果

```css
/* 类选择器 class 为 special 的元素 */
.special {
  color: orange;
  font-weight: bold;
}

/* 选中每个 special class的 li 元素 */
li.special {
  color: orange;
  font-weight: bold;
}
```

##### 根据元素在文档中的位置确定样式

在上面的 html 例子文档中有两个 `<em>`元素 ——一个在段落内，另一个在列表项内。仅选择嵌套在`<li>` 元素内的`<em>`我们可以使用一个称为包含选择符的选择器，只需要一个空格即可。

```css
/* 选择 li 元素内 em 元素 */
li em {
  color: rebeccapurple;
}
```

还可以选择相临的元素，使用+号

```css
/* 选择 h1 同级临近的 p 元素 */
h1 + p {
  font-size: 200%;
}
```

##### 根据状态确定样式

以`<a>`标签为例，未访问的、访问过的、被鼠标悬停的、被键盘定位的，亦或是正在被点击当中的状态，这个标签有着不同的状态

```css
/* 没有被访问的链接颜色为粉色 */
a:link {
  color: pink;
}

/* 访问过的链接变为绿色 */
a:visited {
  color: green;
}

/* 被鼠标悬停的时候的样式，移除下划线 */
a:hover {
  text-decoration: none;
}
```

##### 将选择子和关系选择器组合起来

选择器间可以进行组合，选中特定的元素。

```css
/* <body>之内，紧接在<h1>后面的<p>元素的内部，类名为special。 */
body h1 + p .special {
  color: yellow;
  background-color: black;
  padding: 5px;
}
```

#### 如何构建 CSS

**外部样式表：**

外部样式表是指将 CSS 编写在扩展名为.css 的单独文件中，并从 HTML `<link>` 元素引用它

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
    <!-- 引入外部CSS -->
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
```

**内部样式表：**

内部样式表是指不使用外部 CSS 文件，而是将 CSS 放在 HTML 文件 `<style>` 标签之中。

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
```

**内联样式：**

内联样式表存在于 HTML 元素的 style 属性之中。其特点是每个 CSS 表只影响一个元素

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
  </head>
  <body>
    <h1 style="color: blue;background-color: yellow;border: 1px solid black;">
      Hello World!
    </h1>
    <p style="color:red;">This is my first CSS example</p>
  </body>
</html>
```

除非你有充足的理由，否则不要这样做！它难以维护

##### 选择器

每个 CSS 规则都以一个选择器或一组选择器为开始，去告诉浏览器这些规则应该应用到哪些元素上。

```css
/* 下面全部是css选择器 */
h1
a:link
.manythings
#onething
*
.box p
.box p:first-child
h1, h2, .intro
```

**专一性：**

两个选择器可以选择相同的 HTML 元素。下面将段落设置为蓝色的 p 选择器，还有一个将选定元素设置为红色的类。

```css
p {
  color: red;
}

p {
  color: blue;
}
```

CSS 语言有规则来控制在发生碰撞时哪条规则将获胜--这些规则称为级联规则和专用规则。上面的例子显示为蓝色，稍后的样式将覆盖以前的样式。

```css
/* class样式在p标签上 */
.special {
  color: red;
}

p {
  color: blue;
}
```

在我们使用类选择器和元素选择器的，类将获胜，使得段落变红--即使它出现在样式表的前面。选择器之间存在着一种权重关系。

##### 属性和值

- 属性：人类可读的标识符，指示您想要更改的样式特征(例如 font-size, width, background-color) 你想改变。
- 值：每个指定的属性都有一个值，该值指示您希望如何更改这些样式特性(例如，要将字体、宽度或背景色更改为。)  
  下面的图像突出显示单个属性和值。 属性名为 color, 值为 blue.

![css值与属性](https://mdn.mozillademos.org/files/16498/declaration.png)

与值配对的属性称为 CSS 声明。CSS 声明放在 CSS 声明块中。如下图：

![css声明](https://mdn.mozillademos.org/files/16499/declaration-block.png)

CSS 声明块与选择器配对，以生成 CSS 规则集(或 CSS 规则)。如下图：

![css规则集](https://mdn.mozillademos.org/files/16500/rules.png)

属性和值都是区分大小写的。每对中的属性和值由冒号(：)分隔。

**函数：**

虽然大多数值是相对简单的关键字或数值，但也有一些可能的值以函数的形式出现。如 calc()函数，这个函数允许您在 CSS 中进行简单的计算

```html
<div class="outer"><div class="box">The inner box is 90% - 30px.</div></div>
```

```css
.outer {
  border: 5px solid black;
}

.box {
  padding: 10px;
  width: calc(90% - 30px);
  background-color: rebeccapurple;
  color: white;
}
```

上面例子为我要求此框的宽度为包含块宽度的 90%，减去 30 像素。[calc()效果](https://codepen.io/pen/?&editable=true=https%3A%2F%2Fdeveloper.mozilla.org%2Fzh-CN%2Fdocs%2FLearn%2FCSS%2FFirst_steps%2FHow_CSS_is_structured)  
还有类似这样的其他函数如 rotate()等

##### @规则

有些@rules 规则很简单，有规则名和值。例如，要将额外的样式表导入主 CSS 样式表，可以使用@import:

```css
@import 'styles2.css';
```

最常见的 @rules 之一是@media，它允许您使用 媒体查询 来应用 CSS，仅当某些条件成立(例如，当屏幕分辨率高于某一数量，或屏幕宽度大于某一宽度时)。

```css
body {
  background-color: pink;
}
/* 视口大于30em的浏览器。如果浏览器的宽度大于30em，则背景色将为蓝色。 */
@media (min-width: 30em) {
  body {
    background-color: blue;
  }
}
```

##### 速记属性

一些属性，如 font, background, padding, border, and margin 等属性称为速记属性--这是因为它们允许您在一行中设置多个属性值，从而节省时间并使代码更整洁。

```css
/* In 4-value shorthands like padding and margin, the values are applied
   in the order top, right, bottom, left (clockwise from the top). There are also other 
   shorthand types, for example 2-value shorthands, which set padding/margin
   for top/bottom, then left/right */
padding: 10px 15px 15px 5px;
```

上下的例子他们是可以达到相同的效果

```css
padding-top: 10px;
padding-right: 15px;
padding-bottom: 15px;
padding-left: 5px;
```

##### 注释

注释可以帮助您在过了几个月后回来修改或优化代码时了解它们是如何工作的，同时也便于其他人理解您的代码。  
注释以`/*`开头，以`*/`结尾

```css
/*.special { 
  color: red; 
}*/

p {
  color: blue;
}
```

##### 空白

空白是指实际空格、制表符和新行。许多空白只是为了提高可读性。

```css
body {
  font: 1em/150% Helvetica, Arial, sans-serif;
  padding: 1em;
  margin: 0 auto;
  max-width: 33em;
}

@media (min-width: 70em) {
  body {
    font-size: 130%;
  }
}
```

```css
body {
  font: 1em/150% Helvetica, Arial, sans-serif;
  padding: 1em;
  margin: 0 auto;
  max-width: 33em;
}
@media (min-width: 70em) {
  body {
    font-size: 130%;
  }
}
```

#### CSS 如何运行

不同的浏览器在处理文件的时候会有不同的方式，但是下面的步骤基本都会出现。

- 浏览器载入 HTML 文件（比如从网络上获取）。
- 将 HTML 文件转化成一个 DOM（Document Object Model），DOM 是文件在计算机内存中的表现形式，下一节将更加详细的解释 DOM。
- 接下来，浏览器会拉取该 HTML 相关的大部分资源，比如嵌入到页面的图片、视频和 CSS 样式。JavaScript 则会稍后进行处理。
- 浏览器拉取到 CSS 之后会进行解析，根据选择器的不同类型（比如 element、class、id 等等）把他们分到不同的“桶”中。浏览器基于它找到的不同的选择器，将不同的规则（基于选择器的规则，如元素选择器、类选择器、id 选择器等）应用在对应的 DOM 的节点中，并添加节点依赖的样式（这个中间步骤称为渲染树）。
- 上述的规则应用于渲染树之后，渲染树会依照应该出现的结构进行布局。
- 网页展示在屏幕上（这一步被称为着色）。

![渲染过程](https://mdn.mozillademos.org/files/11781/rendering.svg)

##### 关于 DOM

一个 DOM 有一个树形结构，标记语言中的每一个元素、属性以及每一段文字都对应着结构树中的一个节点（Node/DOM 或 DOM node）。

```html
<p>
  Let's use:
  <span>Cascading</span>
  <span>Style</span>
  <span>Sheets</span>
</p>
```

上面的 HTML 片段转换为 DOM 会类似下方所示：

```
P
├─ "Let's use:"
├─ SPAN
|  └─ "Cascading"
├─ SPAN
|  └─ "Style"
└─ SPAN
   └─ "Sheets"
```

##### 当浏览器遇到无法解析的 CSS 代码会发生什么

浏览器遇到无法解析的 CSS 什么也不会做，继续解析下一个 CSS 样式！

代表着你使用最新的 CSS 优化的过程中浏览器遇到无法解析的规则也不会报错。

### CSS 构建

#### 层叠与继承

##### 冲突规则

**层叠：**

Stylesheets cascade（样式表层叠） — 简单的说，css 规则的顺序很重要；当应用两条同级别的规则到一个元素的时候，写在后面的就是实际使用的规则。

**优先级：**

- 一个元素选择器不是很具体 — 会选择页面上该类型的所有元素 — 所以它的优先级就会低一些。
- 一个类选择器稍微具体点 — 它会选择该页面中有特定 class 属性值的元素 — 所以它的优先级就要高一点。

**继承：**

继承也需要在上下文中去理解 —— 一些设置在父元素上的 css 属性是可以被子元素继承的，有些则不能。

##### 理解继承

继承就是父级的样式会传承给子级元素样式。  
像 widths , margins, padding, 和 borders 不会被继承。如果 borders 可以被继承，每个列表和列表项都会获得一个边框 — 可能就不是我们想要的结果!

**控制继承：**

CSS 为控制继承提供了四个特殊的通用属性值：

- inherit  
  设置该属性会使子元素属性和父元素相同。实际上，就是 "开启继承".
- initial  
  设置属性值和浏览器默认样式相同。如果浏览器默认样式中未设置且该属性是自然继承的，那么会设置为 inherit 。
- unset  
  将属性重置为自然值，也就是如果属性是自然继承那么就是 inherit，否则和 initial 一样
- revert  
  表示样式表中定义的元素属性的默认值。若用户定义样式表中显式设置，则按此设置；否则，按照浏览器定义样式表中的样式设置（只有很少的浏览器支持此属性）

**重设所有属性值：**

CSS 的 shorthand 属性 all 可以用于同时将这些继承值中的一个应用于（几乎）所有属性。它的值可以是其中任意一个(inherit, initial, unset, or revert)。

```css
.fix-this {
  all: unset;
}
```

##### 理解层叠

如果多个同一属性不同值设置一个元素，浏览器采用的样式会以如下优先级选择用哪个属性值。排前的优先级较高：

1. 重要程度
2. 优先级
3. 资源顺序

**资源顺序：**

如果你有超过一条规则，而且都是相同的权重，那么最后面的规则会应用。

**优先级：**

一个选择器的优先级可以说是由四个部分相加 (分量)，可以认为是个十百千 — 四位数的四个位数：

- 千位： 如果声明在 style 的属性（内联样式）则该位得一分。这样的声明没有选择器，所以它得分总是 1000。
- 百位： 选择器中包含 ID 选择器则该位得一分。
- 十位： 选择器中包含类选择器、属性选择器或者伪类则该位得一分。
- 个位：选择器中包含元素、伪元素选择器则该位得一分。

通用选择器 (\*)，组合符 (+, >, ~, ' ')，和否定伪类 (:not) 不会影响优先级。
下列为优先级例子：

| 选择器                                  | 千位 | 百位 | 十位 | 个位 | 优先级 |
| --------------------------------------- | ---- | ---- | ---- | ---- | ------ |
| h1                                      | 0    | 0    | 0    | 1    | 0001   |
| h1 + p::first-letter                    | 0    | 0    | 0    | 3    | 0003   |
| li > a[href*="en-US"] > .inline-warning | 0    | 0    | 2    | 2    | 0022   |
| #identifier                             | 0    | 1    | 0    | 0    | 0100   |
| 内联样式                                | 1    | 0    | 0    | 0    | 1000   |

数字越大的优先级越高

**!important**

有一个特殊的 CSS 可以用来覆盖所有上面所有优先级计算，不过需要很小心的使用 — !important。  
覆盖 !important 唯一的办法就是另一个 !important 具有 相同优先级 而且顺序靠后，或者更高优先级。  
了解 !important 是为了在阅读别人代码的时候知道有什么作用。 但是，强烈建议除了非常情况不要使用它。

##### CSS 位置的影响

相互冲突的声明将按以下顺序适用，后一种声明将覆盖前一种声明：

- 用户代理样式表中的声明(例如，浏览器的默认样式，在没有设置其他样式时使用)。
- 用户样式表中的常规声明(由用户设置的自定义样式)。
- 作者样式表中的常规声明(这些是我们 web 开发人员设置的样式)。
- 作者样式表中的!important 声明
- 用户样式表中的!important 声明

#### CSS 选择器

##### 选择器列表

如果你有多于一个使用相同 CSS 的物件，那么这些单独的选择器可以被混编为一个“选择器列表”

```css
/* 它们之间加上一个逗号，变为选择器列表。使用同一样式 */
h1,
.special {
  color: blue;
}
```

如果每个选择器都另起一行，会更好读些。

##### 选择器的种类

| 选择器                                                                                         | 示例              | 描述                                                         |
| ---------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------------ |
| [类型选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Type_selectors)                  | h1 { }            | 通过 node 节点名称匹配元素                                   |
| [通配选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Universal_selectors)             | \* { }            | 匹配任意类型的 HTML 元素                                     |
| [类选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Class_selectors)                   | .box { }          | 元素的类属性中的内容匹配元素                                 |
| [ID 选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/ID_selectors)                     | #unique { }       | 元素的 ID 属性内容匹配元素                                   |
| [标签属性选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Attribute_selectors)         | a[title] { }      | 已经存在的属性名或属性值匹配元素                             |
| [伪类选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Pseudo-classes)                  | p:first-child { } | 添加到选择器的关键字，指定要选择的元素的特殊状态             |
| [伪元素选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Pseudo-elements)               | p::first-line { } | 附加至选择器末的关键词，允许你对被选择元素的特定部分修改样式 |
| [后代选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Descendant_combinator)           | article p         | 选择祖先元素的所有后代匹配元素                               |
| [子代选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Child_combinator)                | article > p       | 父级元素的直接后代匹配元素(子元素)                           |
| [相邻兄弟选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Adjacent_sibling_combinator) | h1 + p            | 选择同级且紧跟其后的匹配元素                                 |
| [通用兄弟选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/General_sibling_combinator)  | h1 ~ p            | 选择同级在此元素后的匹配元素                                 |

#### 盒模型

##### 块级盒子（Block box） 和 内联盒子（Inline box）

块级的（block）盒子会表现出以下行为:

- 盒子会在内联的方向上扩展并占据父容器在该方向上的所有可用空间，在绝大数情况下意味着盒子会和父容器一样宽
  每个盒子都会换行
- width 和 height 属性可以发挥作用
- 内边距（padding）, 外边距（margin） 和 边框（border） 会将其他元素从当前盒子周围“推开”

内联（inline）盒子表现如下:

- 盒子不会产生换行。
- width 和 height 属性将不起作用。
- 内边距、外边距以及边框会被应用但是不会把其他处于 inline 状态的盒子推开。

内部和外部显示类型

- css 的 box 模型有一个外部显示类型，来决定盒子是块级还是内联。
- 同样盒模型还有内部显示类型，它决定了盒子内部元素是如何布局的。

列如：flex 布局 display: flex 外部显示块级盒子内部为 flex 盒子

##### 什么是 CSS 盒模型?

**盒模型的各个部分：**

- Content box: 这个区域是用来显示内容，大小可以通过设置 width 和 height.
- Padding box: 包围在内容区域外部的空白区域； 大小通过 padding 相关属性设置。
- Border box: 边框盒包裹内容和内边距。大小通过 border 相关属性设置。
- Margin box: 这是最外面的区域，是盒子和其他元素之间的空白区域。大小通过 margin 相关属性设置。

如图：

![盒子模型](https://mdn.mozillademos.org/files/16558/box-model.png)

**标准盒模型：**

设置 width 和 height，实际设置的是 content box。 padding 和 border 再加上设置的宽高一起决定整个盒子的大小。

![标准盒模型](https://mdn.mozillademos.org/files/16559/standard-box-model.png)

**替代（IE）盒模型：**

设置 width 和 height，实际是 padding border 和 content box 一起的大小。

![替代（IE）盒模型](https://mdn.mozillademos.org/files/16557/alternate-box-model.png)

设置 box-sizing 属性来实现两个盒子的转换属性值

- border-box 替代（IE）盒模型
- content-box 标准盒模型
- inherit 继承

##### 外边距，内边距，边框

**外边距：**

除了 margin 属性一次控制一个元素的所有边距，还有如下：

- margin-top
- margin-right
- margin-bottom
- margin-left

外边距折叠

有上外边距和下外边距的两个元素，这些外边距将合并为一个外边距，即最大的单个外边距的大小。

**边框：**

可以使用 border 属性一次设置所有四个边框的宽度、颜色和样式。

设置每边的宽度、颜色和样式，可以使用：

- border-top
- border-right
- border-bottom
- border-left

所有边的颜色、样式或宽度，请使用以下属性：

- border-width
- border-style
- border-color

设置单边的颜色、样式或宽度，可以使用最细粒度的普通属性之一：

- border-top-width
- border-top-style
- border-top-color
- border-right-width
- border-right-style
- border-right-color
- border-bottom-width
- border-bottom-style
- border-bottom-color
- border-left-width
- border-left-style
- border-left-color

**内边距：**

使用 padding 简写属性控制元素所有边，或者每边单独使用等价的普通属性：

- padding-top
- padding-right
- padding-bottom
- padding-left

##### 盒子模型和内联盒子结合（行内块）

使用 display: inline-block，实现我们需要的块级的部分效果：

- 设置 width 和 height 属性会生效。
- padding, margin, 以及 border 会推开其他元素。
- 元素不会跳转到新行

#### 背景与边框

##### CSS 的背景样式

**背景颜色：**

background-color 属性定义了 CSS 中任何元素的背景颜色。

```css
.box {
  background-color: #567895;
}

h2 {
  background-color: black;
  color: white;
}
span {
  background-color: rgba(255, 255, 255, 0.5);
}
```

[color 值详情](https://wiki.developer.mozilla.org/zh-CN/docs/Web/CSS/color_value)

**背景图片：**

background-image 属性允许在元素的背景中显示图像。

```css
.a {
  background-image: url('balloons.jpg');
}

.b {
  background-image: linear-gradient(
      rgba(0, 0, 255, 0.5),
      rgba(255, 255, 0, 0.5)
    ), url('star.png');
}
```

[image 值详情](https://developer.mozilla.org/zh-CN/docs/Web/CSS/image)

控制背景平铺

background-repeat 属性用于控制图像平铺。可用的值是:

- no-repeat — 不重复。
- repeat-x —水平重复。
- repeat-y —垂直重复。
- repeat — 在两个方向重复。

```css
.box {
  background-image: url(star.png);
  background-repeat: repeat-x;
}
```

调整背景图像的大小

使用 background-size 属性，来调整图像的大小以适应背景。

- width height 设置长度或百分比值设置图片大小
- cover —浏览器将使图像足够大，使它完全覆盖了盒子区，同时仍然保持其高宽比。在这种情况下，有些图像可能会跳出盒子外
- contain — 浏览器将使图像的大小适合盒子内。在这种情况下，如果图像的长宽比与盒子的长宽比不同，则可能在图像的任何一边或顶部和底部出现间隙。

```css
.box {
  width: 100px;
  background-image: url(balloons.jpg);
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
```

背景图像定位

background-position 属性允许您选择背景图像显示在其应用到的盒子中的位置。它使用的坐标系中，框的左上角是(0,0)，框沿着水平(x)和垂直(y)轴定位。

```css
.box {
  background-image: url(star.png);
  background-repeat: no-repeat;
  background-position: top center;
}
.box {
  background-image: url(star.png);
  background-repeat: no-repeat;
  background-position: 20px 10%;
}
/* 4值的position */
.box {
  background-image: url(star.png);
  background-repeat: no-repeat;
  background-position: top 20px right 10px;
}
```

[定位值详情](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-position)

**渐变背景：**

渐变——当它用于背景时——就像图像一样，也可以使用 background-image 属性设置。

```css
.a {
  background-image: linear-gradient(
    105deg,
    rgba(0, 249, 255, 1) 39%,
    rgba(51, 56, 57, 1) 96%
  );
}

.b {
  background-image: radial-gradient(
    circle,
    rgba(0, 249, 255, 1) 39%,
    rgba(51, 56, 57, 1) 96%
  );
  background-size: 100px 50px;
}
```

[渐变值详情](https://developer.mozilla.org/zh-CN/docs/Web/CSS/gradient)

**多个背景图像：**

也可以有多个背景图像—在单个属性值中指定多个 background-image 值，用逗号分隔每个值。  
其他 background-\*属性也可以有值逗号分隔的方式相同的 background-image：

```css
.test {
  background-image: url(image1.png), url(image2.png), url(image3.png),
    url(image1.png);
  background-repeat: no-repeat, repeat-x, repeat;
  background-position: 10px 20px, top right;
}
```

**背景附加：**

background-attachment 属性控制背景是指定他们如何滚动时，，内容滚动。它可以接受以下值:

- scroll: 使元素的背景在页面滚动时滚动。如果滚动了元素内容，则背景不会移动。实际上，背景被固定在页面的相同位置，所以它会随着页面的滚动而滚动。
- fixed: 使元素的背景固定在视图端口上，这样当页面或元素内容滚动时，它就不会滚动。它将始终保持在屏幕上相同的位置。
- local: 这个值是后来添加的(它只在 Internet Explorer 9+中受支持，而其他的在 IE4+中受支持)，因为滚动值相当混乱，在很多情况下并不能真正实现您想要的功能。局部值将背景固定在设置的元素上，因此当您滚动元素时，背景也随之滚动。
  [演示](http://mdn.github.io/learning-area/css/styling-boxes/backgrounds/background-attachment.html)

**使用 background 的简写：**

简写允许您一次设置所有不同的属性。

```css
/* 使用 <background-color> */
background: green;

/* 使用 <bg-image> 和 <repeat-style> */
background: url('test.jpg') repeat-y;

/* 使用 <box> 和 <background-color> */
background: border-box red;

/* 将背景设为一张居中放大的图片 */
background: no-repeat center/80% url('../img/image.png');
```

- 在每一层中，下列的值可以出现 0 次或 1 次：
  `<attachment>`
  `<bg-image>`
  `<position>`
  `<bg-size>`
  `<repeat-style>`
- `<bg-size>` 只能紧接着 `<position>` 出现，以"/"分割，如： "center/80%".
- `<box>` 可能出现 0 次、1 次或 2 次。如果出现 1 次，它同时设定 [background-origin](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-origin) 和 [background-clip](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-clip)。如果出现 2 次，第一次的出现设置 background-origin，第二次的出现设置 background-clip。
- `<background-color>` 只能被包含在最后一层。

[background 缩写详情](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background)

##### 边框

使用 border 为一个框的所有四个边设置边框。

```css
/* 设置所有边框 */
.box {
  border: 1px solid black;
}
/* 与上面等价 */
.box {
  border-width: 1px;
  border-style: solid;
  border-color: black;
}

/* 设置一边 */
.box {
  border-top: 1px solid black;
}
/* 与上面等价 */
.box {
  border-top-width: 1px;
  border-top-style: solid;
  border-top-color: black;
}
```

**圆角：**

使用 border-radius 属性和与方框的每个角相关的长边来实现方框的圆角。

```css
/* 使一个盒子的四个角都有10px的圆角半径 */
.box {
  border-radius: 10px;
}
/* 使右上角的水平半径为1em，垂直半径为10％ */
.box {
  border-top-right-radius: 1em 10%;
}
```

#### 处理不同方向的文本

##### 什么是书写模式

CSS 中的书写模式是指文本的排列方向是横向还是纵向的。使用 writing-mode。writing-mode 的三个值分别是：

- horizontal-tb: 块流向从上至下。对应的文本方向是横向的。
- vertical-rl: 块流向从右向左。对应的文本方向是纵向的。
- vertical-lr: 块流向从左向右。对应的文本方向是纵向的。

##### 书写模式、块级布局和内联布局

当我们切换书写模式时，我们也在改变块和内联文本的方向。horizontal-tb 书写模式下块的方向是从上到下的横向的，而 vertical-rl 书写模式下块的方向是从右到左的纵向的。因此，块维度指的总是块在页面书写模式下的显示方向。而内联维度指的总是文本方向。

水平书写模式下的两种维度：

![水平书写模式](https://mdn.mozillademos.org/files/17148/horizontal-tb-zh.png)

纵向书写模式下的两种维度：

![纵向书写模式](https://mdn.mozillademos.org/files/17149/vertical-zh.png)

##### 逻辑属性和逻辑值

想要宽和高随着书写模式一起变化，设置水平模式宽又需要映射竖直模式的高，这就需要逻辑（logical）和相对变化（flow relative）代替了像宽 width 和高 height 一样的物理属性。

- 映射 width 的属性被称作内联尺寸（inline-size）——内联维度的尺寸。
- 映射 height 的属性被称为块级尺寸（block-size）

```css
.box {
  inline-size: 150px; /* width */
  block-size: 300px; /* height */
}
```

变换书写模式就会看起来像旋转了一样。

##### 逻辑外边距、边框和内边距属性

margin、padding、border 均有逻辑属性，这些属性是在方向上都进行定义：

- _-top 等同于 _-block-start
- _-bottom 等同于 _-block-end
- _-left 等同于 _-inline-start
- _-right 等同于 _-inline-start

**逻辑值：**

有一些属性的取值是一些物理值（如 top、right、bottom 和 left）。这些值同样拥有逻辑值映射（block-start、inline-end、block-end 和 inline-start）。

#### 溢出的内容

CSS 中万物皆盒，溢出是在你往盒子里面塞太多东西的时候发生的，所以盒子里面的东西也不会老老实实待着。

overflow 属性控制一个元素溢出的方式，有如下几个值

- `visible` 默认值，会出现溢出的现象。
- `hidden` 隐藏掉溢出，使溢出部分看不到。
- `scroll` 盒子总是有滚动条，不管溢出还是不溢出。
- `auto` 内容溢出时有滚动条，不溢出时无滚动条。

还可以控制两种方向的滚动条：

- overflow-x 仅在 x 轴方向滚动。
- overflow-y 仅在 y 轴方向滚动。

##### 溢出建立了块级格式化上下文(BFC)

BFC 是块盒子的布局过程产生的区域，也是浮动元素与其他元素交互的区域。

下列会创建块级格式化上下文：

- 根元素(`<html>`)
- 浮动元素（元素的 float 不是 none）
- 绝对定位元素（元素的 position 为 absolute 或 - fixed）
- 行内块元素（元素的 display 为 inline-block）
- 表格单元格（元素的 display 为 table-cell，HTML 表格- 单元格默认为该值）
- 表格标题（元素的 display 为 table-caption，HTML 表格标题默认为该值）
- 匿名表格单元格元素（元素的 display 为 table、- table-row、 table-row-group、- table-header-group、table-footer-group（分别是 HTML table、row、tbody、thead、tfoot 的默认属性） 或 inline-table）
- overflow 值不为 visible 的块元素
- display 值为 flow-root 的元素
- contain 值为 layout、content 或 paint 的元素
- 弹性元素（display 为 flex 或 inline-flex 元素的直接子元素）
- 网格元素（display 为 grid 或 inline-grid 元素的直接子元素）
- 多列容器（元素的 column-count 或 column-width 不- 为 auto，包括 column-count 为 1）
- column-span 为 all 的元素始终会创建一个新的 BFC，即- 使该元素没有包裹在一个多列容器中（标准变更，Chrome bug）。

#### CSS 的值与单位

##### 数字，长度和百分比

**长度：**

绝对长度单位

| 单位 | 名称         | 等价换算            |
| ---- | ------------ | ------------------- |
| cm   | 厘米         | 1cm = 96px/2.54     |
| mm   | 毫米         | 1mm = 1/10th of 1cm |
| Q    | 四分之一毫米 | 1Q = 1/40th of 1cm  |
| in   | 英寸         | 1in = 2.54cm = 96px |
| pc   | 十二点活字   | 1pc = 1/16th of 1in |
| pt   | 点           | 1pt = 1/72th of 1in |
| px   | 像素         | 1px = 1/96th of 1in |

这些值中的大多数在用于打印时比用于屏幕输出时更有用。例如，我们通常不会在屏幕上使用 cm。惟一一个您经常使用的值，估计就是 px(像素)。

相对长度单位

| 单位 | 相对于                                                                                        |
| ---- | --------------------------------------------------------------------------------------------- |
| em   | 在 font-size 中使用是相对于父元素的字体大小，在其他属性中使用是相对于自身的字体大小，如 width |
| ex   | 字符“x”的高度                                                                                 |
| ch   | 数字“0”的宽度                                                                                 |
| rem  | 根元素的字体大小                                                                              |
| lh   | 元素的 line-height                                                                            |
| vw   | 视窗宽度的 1%                                                                                 |
| vh   | 视窗高度的 1%                                                                                 |
| vmin | 视窗较小尺寸的 1%                                                                             |
| vmax | 视图大尺寸的 1%                                                                               |

**百分比：**

- 将元素的字体大小设置为百分比，那么它将是元素父元素字体大小的百分比。
- 使用百分比作为宽度值，那么它将是父值宽度的百分比

**数字：**

有些值接受数字，不添加任何单位。接受无单位数字的属性的一个例子是不透明度属性（opacity ）

##### 颜色

**十六进制 RGB 值：**

每个十六进制值由一个散列/磅符号(#)和六个十六进制数字组成，每个十六进制数字都可以取 0 到 f(代表 15)之间的 16 个值中的一个——所以是 0123456789abcdef。每对值表示一个通道—红色、绿色和蓝色—并允许我们为每个通道指定 256 个可用值中的任意一个(16 x 16 = 256)。

**RGB 和 RGBA 的值：**

使用 RGBA 颜色——它们的工作方式与 RGB 颜色完全相同，因此您可以使用任何 RGB 值，但是有第四个值表示颜色的 alpha 通道，它控制不透明度。

**HSL 和 HSLA 的值：**

- 色调： 颜色的底色。这个值在 0 和 360 之间，表示色轮周围的角度。
- 饱和度： 颜色有多饱和？ 它的值为 0 - 100%，其中 0 为无颜色(它将显示为灰色阴影)，100%为全色饱和度
- 亮度：颜色有多亮？ 它从 0 - 100%中获取一个值，其中 0 表示没有光(它将完全显示为黑色)，100%表示完全亮(它将完全显示为白色)

HSL 也有 alpha 通道，它控制不透明度。

##### 图片

通过 url()函数指向的实际图像文件，也可以是一个渐变。

##### 位置

position 数据类型表示一组 2D 坐标，用于定位一个元素，关键字(如 top, left, bottom, right, 以及 center )将元素与 2D 框的特定边界对齐，以及表示框的顶部和左侧边缘偏移量的长度。

##### 字符串和标识符

关键字被用作值的地方(例如 color 关键字，如 red, black, rebeccapurple, and goldenrod)

##### 函数

最后一种类型的值是一组称为函数的值。rgb()、hsl()等。

#### 在 CSS 中调整大小

**把百分数作为内外边距：**

百分数设定内外边距的时候，值是以内联尺寸进行计算的。

**min-和 max-尺寸：**

可以让 CSS 给定一个元素的最大或最小尺寸。这在避免溢出的同时并处理变化容量的内容的时候是很有用的。

**视口单位：**

视口宽度的 vw 单位，以及意为视口高度的 vh 单位。使用这些单位，你可以把一些东西做得随用户的视口改变大小。

#### 图像、媒体和表单元素

**替换元素：**

图像和视频被描述为替换元素。 这意味着 CSS 不能影响这些元素的内部布局-仅影响它们在页面上于其他元素中的位置。

**调整图像大小：**

当替换元素适配大小时可使用 max-width 等调整大小属性设置，也可以使用 object-fit 时，替换元素可以以多种方式被调整到合乎盒子的大小。

object-fit 取值如下：

- contain  
  被替换的内容将被缩放，以在填充元素的内容框时保持其宽高比。 整个对象在填充盒子的同时保留其长宽比，因此如果宽高比与框的宽高比不匹配，该对象将被添加“[黑边](https://zh.wikipedia.org/wiki/%E9%BB%91%E9%82%8A)”。
- cover  
  被替换的内容在保持其宽高比的同时填充元素的整个内容框。如果对象的宽高比与内容框不相匹配，该对象将被剪裁以适应内容框。
- fill  
  被替换的内容正好填充元素的内容框。整个对象将完全填充此框。如果对象的宽高比与内容框不相匹配，那么该对象将被拉伸以适应内容框。
- none  
  被替换的内容将保持其原有的尺寸。
- scale-down  
  内容的尺寸与 none 或 contain 中的一个相同，取决于它们两个之间谁得到的对象尺寸会更小一些。

**布局中的替换元素：**

在一个 flex 或者 grid 布局中，元素默认会把拉伸到充满整块区域。图像不会拉伸，而是会被对齐到网格区域或者弹性容器的起始处。替换元素在成为网格或者弹性布局的一部分时，有不同的默认行为。有可能需要设置元素进行拉伸。

```css
/* 拉伸元素，object-fit在不居中会不生效 */
img {
  width: 100%;
  height: 100%;
}
```

**form 元素：**

继承和表单元素

一些浏览器中，表单元素默认不会继承字体样式。
需要向你的 CSS 中加入这条规则。

```css
button,
input,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
}
```

form 元素与 box-sizing

跨浏览器的 form 元素对于不同的挂件使用不同的盒子约束规则。确保在给 form 元素设定宽度和高度时可以有统一的体验。

```css
button,
input,
select,
textarea {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
```

其他有用的设置

在`<textarea>`上设置 overflow: auto 以避免 IE 在不需要滚动条的时候显示滚动条：

```css
textarea {
  overflow: auto;
}
```

将一切都放在一起“重置”

我们可以将上面讨论过的各式属性包起来，成为以下的“表单重置”，以提供一个统一的在其上继续进行工作的地基。

```css
button,
input,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

textarea {
  overflow: auto;
}
```

#### 组织 CSS

##### 保持你的 CSS 整洁的技巧

- 将 CSS 格式化成可读的形式。CSS 不会管你使用哪种方式来进行格式化，我们自己的看法是，将每个属性值对放在新的一行会更好读。
- 为你的 CSS 加注释。帮任何未来的开发者处理你的 CSS 文件。
- 在你的样式表里面加入逻辑段落。提供全局的格式化样式、工具类样式等。
- 避免太特定的选择器。如果你创建了很特定的选择器，你经常会发现，你需要在你的 CSS 中复用一块代码，以将同样的规则应用到其他元素上。需要减少这样的选择器
- 将大样式表分成几个小的样式表。可以将一个页面连接到多个样式表，层叠的一般规则会在这里生效，即连接的靠前的样式表里面的规则会比后面的有更高优先级。

##### CSS 方法论

**OOCSS：**

OOCSS 的基本理念是将你的 CSS 分解成可复用的对象，于是你可以在你的站点上任何需要的地方使用。  
例如创建一个叫做 comment 的类，用于组件部分的一组规则，然后是叫做 list-item 的类，除了一些细小的区别外，它几乎和 comment 类完全相同。  
无 OO 写法：

```css
.comment {
  display: grid;
  grid-template-columns: 1fr 3fr;
}

.comment img {
  border: 1px solid grey;
}

.comment .content {
  font-size: 0.8rem;
}

.list-item {
  display: grid;
  grid-template-columns: 1fr 3fr;
  border-bottom: 1px solid grey;
}

.list-item .content {
  font-size: 0.8rem;
}
```

在 OOCSS 中，你可以建立一个叫作 media 的排布，里面包含所有的两种排布所共有的 CSS——一个大致用于媒体对象的形状之类的基础类。然后我们再额外加入一个类，处理那些微小的区别，这样特定地扩展基础样式。

```css
.media {
  display: grid;
  grid-template-columns: 1fr 3fr;
}

.media .content {
  font-size: 0.8rem;
}

.comment img {
  border: 1px solid grey;
}

.list-item {
  border-bottom: 1px solid grey;
}
```

```html
<!-- 评论需要同时应用media和comment类 -->
<div class="media comment">
  <img />
  <div class="content"></div>
</div>

<!-- 列表项应用了media和list-item -->
<ul>
  <li class="media list-item">
    <img />
    <div class="content"></div>
  </li>
</ul>
```

**BEM：**

BEM 即为块级元素修饰字符（Block Element Modifier）。在 BEM 中，一个块，例如一个按钮、菜单或者标志，就是独立的实体。一个元素就像一个列表项或者标题一样，被绑定到它所在的块。修饰字符是标记到一个块或者元素的标识，能够改变样式或者行为。[BEM 命名常规](http://getbem.com/naming/)，阅读[BEM 101](https://css-tricks.com/bem-101/) 中关于 CSS Tricks 的段落以了解更多和这个系统相关的信息。

**其他常见体系：**

- Jonathan Snook 创造的[Scalable and Modular Architecture for CSS (SMACSS)](http://smacss.com/)
- Harry Roberts 的[ITCSS](https://itcss.io/)
- Yahoo!创造的[Atomic CSS (ACSS)](https://acss.io/)。

使用这样的体系的缺点是，它们会看起来过于复杂，尤其是对于小项目。

##### CSS 的构建体系

另一种组织 CSS 的方法是利用一些对于前端开发者可用的工具，它们让你可以稍微更程式化地编写 CSS。有很多工具，我们将它们分成预处理工具和后处理工具。

最为流行的预处理工具是[Sass](https://sass-lang.com/)，

后处理以进行优化  
如果你对加入例如许多额外的注释和空格，增大你的样式表大小有所关心的话，那么后处理会通过在生产版本中略去任何不必要的东西的方式，优化 CSS。

### 文字样式

#### 基本文本和字体样式

- 字体样式: 作用于字体的属性，会直接应用到文本中，比如使用哪种字体，字体的大小是怎样的，字体是粗体还是斜体，等等。
- 文本布局风格: 作用于文本的间距以及其他布局功能的属性，比如，允许操纵行与字之间的空间，以及在内容框中，文本如何对齐。

**字体：**

- 字体颜色 color 属性。
- 字体种类 font-family 属性。
  - 有某几个字体通常可以应用到所有系统，因此可以毫无顾忌地使用。这些都是所谓的 网页安全字体。
  - 默认字体。CSS 定义了 5 个常用的字体名称: serif, sans-serif, monospace, cursive,和 fantasy. 这些都是非常通用的，当使用这些通用名称时，使用的字体完全取决于每个浏览器，而且它们所运行的每个操作系统也会有所不同。
  - 字体栈。font-family 属性，其值由几个用逗号分离的字体名称组成。浏览器从列表的第一个开始，然后查看在当前机器中，这个字体是否可用。如果可用，就把这个字体应用到选中的元素中。如果不可用，它就移到列表中的下一个字体，然后再检查。
- 字体大小 font-size 属性。
  - px (像素): 将像素的值赋予给你的文本。这是一个绝对单位， 它导致了在任何情况下，页面上的文本所计算出来的像素值都是一样的。
  - em: 1em 等于我们设计的当前元素的父元素上设置的字体大小 (更加具体的话，比如包含在父元素中的大写字母 M 的宽度) 如果你有大量设置了不同字体大小的嵌套元素，这可能会变得棘手, 但它是可行的，如下图所示。为什么要使用这个麻烦的单位呢? 当你习惯这样做时，那么就会变得很自然，你可以使用 em 调整任何东西的大小，不只是文本。你可以有一个单位全部都使用 em 的网站，这样维护起来会很简单。
  - rem: 这个单位的效果和 em 差不多，除了 1rem 等于 HTML 中的根元素的字体大小， (i.e. `<html>`) ，而不是父元素。这可以让你更容易计算字体大小，但是遗憾的是， rem 不支持 Internet Explorer 8 和以下的版本。如果你的项目需要支持较老的浏览器，你可以坚持使用 em 或 px, 或者是 polyfill 就像 REM-unit-polyfill. （这个单位在“CSS 的值和单位”一节也有讲解）

字体样式，字体粗细，文本转换和文本装饰

- font-style: 用来打开和关闭文本 italic (斜体)。 可能的值如下 (你很少会用到这个属性，除非你因为一些理由想将斜体文字关闭斜体状态)：
  - normal: 将文本设置为普通字体 (将存在的斜体关闭)
  - italic: 如果当前字体的斜体版本可用，那么文本设置为斜体版本；如果不可用，那么会利用 oblique 状态来模拟 italics。
  - oblique: 将文本设置为斜体字体的模拟版本，也就是将普通文本倾斜的样式应用到文本中。
- font-weight: 设置文字的粗体大小。这里有很多值可选 (比如 -light, -normal, -bold, -extrabold, -black, 等等), 不过事实上你很少会用到 normal 和 bold 以外的值：
  - normal, bold: 普通或者加粗的字体粗细
  - lighter, bolder: 将当前元素的粗体设置为比其父元素粗体更细或更粗一步。100–900: 数值粗体值，如果需要，可提供比上述关键字更精细的粒度控制。
  - text-transform: 允许你设置要转换的字体。值包括：
  - none: 防止任何转型。
  - uppercase: 将所有文本转为大写。
  - lowercase: 将所有文本转为小写。
  - capitalize: 转换所有单词让其首字母大写。
  - full-width: 将所有字形转换成全角，即固定宽度的正方形，类似于等宽字体，允许拉丁字符和亚洲语言字形（如中文，日文，韩文）对齐。
- text-decoration: 设置/取消字体上的文本装饰 (你将主要使用此方法在设置链接时取消设置链接上的默认下划线。) 可用值为：
  - none: 取消已经存在的任何文本装饰。
  - underline: 文本下划线.
  - overline: 文本上划线
  - line-through: 穿过文本的线 strikethrough over the text。

文字阴影

使用 text-shadow 属性。这最多需要 4 个值。

4 个属性如下:

- 阴影与原始文本的水平偏移，可以使用大多数的 CSS 单位 length and size units, 但是 px 是比较合适的。这个值必须指定。
- 阴影与原始文本的垂直偏移;效果基本上就像水平偏移，除了它向上/向下移动阴影，而不是左/右。这个值必须指定。
- 模糊半径 - 更高的值意味着阴影分散得更广泛。如果不包含此值，则默认为 0，这意味着没有模糊。可以使用大多数的 CSS 单位 length and size units.
- 阴影的基础颜色，可以使用大多数的 CSS 颜色单位 CSS color unit. 如果没有指定，默认为 black.

多种阴影，通过包含以逗号分隔的多个阴影值，将多个阴影应用于同一文本

```css
text-shadow: -1px -1px 1px #aaa, 0px 4px 1px rgba(0, 0, 0, 0.5),
  4px 4px 5px rgba(0, 0, 0, 0.7), 0px 0px 7px rgba(0, 0, 0, 0.4);
```

**文本布局：**

文本对齐

text-align 属性用来控制文本如何和它所在的内容盒子对齐。

- left: 左对齐文本。
- right: 右对齐文本。
- center: 居中文字。
- justify: 使文本展开，改变单词之间的差距，使所有文本行的宽度相同。你需要仔细使用，它可以看起来很可怕。特别是当应用于其中有很多长单词的段落时。如果你要使用这个，你也应该考虑一起使用别的东西，比如 hyphens，打破一些更长的词语。

行高

line-height 属性设置文本每行之间的高。接受大多数单位 [数字、长度、百分比](#css-%e7%9a%84%e5%80%bc%e4%b8%8e%e5%8d%95%e4%bd%8d)。无单位的数字使用在行高上表示倍数关系。

字母和单词间距

letter-spacing 和 word-spacing 属性允许你设置你的文本中的字母与字母之间的间距、或是单词与单词之间的间距。接受大多数单位 [数字、长度、百分比](#css-%e7%9a%84%e5%80%bc%e4%b8%8e%e5%8d%95%e4%bd%8d)。

其他一些值得看一下的属性

Font 样式:

- [font-variant](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant): 在小型大写字母和普通文本选项之间切换。
- [font-kerning](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-kerning): 开启或关闭字体间距选项。
- [font-feature-settings](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-feature-settings): 开启或关闭不同的 [OpenType](https://zh.wikipedia.org/wiki/OpenType) 字体特性。
- [font-variant-alternates](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-alternates): 控制给定的自定义字体的替代字形的使用。
- [font-variant-caps](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-caps): 控制大写字母替代字形的使用。
- [font-variant-east-asian](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-east-asian): 控制东亚文字替代字形的使用, 像日语和汉语。
- [font-variant-ligatures](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-ligatures): 控制文本中使用的连写和上下文形式。
- [font-variant-numeric](font-variant-numeric): 控制数字，分式和序标的替代字形的使用。
- [font-variant-position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-position): 控制位于上标或下标处，字号更小的替代字形的使用。
- [font-size-adjust](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-variant-position): 独立于字体的实际大小尺寸，调整其可视大小尺寸。
- [font-stretch](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-stretch): 在给定字体的可选拉伸版本中切换。
- [text-underline-position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-underline-position): 指定下划线的排版位置，通过使用 text-decoration-line 属性的 underline 值。
- [text-rendering](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-rendering): 尝试执行一些文本渲染优化。

文本布局样式：

- [text-indent](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-indent): 指定文本内容的第一行前面应该留出多少的水平空间。
- [text-overflow](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-overflow): 定义如何向用户表示存在被隐藏的溢出内容。
- [white-space](https://developer.mozilla.org/zh-CN/docs/Web/CSS/white-space): 定义如何处理元素内部的空白和换行。
- [word-break](https://developer.mozilla.org/zh-CN/docs/Web/CSS/word-break): 指定是否能在单词内部换行。
- [direction](https://developer.mozilla.org/zh-CN/docs/Web/CSS/direction): 定义文本的方向 (这取决于语言，并且通常- 最好让 HTML 来处理这部分，因为它是和文本内容相关联的。)
- [hyphens](https://developer.mozilla.org/zh-CN/docs/Web/CSS/hyphens): 为支持的语言开启或关闭连字符。
- [line-break](https://developer.mozilla.org/zh-CN/docs/Web/CSS/line-break): 对东亚语言采用更强或更弱的换行规则。
- [text-align-last](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-align-last): 定义一个块或行的最后一行，恰好位于一个强制换行前时，如何对齐。
- [text-orientation](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-orientation): 定义行内文本的方向。
- [word-wrap](https://developer.mozilla.org/zh-CN/docs/Web/CSS/word-wrap): 指定浏览器是否可以在单词内换行以避免超出范围。
- [writing-mode](https://developer.mozilla.org/zh-CN/docs/Web/CSS/writing-mode): 定义文本行布局为水平还是垂直，以及后继文本流的方向。

**Font 简写：**

许多字体的属性也可以通过 font 的简写方式来设置 . 这些是按照以下顺序来写的： font-style, font-variant, font-weight, font-stretch, font-size, line-height, and font-family.

```css
font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
```

#### 列表样式

##### 列表特定样式

- [list-style-type](https://developer.mozilla.org/zh-CN/docs/Web/CSS/list-style-type) ：设置用于列表的项目符号的类型，例如无序列表的方形或圆形项目符号，或有序列表的数字，字母或罗马数字。
- [list-style-position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/list-style-position) ：设置在每个项目开始之前，项目符号是出现在列表项内，还是出现在其外。
- [list-style-image](https://developer.mozilla.org/zh-CN/docs/Web/CSS/list-style-position) ：允许您为项目符号使用自定义图片，而不是简单的方形或圆形。

list-style 速记

```css
ul {
  list-style: square url(example.png) inside;
}
```

属性值可以任意顺序排列，你可以设置一个，两个或者三个值（该属性的默认值为 disc, none, outside）

##### 管理列表计数

**start：**

start 属性允许你从 1 以外的数字开始计数

```html
<!-- 序号从4开始 -->
<ol start="4">
  <li>Toast pitta, leave to cool, then slice down the edge.</li>
  <li>
    Fry the halloumi in a shallow, non-stick pan, until browned on both sides.
  </li>
  <li>Wash and chop the salad.</li>
  <li>Fill pitta with salad, humous, and fried halloumi.</li>
</ol>
```

**reversed：**

reversed 属性将启动列表倒计数。

**value：**

value 属性允许设置列表项指定数值

#### 链接样式

链接状态

- Link (没有访问过的): 这是链接的默认状态，当它没有处在其他状态的时候，它可以使用:link 伪类来应用样式。
- Visited: 这个链接已经被访问过了(存在于浏览器的历史纪录), 它可以使用 :visited 伪类来应用样式。
- Hover: 当用户的鼠标光标刚好停留在这个链接，它可以使用 :hover 伪类来应用样式。
- Focus: 一个链接当它被选中的时候 (比如通过键盘的 Tab 移动到这个链接的时候，或者使用编程的方法来选中这个链接 HTMLElement.focus()) 它可以使用 :focus 伪类来应用样式。
- Active: 一个链接当它被激活的时候 (比如被点击的时候)，它可以使用 :active 伪类来应用样式。

#### Web 字体

在 CSS 的开始处有一个[@font-face](https://developer.mozilla.org/zh-CN/docs/Web/CSS/@font-face)块，它指定要下载的字体文件

```css
/* 定义字体 */
@font-face {
  font-family: 'myFont';
  src: url('myFont.ttf');
}

/* 使用字体 */
html {
  font-family: 'myFont', 'Bitstream Vera Serif', serif;
}
```

- 览器支持不同的字体格式，因此您需要多种字体格式以获得良好的跨浏览器支持。例如,大多数现代浏览器都支持 WOFF / WOFF2(Web Open Font Format versions 1 and 2，Web 开放字体格式版本 1 和 2)，它是最有效的格式，但是旧版本 IE 只支持 EOT (Embedded Open Type，嵌入式开放类型)的字体,你可能需要包括一个 SVG 版本的字体支持旧版本的 iPhone 和 Android 浏览器。我们将向您展示如何生成所需的代码。
- 字体一般都不能自由使用。您必须为他们付费，或者遵循其他许可条件，比如在代码中(或者在您的站点上)提供字体创建者。你不应该在没有适当的授权的情况下偷窃字体。

### CSS 排版

#### 正常布局流

默认情况下的布局：

- 一个块级元素的内容宽度是其父元素的 100%，其高度与其内容高度一致。行内元素的 height width 与内容一致。
- 两个块级元素通常情况下会在上一个元素下面另起一行。
- 只要在其父级块级元素的宽度内有足够的空间，它们与其他行内元素、相邻的文本内容（或者被包裹的）被安排在同一行。如果空间不够，溢出的文本或元素将移到新的一行。
- 两个相邻的元素都设置了 margin 并且两个 margin 有重叠，那么更大的设置会被保留，小的则会消失 --- 这被称为外边距叠加，我们之前见到过。

#### 弹性盒子

##### flex 模型说明

![flex说明](https://developer.mozilla.org/files/3739/flex_terms.png)

- 主轴（main axis）是沿着 flex 元素放置的方向延伸的轴（比如页面上的横向的行、纵向的列）。该轴的开始和结束被称为 main start 和 main end。
- 交叉轴（cross axis）是垂直于 flex 元素放置方向的轴。该轴的开始和结束被称为 cross start 和 cross end。
- 设置了 display: flex 的父元素被称之为 flex 容器（flex container）。
- 在 flex 容器中表现为柔性的盒子的元素被称之为 flex 项（flex item）

##### flex 属性

**列和行：**

- flex-direction 控制主轴方向是行还是列(row/column)，还有 row-reverse/column-reverse 向相反的方向排列。
- flex-wrap 子代超过容器是否换行。
  - nowrap 不换行。
  - wrap 换行 从交叉轴 cross-start 向 cross-end 的方向进行换行。
  - wrap-reverse 和 wrap 一样但是换行方向与 wrap 相反
- flex-flow flex-direction flex-wrap 的缩写（flex-flow: 方向 换行;）。

**flex 项的尺寸和排序：**

- flex-grow 主轴方向的 flex 元素增长系数。它指定了 flex 容器中剩余空间的多少应该分配给该元素
- flex-shrink 属性指定了 flex 元素的收缩规则。flex 元素仅在默认宽度之和大于容器的时候才会发生收缩，其收缩的大小是依据 flex-shrink 的值。
- flex-basis 指定了 flex 元素在主轴方向上的初始大小。
- flex flex 元素属性缩写
  - 第一个就是上面所讨论过的无单位比例。可以单独指定全写 flex-grow 属性的值。
  - 第二个无单位比例 — flex-shrink — 一般用于溢出容器的 flex 项。这指定了从每个 flex 项中取出多少溢出量，以阻止它们溢出它们的容器。
  - 第三个是上面讨论的最小值。可以单独指定全写 flex-basis 属性的值。
- order 调整 flex 项排序
  - 所有 flex 项默认的 order 值是 0。
  - order 值大的 flex 项比 order 值小的在显示顺序中更靠后。
  - 相同 order 值的 flex 项按源顺序显示。所以假如你有四个元素，其 order 值分别是 2，1，1 和 0，那么它们的显示顺序就分别是第四，第二，第三，和第一。
  - 第三个元素显示在第二个后面是因为它们的 order 值一样，且第三个元素在源顺序中排在第二个后面。

**水平和垂直对齐：**

- [align-items](https://developer.mozilla.org/zh-CN/docs/Web/CSS/align-items) 交叉轴方向上的对齐方式。
- [justify-content](https://developer.mozilla.org/zh-CN/docs/Web/CSS/justify-content) 控制 flex 项在主轴上的位置。

#### 网格

![网格](https://mdn.mozillademos.org/files/13899/grid.png)

网格通常具有列（column），行（row），以及在每行和列之间的间隙——通常称为沟槽（gutter）。

[网格布局](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Grid_Layout)

#### 浮动

float 属性使得元素脱离文档流，可以选择左浮动和右浮动（left/right）

**清除浮动：**

所有在浮动下面的自身不浮动的内容都将围绕浮动元素进行包装，可以使用 clear 属性清除浮动，它主要意味着"此处停止浮动"——这个元素和源码中后面的元素将不浮动

clear 可以取三个值：

- left：停止任何活动的左浮动
- right：停止任何活动的右浮动
- both：停止任何活动的左右浮动

**浮动问题：**

- 整个宽度可能难以计算，你开始给这些框加上样式时，比如添加背景、外边距、内边距等等，如[例子](https://mdn.github.io/learning-area/css/css-layout/floats/3_broken-layout.html)可能原本在一行上的元素就不在一行了，最后一个元素结果在前面元素之下。可能需要 box-sizing: border-box;来解决
- 同上的例子最后的 footer 在紧贴最长的浮动元素下面，如果设置 margin，值会无效——浮动的元素存在于正常的文档布局流之外。需要新加一个元素（也可以是伪元素）在 footer 与最后浮动的元素之间，并给该元素 clear 样式。（推荐使用伪元素）

```html
<!-- 使用元素清除 -->
<div class="clearfix"></div>
.clearfix { clear: both; }
<!-- 伪元素清除浮动，直接添加类 -->
.clearfix:after { 
   content: '.'; 
   visibility: hidden; 
   display: block; 
   height: 0; 
   clear: both; }
```

#### 定位

要使某个元素上的特定类型的定位，我们使用 position 属性。

**静态定位：**

静态定位是每个元素获取的默认值——它只是意味着“将元素放入它在文档布局流中的正常位置（position: static;）

**相对定位：**

相对定位是相对于元素自身原来的位置使用 top，bottom，left 和 right 属性来控制元素与原来的位置距离（position: relative;）

**绝对定位：**

绝对定位于相对定位类似，但不同的是绝对定位参照的位移距离不是自身，而是父级或者祖先级第一个存在 position 不为 static 的定位元素，如果都不存在则会根据 html 标签来定位。（position: absolute;）

**固定定位：**

固定定位与绝对定位的工作方式完全相同，主要区别是固定定位固定元素则是相对于浏览器视口本身，也就是及时有滚动条的网页不管怎么滚动滚动条，元素还是在原来的位置不跟随页面滚动。（position: fixed;）

**粘性定位：**

粘性定位它基本上是相对位置和固定位置的混合体，它允许被定位的元素表现得像相对定位一样，直到它滚动到某个阈值点（例如，从视口顶部起 1​​0 像素）为止，此后它就变得固定了。（position: sticky）

**介绍 z-index：**

所有这些除静态元素的定位，他们之间发生重叠时就需要使用 z-index 决定谁显示在顶部

#### 多列布局

多列布局通过这两个属性开启 column-count 或者 column-width。

- column-count 将创建指定数量的列
- column-width 浏览器将按照你指定的宽度尽可能多的创建列；任何剩余的空间之后会被现有的列平分。
- column-gap 改变列间间隙。
- column-rule 在列间加入一条分割线。与 border 属性类似， 也有 column-rule-color 和 column-rule-style 的缩写

**列与内容折断：**

当你把内容放入多列布局容器内，内容可能由于过长导致一部分内容在一列另一部分内容在另外一列上，内容被折断。

可以使用 [CSS Fragmentation](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_%E5%88%86%E7%89%87)解决此问题。

#### 媒体查询

```css
@media media-type and (media-feature-rule) {
  /* CSS rules go here */
}
```

媒体查询组成：

- media-type 一个媒体类型，告诉浏览器这段代码是用在什么类型的媒体上的（例如印刷品或者屏幕）；
- media-feature-rule 一个媒体表达式，是一个被包含的 CSS 生效所需的规则或者测试；
- CSS rules 一组 CSS 规则，会在测试通过且媒体类型正确的时候应用。

**媒体类型：**

媒体类型为：

- all 用于所有设备
- print 用于打印机和打印预览
- screen 用于电脑屏幕，平板电脑，智能手机等。
- speech 应用于屏幕阅读器等发声设备

**媒体特征规则：**

宽和高  

可以使用宽度和高度来添加css规则生效的条件，列如使用min-width、max-width和width媒体特征，在视口宽度大于或者小于某个大小——或者是恰好处于某个大小——的时候，应用CSS。

朝向

orientation 用屏幕是竖放还是横放来让条件生成。

- orientation: landscape 横放指的是屏幕width 大于 height
- orientation: portrait 竖放指的是屏幕width 小于 height

**使用指点设备：**

pointer媒体特征：

- fine 指针是类似于鼠标或者触控板的东西，它让用户可以精确指向一片小区域。
- coarse 指针是你在触摸屏上的手指。
- none值意味着，用户没有指点设备，也许是他们正只使用键盘导航，或者是语音命令。

**媒体查询逻辑：**

```css
/* 与 */
/* body的文字只会在视口至少为400像素宽，且设备横放时变为蓝色。 */
@media screen and (min-width: 400px) and (orientation: landscape) {
    body {
        color: blue;
    }
}

/* 或 */
/* 文本会在视口至少为400像素宽的时候或者设备处于横放状态的时候变为蓝色。 */
@media screen and (min-width: 400px), screen and (orientation: landscape) {
    body {
        color: blue;
    }
}

/* 非 */
/* 文本只会在朝向为竖着的时候变成蓝色。 */
@media not all and (orientation: landscape) {
    body {
        color: blue;
    }
}
```

如果做响应式布局优先做移动端，用在最小的那个设备上的视图很多时候都是一个简单的单列内容，很像正常文本流显示的那样。这意味着，你很可能不需要为小设备做多少布局设计，合适地安排下你的源代码，默认情况下你就可以得到可读的布局。
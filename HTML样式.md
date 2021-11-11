# HTML样式

首先我们先看以下

## 学习 CSS

CSS被用来同时控制多重网页的样式和布局。

通过使用 CSS，所有的格式化均可从 HTML 中剥离出来，并存储于一个独立的文件中。

### 如何使用CSS

CSS 是在 HTML 4 开始使用的,是为了更好的渲染HTML元素而引入的.

CSS 可以通过以下方式添加到HTML中:

- 内联样式- 在HTML元素中使用"style" **属性**
- 内部样式表 -在HTML文档头部 <head> 区域使用<style> **元素** 来包含CSS
- 外部引用 - 使用外部 CSS **文件**

最好的方式是通过外部引用CSS文件.

------

## 学习 JavaScript

JavaScript 可以让你的网页更加生动。

如果你只想展示内容，静态网站是很好的展示形象，如果你想与用户进行交换或者让网页更加生动那就需要使用到Javascript。

JavaScript是互联网上最流行的脚本语言，目前所有主流浏览器都支持Javascript。

如果你想学习更多关于Javascript的知识，可以访问本站的[JavaScript 教程](https://www.runoob.com/js/js-tutorial.html).

#### 那我们回到HTML样式

## 内联样式

当特殊的样式需要应用到个别元素时，就可以使用内联样式。 使用内联样式的方法是在相关的标签中使用样式属性。样式属性可以包含任何 CSS 属性

如何改变段落的颜色和左外边距。

```
<p style="color:blue;margin-left:20px;">这是一个段落。</p>
```

## HTML样式- 背景颜色

背景色属性（background-color）定义一个元素的背景颜色：

<body style="background-color:yellow;"> 

<h2 style="background-color:red;">这是一个标题</h2> 

<p style="background-color:green;">这是一个段落。</p> </body>

## HTML 样式 - 字体, 字体颜色 ，字体大小

我们可以使用font-family（字体），color（颜色），和font-size（字体大小）属性来定义字体的样式:

<h1 style="font-family:verdana;">一个标题</h1> <p style="font-family:arial;color:red;font-size:20px;">一个段落。</p>

## HTML 样式 - 文本对齐方式

使用 text-align（文字对齐）属性指定文本的水平与垂直对齐方式：

<h1 style="text-align:center;">居中对齐的标题</h1> <p>这是一个段落。</p>

## 内部样式表

当单个文件需要特别样式时，就可以使用内部样式表。你可以在 ead> 部分通过 <style>标签定义内部样式表:

## 外部样式表

当样式需要被应用到很多页面的时候，外部样式表将是理想的选择。使用外部样式表，你就可以通过更改一个文件来改变整个站点的外观。
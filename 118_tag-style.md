# HTML &lt;style&gt; 标签

## 实例

在 HTML 文档中使用 &lt;style&gt; 元素：

```HTML
<html> 
<head> 
<style type="text/css"> 
h1 {color:red;} 
p {color:blue;} 
</style> 
</head> 

<body> 
<h1>这是一个标题</h1> 
<p>这是一个段落。</p> 
</body> 

</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_style)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;style&gt; 标签。

--------

## 标签定义及使用说明

&lt;style&gt; 标签定义 HTML 文档的样式信息。

在 &lt;style&gt; 元素中，您可以规定在浏览器中如何呈现 HTML 文档。

每个 HTML 文档能包含多个 &lt;style&gt; 标签。

--------

## 提示和注释

**提示：** 如需链接外部样式表，请使用 [&lt;link&gt;](085_tag-link.md) 标签。

**提示：** 如需学习更多有关样式表的知识，请阅读我们的 [CSS 教程](css-tutorial.html)。

**注释：** 如果没有使用 "scoped" 属性，则每一个 &lt;style&gt; 标签必须位于 head 头部区域。

--------

## HTML 4.01 与 HTML5之间的差异

"scoped" 属性是 HTML 5 中的新属性，它允许我们为文档的指定部分定义样式，而不是整个文档。 

 如果使用 "scoped" 属性，那么所规定的样式只能应用到 style 元素的父元素及其子元素。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [media](att-style-media.html) | _media_query_ | 为样式表规定不同的媒体类型。 |
| [scoped](att-style-scoped.html) (New) | scoped | 如果使用该属性，则样式仅仅应用到 style 元素的父元素及其子元素。 |
| [type](att-style-type.html) | text/css | 规定样式表的 MIME 类型。 |

--------

## 全局属性

&lt;style&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;style&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML CSS](http://www.runoob.com/html/html-css.html)

HTML DOM 参考手册：[Style 对象](http://www.runoob.com/jsref/dom-obj-style.html)

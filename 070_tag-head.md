# HTML &lt;head&gt; 标签

## 实例

一份在头部带有 &lt;title&gt; 标签的 HTML 文档：

```HTML
<!DOCTYPE html> 
<html> 
<head> 
<meta charset="utf-8"> 
<title>文档标题</title> 
</head> 

<body> 
文档内容...... 
</body> 

</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_basic)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;head&gt; 标签。

--------

## 标签定义及使用说明

&lt;head&gt; 元素是所有头部元素的容器。

&lt;head&gt; 元素必须包含文档的标题（title），可以包含脚本、样式、meta 信息 以及其他更多的信息。

以下列出的元素能被用在 &lt;head&gt; 元素内部：

 * [&lt;title&gt;](130_tag-title.md) （在头部中，这个元素是必需的）
 * [&lt;style&gt;](118_tag-style.md)
 * [&lt;base&gt;](033_tag-base.md)
 * [&lt;link&gt;](085_tag-link.md)
 * [&lt;meta&gt;](089_tag-meta.md)
 * [&lt;script&gt;](110_tag-script.md)
 * [&lt;noscript&gt;](093_tag-noscript.md)

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 不再支持 profile 属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| profile | _URL_ | **HTML5 不支持。** 规定文档 URL 的一系列规则。这些规则能被浏览器识别并且准确读取 &lt;meta&gt; 标签的内容属性中的信息。 |

--------

## 全局属性

&lt;head&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[在 &lt;head&gt; 中使用 &lt;base&gt; 标签](http://www.runoob.com/try/try.php?filename=tryhtml_base_test)

 本例演示如何使用 &lt;base&gt; 标签规定页面中所有链接的默认 URL 和默认 target。

[在 &lt;head&gt; 中使用 &lt;style&gt; 标签](http://www.runoob.com/try/try.php?filename=tryhtml_style)

 本例演示如何在 &lt;head&gt; 部分添加样式信息。

[在 &lt;head&gt; 中使用 &lt;link&gt; 标签](http://www.runoob.com/try/try.php?filename=tryhtml_link_tag)

 本例演示如何使用 &lt;link&gt; 标签链接到一个外部样式表。

--------

## 相关文章

HTML 教程：[HTML 头部](html-head.html)

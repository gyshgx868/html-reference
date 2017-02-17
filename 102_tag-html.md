# HTML &lt;html&gt; 标签

## 实例

简单的 HTML5 文档：

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

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;html&gt; 标签。

--------

## 标签定义及使用说明

&lt;html&gt; 标签告知浏览器这是一个 HTML 文档。

&lt;html&gt; 标签是 HTML 文档中最外层的元素。

&lt;html&gt; 标签是所有其他 HTML 元素（除了 [&lt;!DOCTYPE&gt;](022_tag-doctype.md) 标签）的容器。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中，增加了一个新属性：manifest。

--------

## HTML 与 XHTML 之间的差异

xmlns 属性在 XHTML 中是必需的，但在 HTML中不是。

然而，即使 XHTML 文档中的 &lt;html&gt; 没有使用 xmlns 属性，W3C 上的 HTML 验证器也不会报错。这是因为 "xmlns=http://www.w3.org/1999/xhtml" 是一个固定值，即使您没有包含它，此值也会被添加到 &lt;html&gt; 标签中。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [manifest](att-html-manifest.html) (New) | _URL_ | 定义一个 URL，在这个 URL 上描述了文档的缓存信息。 |
| [xmlns](att-html-xmlns.html) | http://www.w3.org/1999/xhtml | **HTML 不支持。只有 XHTML 支持。** 规定 XML 的 namespace 属性（如果您需要您的内容符合 XHTML，则使用这个属性。）。 |

--------

## 全局属性

&lt;html&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

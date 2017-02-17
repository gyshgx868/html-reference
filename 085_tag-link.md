# HTML &lt;link&gt; 标签

## 实例

链接到外部样式文件:

```HTML
<head>
<link rel="stylesheet" type="text/css" href="theme.css">
</head>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_link_tag)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;link&gt; 标签。

--------

## 标签定义及使用说明

&lt;link&gt; 标签定义文档与外部资源的关系。

&lt;link&gt; 标签最常见的用途是链接样式表。

--------

**注意：**  link 元素是空元素，它仅包含属性。

**注意：**  此元素只能存在于 head 部分，不过它可出现任何次数。

--------

## HTML 4.01 与 HTML5之间的差异

一些 HTML 4.01 属性在 HTML5 中不支持。

HTML5 新增了 "sizes" 属性。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;link&gt; 标签没有结束标签。

在 XHTML 中，&lt;link&gt; 标签必须被正确地关闭。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [charset](att-link-charset.html) | _char_encoding_ | **HTML5 不支持该属性。** 定义被链接文档的字符编码方式。 |
| [href](att-link-href.html) | _URL_ | 定义被链接文档的位置。 |
| [hreflang](att-link-hreflang.html) | _language_code_ | 定义被链接文档中文本的语言。 |
| [media](att-link-media.html) | _media_query_ | 规定被链接文档将显示在什么设备上。 |
| [rel](att-link-rel.html) | alternate<br/>archives<br/>author<br/>bookmark<br/>external<br/>first<br/>help<br/>icon<br/>last<br/>license<br/>next<br/>nofollow<br/>noreferrer<br/>pingback<br/>prefetch<br/>prev<br/>search<br/>sidebar<br/>stylesheet<br/>tag<br/>up | 必需。定义当前文档与被链接文档之间的关系。 |
| [rev](att-link-rev.html) | _reversed relationship_ | **HTML5 不支持该属性。** 定义被链接文档与当前文档之间的关系。 |
| [sizes](att-link-sizes.html) (New) | _Height_ x _Width_ any | 定义了链接属性大小，只对属性 rel="icon" 起作用。 |
| [target](att-link-target.html) | _blank<br/>_self<br/>_top<br/>_parent<br/>_frame_name_ | **HTML5 不支持该属性。** 定义在何处加载被链接文档。 |
| [type](att-link-type.html) | _MIME_type_ | 规定被链接文档的 MIME 类型。 |

--------

## 全局属性

&lt;link&gt; 标签支持全局属性，查看完整属性表 [HTML 全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;link&gt; 标签支持所有 [HTML 事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML 样式](http://www.runoob.com/html/html-css.html)

HTML DOM 参考手册：[Link 对象](http://www.runoob.com/jsref/dom-obj-link.html)

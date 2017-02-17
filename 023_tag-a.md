# HTML &lt;a&gt; 标签

## 实例

链接到菜鸟教程 ：

```HTML
<a href="http://www.runoob.com">访问菜鸟教程!</a>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_link_test)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;a&gt; 标签。

--------

## 标签定义及使用说明

&lt;a&gt; 标签定义超链接，用于从一个页面链接到另一个页面。

&lt;a&gt; 元素最重要的属性是 href 属性，它指定链接的目标。

在所有浏览器中，链接的默认外观如下：

 * 未被访问的链接带有下划线而且是蓝色的
 * 已被访问的链接带有下划线而且是紫色的
 * 活动链接带有下划线而且是红色的

--------

## 提示和注释

**提示：** 如果没有使用 href 属性，则不能使用 hreflang、media、rel、target 以及 type 属性。

**提示：** 通常在当前浏览器窗口中显示被链接页面，除非规定了其他 target。

**提示：** 请使用 CSS 来改变链接的样式。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 4.01 中，&lt;a&gt; 标签既可以是超链接，也可以是锚。在 HTML5 中，&lt;a&gt; 标签是超链接，但是假如没有 href 属性，它仅仅是超链接的一个占位符。

HTML5 有一些新的属性，同时不再支持一些 HTML 4.01 的属性。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [charset](http://www.runoob.com/tags/att-a-charset.html) | _char_encoding_ | HTML5 不支持。规定目标 URL 的字符编码。 |
| [coords](http://www.runoob.com/tags/att-a-coords.html) | _coordinates_ | HTML5 不支持。规定链接的坐标。 |
| [download](http://www.runoob.com/tags/att-a-download.html) (New) | _filename_ | 指定下载链接 |
| [href](http://www.runoob.com/tags/att-a-href.html) | _URL_ | 规定链接的目标 URL。 |
| [hreflang](http://www.runoob.com/tags/att-a-hreflang.html) | _language_code_ | 规定目标 URL 的基准语言。仅在 href 属性存在时使用。 |
| [media](http://www.runoob.com/tags/att-a-media.html) (New) | _media_query_ | 规定目标 URL 的媒介类型。默认值：all。仅在 href 属性存在时使用。 |
| [name](http://www.runoob.com/tags/att-a-name.html) | _section_name_ | HTML5 不支持。规定锚的名称。 |
| [rel](http://www.runoob.com/tags/att-a-rel.html) | alternate<br/>author<br/>bookmark<br/>help<br/>license<br/>next<br/>nofollow<br/>noreferrer<br/>prefetch<br/>prev<br/>search<br/>tag | 规定当前文档与目标 URL 之间的关系。仅在 href 属性存在时使用。 |
| [rev](http://www.runoob.com/tags/att-a-rev.html) | _text_ | HTML5 不支持。规定目标 URL 与当前文档之间的关系。 |
| [shape](http://www.runoob.com/tags/att-a-shape.html) | default<br/>rect<br/>circle<br/>poly | HTML5 不支持。规定链接的形状。 |
| [target](http://www.runoob.com/tags/att-a-target.html) | _blank<br/>_parent<br/>_self<br/>_top<br/>_framename_ | 规定在何处打开目标 URL。仅在 href 属性存在时使用。 |
| [type](http://www.runoob.com/tags/att-a-type.html) (New) | _MIME_type_ | 规定目标 URL 的 MIME 类型。仅在 href 属性存在时使用。

注：MIME = Multipurpose Internet Mail Extensions。 |

## 全局属性

&lt;a&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;a&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[创建超级链接](http://www.runoob.com/try/try.php?filename=tryhtml_link)

 本例演示如何在 HTML 文档中创建链接。

[将图像作为链接](http://www.runoob.com/try/try.php?filename=tryhtml_link_image)

 本例演示如何使用图像作为链接。

[在新的浏览器窗口打开链接](http://www.runoob.com/try/try.php?filename=tryhtml_link_target)

 本例演示如何在新窗口打开一个页面，这样的话访问者就无需离开您的站点了。

[创建电子邮件链接](http://www.runoob.com/try/try.php?filename=tryhtml_link_mailto)

 本例演示如何链接到一个邮件。（本例在安装邮件客户端程序后才能工作。）

[创建电子邮件链接 2](http://www.runoob.com/try/try.php?filename=tryhtml_link_mailto2)

 本例演示更加复杂的邮件链接。

[使用锚跳转到同一个页面的不同位置](http://www.runoob.com/try/try.php?filename=tryhtml5_a_href_anchor)

 本例演示如何使用锚的 id 属性跳转到页面的不同位置（ HTML5 不支持 name 属性）。

--------

## 相关文章

HTML 教程：[HTML 链接](http://www.runoob.com/html/html-links.html)

HTML DOM 参考手册： [Anchor 对象](http://www.runoob.com/jsref/dom-obj-anchor.html)

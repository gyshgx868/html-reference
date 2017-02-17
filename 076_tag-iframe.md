# HTML &lt;iframe&gt; 标签

## 实例

标记一个内联框架：

```HTML
<iframe src="http://www.runoob.com"></iframe>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_iframe)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;iframe&gt; 标签。

--------

## 标签定义及使用说明

&lt;iframe&gt; 标签规定一个内联框架。

一个内联框架被用来在当前 HTML 文档中嵌入另一个文档。

--------

## 提示和注释

**提示：** 您可以把需要的文本放置在 &lt;iframe&gt; 和 &lt;/iframe&gt; 之间，这样就可以应对不支持 &lt;iframe&gt; 的浏览器。

**提示：** 使用 CSS 为 &lt;iframe&gt; （包括滚动条）定义样式。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 新增了一些新的属性，同时去掉了 HTML 4.01 中的一些属性。

--------

## HTML 与 XHTML 之间的差异

在 XHTML 中，name 属性已被废弃，并将被去掉。请使用 id 属性代替。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-iframe-align.html) | left<br/>right<br/>top<br/>middle<br/>bottom | **HTML5 不支持。HTML 4.01 已废弃。** 规定如何根据周围的元素来对齐 &lt;iframe&gt;。 |
| [frameborder](att-iframe-frameborder.html) | 1<br/>0 | **HTML5 不支持。** 规定是否显示 &lt;iframe&gt; 周围的边框。 |
| [height](att-iframe-height.html) | _pixels_ | 规定 &lt;iframe&gt; 的高度。 |
| [longdesc](att-iframe-longdesc.html) | _URL_ | **HTML5 不支持。** 规定一个页面，该页面包含了有关 &lt;iframe&gt; 的较长描述。 |
| [marginheight](att-iframe-marginheight.html) | _pixels_ | **HTML5 不支持。** 规定 &lt;iframe&gt; 的顶部和底部的边距。 |
| [marginwidth](att-iframe-marginwidth.html) | _pixels_ | **HTML5 不支持。** 规定 &lt;iframe&gt; 的左侧和右侧的边距。 |
| [name](att-iframe-name.html) | _name_ | 规定 &lt;iframe&gt; 的名称。 |
| [sandbox](att-iframe-sandbox.html) (New) | ""<br/>allow-forms<br/>allow-same-origin<br/>allow-scripts<br/>allow-top-navigation | 对 &lt;iframe&gt; 的内容定义一系列额外的限制。 |
| [scrolling](att-iframe-scrolling.html) | yes<br/>auto | **HTML5 不支持。** 规定是否在 &lt;iframe&gt; 中显示滚动条。 |
| [seamless](att-iframe-seamless.html) (New) | seamless | 规定 &lt;iframe&gt; 看起来像是父文档中的一部分。 |
| [src](att-iframe-src.html) | _URL_ | 规定在 &lt;iframe&gt; 中显示的文档的 URL。 |
| [srcdoc](att-iframe-srcdoc.html) (New) | _HTML_code_ | 规定页面中的 HTML 内容显示在 &lt;iframe&gt; 中。 |
| [width](att-iframe-width.html) | _pixels_ | 规定 &lt;iframe&gt; 的宽度。 |

--------

## 全局属性

&lt;iframe&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;iframe&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML 框架](html-iframe.html)

HTML DOM 参考手册：[IFrame 对象](http://www.runoob.com/jsref/dom-obj-frame.html)

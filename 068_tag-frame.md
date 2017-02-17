# HTML &lt;frame&gt; 标签 - HTML5 不支持

## 实例

简单的三框架页面：

```HTML
<frameset cols="25%,50%,25%">
  <frame src="frame_a.htm">
  <frame src="frame_b.htm">
  <frame src="frame_c.htm">
</frameset>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_frame_cols)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;frame&gt; 标签。

--------

## 标签定义及使用说明

HTML5 不支持 &lt;frame&gt; 标签。

&lt;frame&gt; 标签定义 &lt;frameset&gt; 中的子窗口（框架）。

&lt;frameset&gt; 中的每个 &lt;frame&gt; 都可以设置不同的属性，比如 border、scrolling, noresize 等等。

**注释：** 如果您希望验证包含框架的页面，请确保 [&lt;!DOCTYPE&gt;](022_tag-doctype.md) 被设置为 "HTML Frameset DTD" 或者 "XHTML Frameset DTD" 。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 不支持 &lt;frame&gt; 标签，HTML 4.01 支持 &lt;frame&gt; 标签。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;frame&gt; 标签没有结束标签。在 XHTML 中，&lt;frame&gt; 标签必须被正确地关闭。

--------

## 可选的属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [frameborder](att-frame-frameborder.html) | 0<br/>1 | **HTML5 不支持。** 规定是否显示框架周围的边框。 |
| [longdesc](att-frame-longdesc.html) | _URL_ | **HTML5 不支持。** 规定一个包含有关框架内容的长描述的页面。 |
| [marginheight](att-frame-marginheight.html) | _pixels_ | **HTML5 不支持。** 规定框架的上方和下方的边距。 |
| [marginwidth](att-frame-marginwidth.html) | _pixels_ | **HTML5 不支持。** 规定框架的左侧和右侧的边距。 |
| [name](att-frame-name.html) | _name_ | **HTML5 不支持。** 规定框架的名称。 |
| [noresize](att-frame-noresize.html) | noresize | **HTML5 不支持。** 规定无法调整框架的大小。 |
| [scrolling](att-frame-scrolling.html) | yes<br/>no<br/>auto | **HTML5 不支持。** 规定是否在框架中显示滚动条。 |
| [src](att-frame-src.html) | _URL_ | **HTML5 不支持。** 规定在框架中显示的文档的 URL。 |

--------

## 标准属性

在 HTML 4.01 中，&lt;frame&gt; 标签支持如下标准属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| class | _classname_ | 规定元素的类名 |
| id | _id_ | 规定元素的唯一 id |
| style | _style_definition_ | 规定元素的行内样式 |
| title | _text_ | 规定元素的额外信息 |

如需完整的描述，请访问[标准属性](003_ref-standardattributes.md)。

--------

## 事件属性

根据 W3C 的标准，在 HTML 4.01 中，&lt;frame&gt; 标签不支持任何的事件属性。

但是，所有的浏览器都支持 onload 事件。

如需完整的描述，请访问[事件属性](r/tags/004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[水平框架](http://www.runoob.com/try/try.php?filename=tryhtml_frame_rows)

 本例演示：如何使用三份不同的文档制作一个水平框架。

[混合结构框架](http://www.runoob.com/try/try.php?filename=tryhtml_frame_mix)

 本例演示如何制作含有三份文档的框架结构，同时将他们混合置于行和列之中。

[含有 noresize="noresize" 属性的框架结构](http://www.runoob.com/try/try.php?filename=tryhtml_frame_noresize)

 本例演示 noresize 属性。在本例中，框架是不可调整尺寸的。在框架间的边框上拖动鼠标，您会发现边框是无法移动的。

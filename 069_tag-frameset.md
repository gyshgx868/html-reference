# HTML &lt;frameset&gt; 标签 - HTML5 不支持

## 实例

简单的三框架页面：

```HTML
<frameset cols="25%,*,25%">
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

所有主流浏览器都支持 &lt;frameset&gt; 标签。

--------

## 标签定义及使用说明

HTML5 不支持 &lt;frameset&gt; 标签。

&lt;frameset&gt; 标签定义一个框架集。

&lt;frameset&gt; 元素被用来组织一个或者多个 [&lt;frame&gt;](068_tag-frame.md) 元素。每个 &lt;frame&gt; 有各自独立的文档。

&lt;frameset&gt; 元素规定在框架集中存在多少列或多少行，以及每行每列占用的百分比/像素。

**注释：** 如果您希望验证包含框架的页面，请确保 [&lt;!DOCTYPE&gt;](022_tag-doctype.md) 被设置为 "HTML Frameset DTD" 或者 "XHTML Frameset DTD" 。

--------

## HTML 与 XHTML 之间的差异

无。

--------

## 可选的属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [cols](att-frameset-cols.html) | _pixels<br/>%<br/>*_ | **HTML5 不支持。** 规定框架集中列的数目和尺寸。 |
| [rows](att-frameset-rows.html) | _pixels<br/>%<br/>*_ | **HTML5 不支持。** 规定框架集中行的数目和尺寸。 |

--------

## 标准属性

在 HTML 4.01 中，&lt;frameset&gt; 标签支持如下标准属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| class | _classname_ | 规定元素的类名 |
| id | _id_ | 规定元素的唯一 id |
| style | _style_definition_ | 规定元素的行内样式 |
| title | _text_ | 规定元素的额外信息 |

如需完整的描述，请访问[标准属性](003_ref-standardattributes.md)。

--------

## 事件属性

在 HTML 4.01 中，&lt;frameset&gt; 标签支持如下事件属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| onload | _script_ | 当文档被载入时执行脚本 |
| onunload | _script_ | 当文档被卸下时执行脚本 |

如需完整的描述，请访问[事件属性](r/tags/004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[水平框架](http://www.runoob.com/try/try.php?filename=tryhtml_frame_rows)

 本例演示：如何使用三份不同的文档制作一个水平框架。

[混合结构框架](http://www.runoob.com/try/try.php?filename=tryhtml_frame_mix)

 本例演示如何制作含有三份文档的框架结构，同时将他们混合置于行和列之中。

[含有 noresize="noresize" 属性的框架结构](http://www.runoob.com/try/try.php?filename=tryhtml_frame_noresize)

 本例演示 noresize 属性。在本例中，框架是不可调整尺寸的。在框架间的边框上拖动鼠标，您会发现边框是无法移动的。

--------

## 相关文章

HTML DOM 参考手册： [Frameset 对象](http://www.runoob.com/jsref/dom-obj-frameset.html)

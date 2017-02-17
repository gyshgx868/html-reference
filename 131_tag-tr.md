# HTML &lt;tr&gt; 标签

## 实例

一个简单的 HTML 表格，包含两列两行：

```HTML
<table border="1">
<tr>
<th>Month</th>
<th>Savings</th>
</tr>
<tr>
<td>January</td>
<td>$100</td>
</tr>
</table>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_table_test)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;tr&gt; 标签。

--------

## 标签定义及使用说明

&lt;tr&gt; 标签定义 HTML 表格中的行。

一个 &lt;tr&gt; 元素包含一个或多个 [&lt;th&gt;](127_tag-th.md) 或 [&lt;td&gt;](124_tag-td.md) 元素。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 5 中，不支持 &lt;tr&gt; 标签在 HTML 4.01 中的任何属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-tr-align.html) | right<br/>left<br/>center<br/>justify<br/>char | **HTML5 不支持。** 定义表格行的内容对齐方式。 |
| [bgcolor](att-tr-bgcolor.html) | _rgb(x,x,x)<br/>#xxxxxx<br/>colorname_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定表格行的背景颜色。 |
| [char](att-tr-char.html) | _character_ | **HTML5 不支持。** 规定根据哪个字符来进行文本对齐。 |
| [charoff](att-tr-charoff.html) | _number_ | **HTML5 不支持。** 规定第一个对齐字符的偏移量。 |
| [valign](att-tr-valign.html) | top<br/>middle<br/>bottom<br/>baseline | **HTML5 不支持。** 规定表格行中内容的垂直对齐方式。 |

--------

## 全局属性

&lt;tr&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;tr&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[表格中的标题](http://www.runoob.com/try/try.php?filename=tryhtml_table_header)

 本例演示如何显示表格标题。

[空单元格](http://www.runoob.com/try/try.php?filename=tryhtml_table_nbsp)

 本例演示如何使用 "&amp;nbsp;" 处理没有内容的单元格。

[带有标题的表格](http://www.runoob.com/try/try.php?filename=tryhtml_caption_test)

 本例演示一个带标题(caption)的表格。

[表格内的标签](http://www.runoob.com/try/try.php?filename=tryhtml_table_elements)

 本例演示如何在其他的元素内显示元素。

[跨行或跨列的表格单元格](http://www.runoob.com/try/try.php?filename=tryhtml_table_span)

 本例演示如何定义跨行或跨列的表格单元格。

--------

## 相关文章

HTML 教程：[HTML 表格](http://www.runoob.com/html/html-tables.html)

HTML DOM 参考手册： [Tr 对象](http://www.runoob.com/jsref/dom-obj-tablerow.html)

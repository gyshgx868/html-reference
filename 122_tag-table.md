# HTML &lt;table&gt; 标签

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

所有主流浏览器都支持 &lt;table&gt; 标签。

--------

## 标签定义及使用说明

&lt;table&gt; 标签定义 HTML 表格

一个 HTML 表格包括 &lt;table&gt; 元素，一个或多个 [&lt;tr&gt;](131_tag-tr.md)、[&lt;th&gt;](127_tag-th.md) 以及 [&lt;td&gt;](124_tag-td.md) 元素。

&lt;tr&gt; 元素定义表格行，&lt;th&gt; 元素定义表头，&lt;td&gt; 元素定义表格单元。

更复杂的 HTML 表格也可能包括 &lt;caption&gt;、&lt;col&gt;、&lt;colgroup&gt;、&lt;thead&gt;、&lt;tfoot&gt; 以及 &lt;tbody&gt; 元素。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML5 中，仅支持 "border" 属性，并且只允许使用值 "1" 或 ""。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-table-align.html) | left<br/>center<br/>right | **HTML5 不支持。HTML 4.01 已废弃。** 规定表格相对周围元素的对齐方式。 |
| [bgcolor](att-table-bgcolor.html) | _rgb(x,x,x)<br/>#xxxxxx<br/>colorname_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定表格的背景颜色。 |
| [border](att-table-border.html) | 1<br/>"" | 规定表格单元是否拥有边框。 |
| [cellpadding](att-table-cellpadding.html) | _pixels_ | **HTML5 不支持。** 规定单元边沿与其内容之间的空白。 |
| [cellspacing](att-table-cellspacing.html) | _pixels_ | **HTML5 不支持。** 规定单元格之间的空白。 |
| [frame](att-table-frame.html) | void<br/>above<br/>below<br/>hsides<br/>lhs<br/>rhs<br/>vsides<br/>box<br/>border | **HTML5 不支持。** 规定外侧边框的哪个部分是可见的。 |
| [rules](att-table-rules.html) | none<br/>groups<br/>rows<br/>cols<br/>all | **HTML5 不支持。** 规定内侧边框的哪个部分是可见的。 |
| [summary](att-table-summary.html) | _text_ | **HTML5 不支持。** 规定表格的摘要。 |
| [width](att-table-width.html) | _pixels<br/>%_ | **HTML5 不支持。** 规定表格的宽度。 |

--------

## 全局属性

&lt;table&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;table&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

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

HTML DOM 参考手册：[Table 对象](http://www.runoob.com/jsref/dom-obj-table.html)

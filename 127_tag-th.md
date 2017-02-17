# HTML &lt;th&gt; 标签

## 实例

一个简单的 HTML 表格，带有两个表头单元格和两个数据单元格：

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

所有主流浏览器都支持 &lt;th&gt; 标签。

--------

## 标签定义及使用说明

&lt;th&gt; 标签定义 HTML 表格中的表头单元格。

HTML 表格有两种单元格类型：

 * 表头单元格 - 包含头部信息（由 &lt;th&gt; 元素创建）
 * 标准单元格 - 包含数据（由 [&lt;td&gt;](124_tag-td.md) 元素创建）&lt;th&gt; 元素中的文本通常呈现为粗体并且居中。

&lt;td&gt; 元素中的文本通常是普通的左对齐文本。

--------

## 提示和注释

**提示：** 如果需要将内容横跨多个行或列，请使用 colspan 和 rowspan 属性！

--------

## HTML 4.01 与 HTML5之间的差异

HTML 5 中不再支持 HTML 4.01 中的某些属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [abbr](att-th-abbr.html) | _text_ | **HTML5 不支持。** 规定表头单元格中内容的缩写版本。 |
| [align](att-th-align.html) | left<br/>right<br/>center<br/>justify<br/>char | **HTML5 不支持。** 规定表头单元格内容的水平对齐方式。 |
| [axis](att-th-axis.html) | _category_name_ | **HTML5 不支持。** 对表头单元格进行分类。 |
| [bgcolor](att-th-bgcolor.html) | _rgb(x,x,x)<br/>#xxxxxx<br/>colorname_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定表头单元格的背景颜色。 |
| [char](att-th-char.html) | _character_ | **HTML5 不支持。** 规定根据哪个字符来进行内容的对齐。 |
| [charoff](att-th-charoff.html) | _number_ | **HTML5 不支持。** 规定对齐字符的偏移量。 |
| [colspan](att-th-colspan.html) | _number_ | 规定表头单元格可横跨的列数。 |
| [headers](att-th-headers.html) | _header_id_ | 规定与表头单元格相关联的一个或多个表头单元格。 |
| [height](att-th-height.html) | _pixels<br/>%_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定表头单元格的高度。 |
| [nowrap](att-th-nowrap.html) | nowrap | **HTML5 不支持。HTML 4.01 已废弃。** 规定表头单元格中的内容是否折行。 |
| [rowspan](att-th-rowspan.html) | _number_ | 规定表头单元格可横跨的行数。 |
| [scope](att-th-scope.html) | col<br/>colgroup<br/>row<br/>rowgroup | 规定表头单元格是否是行、列、行组或列组的头部。 |
| [valign](att-th-valign.html) | top<br/>middle<br/>bottom<br/>baseline | **HTML5 不支持。** 规定表头单元格内容的垂直排列方式。 |
| [width](att-th-width.html) | _pixels<br/>%_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定表头单元格的宽度。 |

--------

## 全局属性

&lt;th&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;th&gt; 标签支持所有 [HTML 的事件属性](004_ref-eventattributes.md)。

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

HTML DOM 参考手册： [Th 对象](http://www.runoob.com/jsref/dom-obj-tabledata.html)

# HTML &lt;tbody&gt; 标签

## 实例

带有 &lt;thead&gt;、&lt;tfoot&gt; 和 &lt;tbody&gt; 元素的 HTML 表格：

```HTML
<table border="1">
<thead>
<tr>
<th>Month</th>
<th>Savings</th>
</tr>
</thead>
<tfoot>
<tr>
<td>Sum</td>
<td>$180</td>
</tr>
</tfoot>
<tbody>
<tr>
<td>January</td>
<td>$100</td>
</tr>
<tr>
<td>February</td>
<td>$80</td>
</tr>
</tbody>
</table>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_tbody)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;tbody&gt; 标签。

--------

## 标签定义及使用说明

&lt;tbody&gt; 标签用于组合 HTML 表格的主体内容。

&lt;tbody&gt; 元素应该与 [&lt;thead&gt;](128_tag-thead.md) and [&lt;tfoot&gt;](126_tag-tfoot.md) 元素结合起来使用，用来规定表格的各个部分（主体、表头、页脚）。

通过使用这些元素，使浏览器有能力支持独立于表格表头和表格页脚的表格主体滚动。当包含多个页面的长的表格被打印时，表格的表头和页脚可被打印在包含表格数据的每张页面上。

&lt;tbody&gt; 标签必须被用在以下情境中：作为 &lt;table&gt; 元素的子元素，出现在 &lt;caption&gt;、&lt;colgroup&gt; 和 &lt;thead&gt; 元素之后。

--------

## 提示和注释

**注释：** &lt;tbody&gt; 元素内部必须包含一个或者多个 &lt;tr&gt; 标签。

**提示：** &lt;thead&gt;、&lt;tbody&gt; 和 &lt;tfoot&gt; 元素默认不会影响表格的布局。不过，您可以使用 CSS 来为这些元素定义样式，从而改变表格的外观。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 5 中，不再支持 HTML 4.01 中 &lt;tbody&gt; 标签的任何属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-tbody-align.html) | right<br/>left<br/>center<br/>justify<br/>char | **HTML5 不支持。** 定义 &lt;tbody&gt; 元素中内容的对齐方式。 |
| [char](att-tbody-char.html) | _character_ | **HTML5 不支持。** 规定 &lt;tbody&gt; 元素中内容根据哪个字符来对进行文本对齐。 |
| [charoff](att-tbody-charoff.html) | _number_ | **HTML5 不支持。** 规定 &lt;tbody&gt; 元素中内容的第一个对齐字符的偏移量。 |
| [valign](att-tbody-valign.html) | top<br/>middle<br/>bottom<br/>baseline | **HTML5 不支持。** 规定 &lt;tbody&gt; 元素中内容的垂直对齐方式。 |

--------

## 全局属性

&lt;tbody&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;tbody&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

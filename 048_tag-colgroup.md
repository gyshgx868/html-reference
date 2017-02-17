# HTML &lt;colgroup&gt; 标签

## 实例

&lt;colgroup&gt; 和 &lt;col&gt; 标签为表格中的三个列设置了背景色：

```HTML
<table border="1">
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
</table>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_colgroup_test)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;colgroup&gt; 标签。

--------

## 标签定义及使用说明

&lt;colgroup&gt; 标签用于对表格中的列进行组合，以便对其进行格式化。

通过使用 &lt;colgroup&gt; 标签，可以向整个列应用样式，而不需要重复为每个单元格或每一行设置样式。

**注释：** 只能在 &lt;table&gt; 元素之内，在任何一个 &lt;caption&gt; 元素之后，在任何一个 &lt;thead&gt;、&lt;tbody&gt;、&lt;tfoot&gt;、&lt;tr&gt; 元素之前使用 &lt;colgroup&gt; 标签。

**提示：** 如果想对 &lt;colgroup&gt; 中的某列定义不同的属性，请在 &lt;colgroup&gt; 标签内使用 [&lt;col&gt;](047_tag-col.md) 标签。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中不再支持 HTML 4.01 中的大部分属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-colgroup-align.html) | left<br/>right<br/>center<br/>justify<br/>char | **HTML5 不支持。** 规定在列组合中内容的水平对齐方式。 |
| [char](att-colgroup-char.html) | _character_ | **HTML5 不支持。** 规定根据哪个字符来对齐列组中的内容。 |
| [charoff](att-colgroup-charoff.html) | _number_ | **HTML5 不支持。** 规定第一个对齐字符的偏移量。 |
| [span](att-colgroup-span.html) | _number_ | 规定列组应该横跨的列数。 |
| [valign](att-colgroup-valign.html) | top<br/>middle<br/>bottom<br/>baseline | **HTML5 不支持。** 定义在列组合中内容的垂直对齐方式。 |
| [width](att-colgroup-width.html) | _pixels<br/>%<br/>relative_length_ | **HTML5 不支持。** 规定列组合的宽度。 |

--------

## 全局属性

&lt;colgroup&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;colgroup&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

# HTML &lt;col&gt; 标签

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

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_col_test)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;col&gt; 标签。

--------

## 标签定义及使用说明

&lt;col&gt; 标签规定了 [&lt;colgroup&gt;](048_tag-colgroup.md) 元素内部的每一列的列属性。

通过使用 &lt;col&gt; 标签，可以向整个列应用样式，而不需要重复为每个单元格或每一行设置样式。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中不再支持 HTML 4.01 中的大部分属性。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;col&gt; 标签没有结束标签。

在 XHTML 中，&lt;col&gt; 标签必须被正确的关闭。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-col-align.html) | left<br/>right<br/>center<br/>justify<br/>char | ***HTML5 不支持。** 规定与 &lt;col&gt; 元素相关的内容的水平对齐方式。 |
| [char](att-col-char.html) | _character_ | **HTML5 不支持。** 规定根据哪个字符来对齐与 &lt;col&gt; 元素相关的内容。 |
| [charoff](att-col-charoff.html) | _number_ | **HTML5 不支持。** 规定第一个对齐字符的偏移量。 |
| [span](att-col-span.html) | _number_ | 规定 &lt;col&gt; 元素应该横跨的列数。 |
| [valign](att-col-valign.html) | top<br/>middle<br/>bottom<br/>baseline | **HTML5 不支持。** 规定与 &lt;col&gt; 元素相关的内容的垂直对齐方式。 |
| [width](att-col-width.html) | _%<br/>pixels<br/>relative_length_ | **HTML5 不支持。** Specifies the width of a &lt;col&gt; element |

--------

## 全局属性

&lt;col&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;col&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

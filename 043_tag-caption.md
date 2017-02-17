# HTML &lt;caption&gt; 标签

## 实例

带有标题的表格：

```HTML
<table border="1">
  <caption>Monthly savings</caption>
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

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_caption_test)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;caption&gt; 标签。

--------

## 标签定义及使用说明

&lt;caption&gt; 标签定义表格的标题。

&lt;caption&gt; 标签必须直接放置到 &lt;table&gt; 标签之后。

您只能对每个表格定义一个标题。

**提示：** 通常这个标题会被居中于表格之上。然而，CSS 属性 "text-align" 和 "caption-side" 能用来设置标题的对齐方式和显示位置。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 不支持 align 属性。

HTML 4.01 [已废弃](NewWindow('deprecated.htm')) align 属性。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-caption-align.html) | left<br/>right<br/>top<br/>bottom | **HTML5 不支持。HTML 4.01 已废弃。** 定义标题的对齐方式。 |

--------

## 全局属性

&lt;caption&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;caption&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

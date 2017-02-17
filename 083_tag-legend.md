# HTML &lt;legend&gt; 标签

## 实例

组合表单中的相关元素：

```HTML
<form>
  <fieldset>
    <legend>Personalia:</legend>
    Name: <input type="text" size="30"><br>
    Email: <input type="text" size="30"><br>
    Date of birth: <input type="text" size="10">
  </fieldset>
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_fieldset)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;legend&gt; 标签。

--------

## 标签定义及使用说明

The &lt;legend&gt; 元素为 [&lt;fieldset&gt;](062_tag-fieldset.md)元素定义标题。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 4.01中 "align" 属性已被废弃, HTML5不支持该属性。不建议使用。 请使用 CSS 来设置 &lt;legend&gt; 元素的对齐方式。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-legend-align.html) | top<br/>bottom<br/>left<br/>right | **HTML5 不支持。 HTML 4.01 已废弃。** 不建议使用。 请使用样式代替。 为 fieldset 中的标题定义对齐方式。 |

--------

## 全局属性

&lt;legend&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;legend&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

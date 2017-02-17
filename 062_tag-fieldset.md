# HTML &lt;fieldset&gt; 标签

## 实例

对表单中的相关元素进行分组：

```HTML
<form>
  <fieldset>
    <legend>Personalia:</legend>
    Name: <input type="text"><br>
    Email: <input type="text"><br>
    Date of birth: <input type="text">
  </fieldset>
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_fieldset)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;fieldset&gt; 标签。

--------

## 标签定义及使用说明

&lt;fieldset&gt; 标签可以将表单内的相关元素分组。

&lt;fieldset&gt; 标签会在相关表单元素周围绘制边框。

--------

## 提示和注释

**提示：** [&lt;legend&gt;](083_tag-legend.md) 标签为 &lt;fieldset&gt; 元素定义标题。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中新增了一些 &lt;fieldset&gt; 的新属性：disabled、form、name，HTML 4.01 中不支持这些属性。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [disabled](att-fieldset-disabled.html) (New) | disabled | 规定该组中的相关表单元素应该被禁用。 |
| [form](att-fieldset-form.html) (New) | _form_id_ | 规定 fieldset 所属的一个或多个表单。 |
| [name](att-fieldset-name.html) (New) | _text_ | 规定 fieldset 的名称。 |

--------

## 全局属性

&lt;fieldset&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;fieldset&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

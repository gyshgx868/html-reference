# HTML &lt;label&gt; 标签

## 实例

带有两个输入字段和相关标记的简单 HTML 表单：

```HTML
<form action="demo_form.asp">
  <label for="male">Male</label>
  <input type="radio" name="sex" id="male" value="male"><br>
  <label for="female">Female</label>
  <input type="radio" name="sex" id="female" value="female"><br>
  <input type="submit" value="提交">
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_label)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;label&gt; 标签。

--------

## 标签定义及使用说明

&lt;label&gt; 标签为 input 元素定义标注（标记）。

label 元素不会向用户呈现任何特殊效果。不过，它为鼠标用户改进了可用性。如果您在 label 元素内点击文本，就会触发此控件。就是说，当用户选择该标签时，浏览器就会自动将焦点转到和标签相关的表单控件上。

&lt;label&gt; 标签的 for 属性应当与相关元素的 id 属性相同。

--------

## 提示和注释

**提示:** "for" 属性可把 label 绑定到另外一个元素。请把 "for" 属性的值设置为相关元素的 id 属性的值。

--------

## HTML 4.01 与 HTML5之间的差异

"form" 属性是 HTML5 的新属性。

--------

## 属性

(New)：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [for](att-label-for.html) | _element_id_ | 规定 label 与哪个表单元素绑定。 |
| [form](att-label-form.html) (New) | _form_id_ | 规定 label 字段所属的一个或多个表单。 |

--------

## 全局属性

&lt;label&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;label&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

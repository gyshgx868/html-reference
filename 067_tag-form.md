# HTML &lt;form&gt; 标签

## 实例

带有两个输入字段和一个提交按钮的 HTML 表单：

```HTML
<form action="demo_form.php" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <input type="submit" value="提交">
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_form_submit)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;form&gt; 标签。

--------

## 标签定义及使用说明

&lt;form&gt; 标签用于创建供用户输入的 HTML 表单。

&lt;form&gt; 元素包含一个或多个如下的表单元素：

 * [&lt;input&gt;](078_tag-input.md)
 * [&lt;textarea&gt;](125_tag-textarea.md)
 * [&lt;button&gt;](041_tag-button.md)
 * [&lt;select&gt;](112_tag-select.md)
 * [&lt;option&gt;](097_tag-option.md)
 * [&lt;optgroup&gt;](096_tag-optgroup.md)
 * [&lt;fieldset&gt;](062_tag-fieldset.md)
 * [&lt;label&gt;](082_tag-label.md)

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 新增了两个新的属性：autocomplete 和 novalidate，同时不再支持 HTML 4.01 中的某些属性。

--------

## HTML 与 XHTML 之间的差异

在 XHTML 中，name 属性已被废弃。使用全局 id 属性代替。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [accept](att-form-accept.html) | _MIME_type_ | HTML5 不支持。规定服务器接收到的文件的类型。（文件是通过文件上传提交的） |
| [accept-charset](att-form-accept-charset.html) | _character_set_ | 规定服务器可处理的表单数据字符集。 |
| [action](att-form-action.html) | _URL_ | 规定当提交表单时向何处发送表单数据。 |
| [autocomplete](att-form-autocomplete.html) (New) | on<br/>off | 规定是否启用表单的自动完成功能。 |
| [enctype](att-form-enctype.html) | application/x-www-form-urlencoded<br/>multipart/form-data<br/>text/plain | 规定在向服务器发送表单数据之前如何对其进行编码。（适用于 method="post" 的情况） |
| [method](att-form-method.html) | get<br/>post | 规定用于发送表单数据的 HTTP 方法。 |
| [name](att-form-name.html) | _text_ | 规定表单的名称。 |
| [novalidate](att-form-novalidate.html) (New) | novalidate | 如果使用该属性，则提交表单时不进行验证。 |
| [target](att-form-target.html) | _blank<br/>_self<br/>_parent<br/>_top | 规定在何处打开 action URL。 |

--------

## 全局属性

&lt;form&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;form&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[带有复选框的表单](http://www.runoob.com/try/try.php?filename=tryhtml_form_checkbox)

 此表单包含两个复选框和一个提交按钮。

[带有单选按钮的表单](http://www.runoob.com/try/try.php?filename=tryhtml_form_radio)

 此表单包含两个单选框和一个提交按钮。

--------

## 相关文章

HTML 教程：[HTML 表单和输入](html-forms.html)

HTML DOM 参考手册： [Form 对象](http://www.runoob.com/jsref/dom-obj-form.html)

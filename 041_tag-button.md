# HTML &lt;button&gt; 标签

## 实例

以下代码标记一个按钮：

```HTML
<button type="button">点我!</button> 
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_button_test)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;button&gt; 标签。

--------

## 标签定义及使用说明

&lt;button&gt; 标签定义一个按钮。

在 &lt;button&gt; 元素内部，您可以放置内容，比如文本或图像。这是该元素与使用 &lt;input&gt; 元素创建的按钮之间的不同之处。

**提示：** 请始终为 &lt;button&gt; 元素规定 type 属性。不同的浏览器对 &lt;button&gt; 元素的 type 属性使用不同的默认值。

--------

## 提示和注释

**注释：** 如果在 HTML 表单中使用 &lt;button&gt; 元素，不同的浏览器可能会提交不同的按钮值。请使用 [&lt;input&gt;](078_tag-input.md) 在 HTML 表单中创建按钮。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中的新属性：autofocus、form、formaction、formenctype、formmethod、formnovalidate 以及 formtarget。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autofocus](att-button-autofocus.html) (New) | autofocus | 规定当页面加载时按钮应当自动地获得焦点。 |
| [disabled](att-button-disabled.html) | disabled | 规定应该禁用该按钮。 |
| [form](att-button-form.html) (New) | _form_id_ | 规定按钮属于一个或多个表单。 |
| [formaction](att-button-formaction.html) (New) | _URL_ | 规定当提交表单时向何处发送表单数据。覆盖 form 元素的 action 属性。该属性与 type="submit" 配合使用。 |
| [formenctype](att-button-formenctype.html) (New) | application/x-www-form-urlencoded<br/>multipart/form-data<br/>text/plain | 规定在向服务器发送表单数据之前如何对其进行编码。覆盖 form 元素的 enctype 属性。该属性与 type="submit" 配合使用。 |
| [formmethod](att-button-formmethod.html) (New) | get<br/>post | 规定用于发送表单数据的 HTTP 方法。覆盖 form 元素的 method 属性。该属性与 type="submit" 配合使用。 |
| [formnovalidate](att-button-formnovalidate.html) (New) | formnovalidate | 如果使用该属性，则提交表单时不进行验证。覆盖 form 元素的 novalidate 属性。该属性与 type="submit" 配合使用。 |
| [formtarget](att-button-formtarget.html) (New) | _blank</br>_self<br/>_parent<br/>_top<br/>_framename_ | 规定在何处打开 action URL。覆盖 form 元素的 target 属性。该属性与 type="submit" 配合使用。 |
| [name](att-button-name.html) | _name_ | 规定按钮的名称。 |
| [type](att-button-type.html) | button<br/>reset<br/>submit | 规定按钮的类型。 |
| [value](att-button-value.html) | _text_ | 规定按钮的初始值。可由脚本进行修改。 |

--------

## 全局属性

&lt;button&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;button&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML DOM 参考手册： [Button 对象](http://www.runoob.com/jsref/dom-obj-pushbutton.html)

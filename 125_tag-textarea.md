# HTML &lt;textarea&gt; 标签

## 实例

一个 HTML 文本区域：

```HTML
<textarea rows="10" cols="30">
我是一个文本框。 
</textarea>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_textarea)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;textarea&gt; 标签。

--------

## 标签定义及使用说明

&lt;textarea&gt; 标签定义一个多行的文本输入控件。

文本区域中可容纳无限数量的文本，其中的文本的默认字体是等宽字体（通常是 Courier）。

可以通过 cols 和 rows 属性来规定 textarea 的尺寸大小，不过更好的办法是使用 CSS 的 height 和 width 属性。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 增加了一些新的属性。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autofocus](att-textarea-autofocus.html) (New) | autofocus | 规定当页面加载时，文本区域自动获得焦点。 |
| [cols](att-textarea-cols.html) | _number_ | 规定文本区域内可见的列数。 |
| [disabled](att-textarea-disabled.html) | disabled | 规定禁用文本区域。 |
| [form](att-textarea-form.html) (New) | _form_id_ | 定义文本区域所属的一个或多个表单。 |
| [maxlength](att-textarea-maxlength.html) (New) | _number_ | 规定文本区域允许的最大字符数。 |
| [name](att-textarea-name.html) | _text_ | 规定文本区域的名称。 |
| [placeholder](att-textarea-placeholder.html) (New) | _text_ | 规定一个简短的提示，描述文本区域期望的输入值。 |
| [readonly](att-textarea-readonly.html) | readonly | 规定文本区域为只读。 |
| [required](att-textarea-required.html) (New) | required | 规定文本区域是必需的/必填的。 |
| [rows](att-textarea-rows.html) | _number_ | 规定文本区域内可见的行数。 |
| [wrap](att-textarea-wrap.html) (New) | hard

 soft | 规定当提交表单时，文本区域中的文本应该怎样换行。 |

--------

## 全局属性

&lt;textarea&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;textarea&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML DOM 参考手册：[Textarea 对象](http://www.runoob.com/jsref/dom-obj-textarea.html)

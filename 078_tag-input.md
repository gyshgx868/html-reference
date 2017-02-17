# HTML &lt;input&gt; 标签

## 实例

一个简单的 HTML 表单，包含两个文本输入框和一个提交按钮：

```HTML
<form action="demo_form.asp">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <input type="submit" value="提交">
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_form_submit)

(本页底部可以查看更多实例)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;input&gt;标签。

--------

## 标签定义及使用说明

&lt;input&gt; 标签规定了用户可以在其中输入数据的输入字段。

&lt;input&gt; 元素在 &lt;form&gt; 元素中使用，用来声明允许用户输入数据的 input 控件。

输入字段可通过多种方式改变，取决于 type 属性。

--------

## 提示和注释

**注意:** &lt;input&gt; 元素是空的,它只包含标签属性。

**提示:**  你可以使用 [&lt;label&gt;](082_tag-label.md) 元素来定义 &lt;input&gt; 元素的标注。

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 4.01 中, "align" 数据已经不再使用。HTML5 中不支持该属性。 可以使用CSS来定义 &lt;input&gt; 元素的对齐方式。

在 HTML5中, &lt;input&gt; 添加了几个属性，并且添加了对应的值。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;input&gt; 标签没有结束标签。

在 XHTML 中，&lt;input&gt; 标签必须被正确地关闭。

--------

## 属性

New: HTML5新标签。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [accept](att-input-accept.html) | audio/* video/* image/*  _MIME_type_ | 规定通过文件上传来提交的文件的类型。 (只针对type="file") |
| [align](att-input-align.html) | left right top middle bottom | **HTML5已废弃，不赞成使用。规定图像输入的对齐方式。 (只针对type="image")** |
| [alt](att-input-alt.html) | _text_ | 定义图像输入的替代文本。 (只针对type="image") |
| [autocomplete](att-input-autocomplete.html) (New) | on off | autocomplete 属性规定 &lt;input&gt; 元素输入字段是否应该启用自动完成功能。 |
| [autofocus](att-input-autofocus.html) (New) | autofocus | 属性规定当页面加载时 &lt;input&gt; 元素应该自动获得焦点。 |
| [checked](att-input-checked.html) | checked | checked 属性规定在页面加载时应该被预先选定的 &lt;input&gt; 元素。 (只针对 type="checkbox" 或者 type="radio") |
| [disabled](att-input-disabled.html) | disabled | disabled 属性规定应该禁用的 &lt;input&gt; 元素。 |
| [form](att-input-form.html) (New) | _form_id_ | form 属性规定 &lt;input&gt; 元素所属的一个或多个表单。 |
| [formaction](att-input-formaction.html) (New) | _URL_ | 属性规定当表单提交时处理输入控件的文件的 URL。(只针对 type="submit" 和 type="image") |
| [formenctype](att-input-formenctype.html) (New) | application/x-www-form-urlencoded<br/>multipart/form-data text/plain | 属性规定当表单数据提交到服务器时如何编码(只适合 type="submit" 和 type="image")。 |
| [formmethod](att-input-formmethod.html) (New) | get post | 定义发送表单数据到 action URL 的 HTTP 方法。 (只适合 type="submit" 和 type="image") |
| [formnovalidate](att-input-formnovalidate.html) (New) | formnovalidate | formnovalidate 属性覆盖 &lt;form&gt; 元素的 novalidate 属性。 |
| [formtarget](att-input-formtarget.html) (New) | _blank _self _parent _top  _framename_ | 规定表示提交表单后在哪里显示接收到响应的名称或关键词。(只适合 type="submit" 和 type="image") |
| [height](att-input-height.html) (New) | _pixels_ | 规定 &lt;input&gt;元素的高度。(只针对type="image") |
| [list](att-input-list.html) (New) | _datalist_id_ | 属性引用 &lt;datalist&gt; 元素，其中包含 &lt;input&gt; 元素的预定义选项。 |
| [max](att-input-max.html) (New) | _number date_ | 属性规定 &lt;input&gt; 元素的最大值。 |
| [maxlength](att-input-maxlength.html) | _number_ | 属性规定 &lt;input&gt; 元素中允许的最大字符数。 |
| [min](att-input-min.html) (New) | _number date_ | 属性规定 &lt;input&gt;元素的最小值。 |
| [multiple](att-input-multiple.html) (New) | multiple | 属性规定允许用户输入到 &lt;input&gt; 元素的多个值。 |
| [name](att-input-name.html) | _text_ | name 属性规定 &lt;input&gt; 元素的名称。 |
| [pattern](att-input-pattern.html) (New) | _regexp_ | pattern 属性规定用于验证 &lt;input&gt; 元素的值的正则表达式。 |
| [placeholder](att-input-placeholder.html) (New) | _text_ | placeholder 属性规定可描述输入 &lt;input&gt; 字段预期值的简短的提示信息 。 |
| [readonly](att-input-readonly.html) | readonly | readonly 属性规定输入字段是只读的。 |
| [required](att-input-required.html) (New) | required | 属性规定必需在提交表单之前填写输入字段。 |
| [size](att-input-size.html) | _number_ | size 属性规定以字符数计的 &lt;input&gt; 元素的可见宽度。 |
| [src](att-input-src.html) | _URL_ | src 属性规定显示为提交按钮的图像的 URL。 (只针对 type="image") |
| [step](att-input-step.html) (New) | _number_ | step 属性规定 &lt;input&gt; 元素的合法数字间隔。 |
| [type](att-input-type.html) | button<br/>checkbox<br/>color<br/>date<br/>datetime<br/>datetime-local<br/>email<br/>file<br/>hidden<br/>image<br/>month<br/>number<br/>password<br/>radio<br/>range<br/>reset<br/>search<br/>submit<br/>tel<br/>text<br/>time<br/>url<br/>week | type 属性规定要显示的 &lt;input&gt; 元素的类型。 |
| [value](att-input-value.html) | _text_ | 指定 &lt;input&gt; 元素 value 的值。 |
| [width](att-input-width.html) (New) | _pixels_ | width 属性规定 &lt;input&gt; 元素的宽度。 (只针对type="image") |

--------

## 全局属性

&lt;input&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;input&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

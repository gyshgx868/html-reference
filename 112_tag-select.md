# HTML &lt;select&gt; 标签

## 实例

创建带有 4 个选项的选择列表：

```HTML
<select>
<option value="volvo">Volvo</option>
<option value="saab">Saab</option>
<option value="mercedes">Mercedes</option>
<option value="audi">Audi</option>
</select>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_select)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;select&gt; 标签。

--------

## 标签定义及使用说明

&lt;select&gt; 元素用来创建下拉列表。

&lt;select&gt; 元素中的 [&lt;option&gt;](097_tag-option.md) 标签定义了列表中的可用选项。

--------

## 提示和注释

**提示：** &lt;select&gt; 元素是一种表单控件，可用于在表单中接受用户输入。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 增加了一些新的属性。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autofocus](att-select-autofocus.html) (New) | autofocus | 规定在页面加载时下拉列表自动获得焦点。 |
| [disabled](att-select-disabled.html) | disabled | 当该属性为 true 时，会禁用下拉列表。 |
| [form](att-select-form.html) (New) | _form_id_ | 定义 select 字段所属的一个或多个表单。 |
| [multiple](att-select-multiple.html) | multiple | 当该属性为 true 时，可选择多个选项。 |
| [name](att-select-name.html) | _name_ | 定义下拉列表的名称。 |
| [required](att-select-required.html) (New) | required | 规定用户在提交表单前必须选择一个下拉列表中的选项。 |
| [size](att-select-size.html) | _number_ | 规定下拉列表中可见选项的数目。 |

--------

## 全局属性

&lt;select&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;select&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML DOM 参考手册： [Select 对象](http://www.runoob.com/jsref/dom-obj-select.html)

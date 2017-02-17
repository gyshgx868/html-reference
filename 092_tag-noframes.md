# HTML &lt;noframes&gt; 标签HTML5不支持该标签

## 实例

显示三个frame框架，如果不支持frame输出 &lt;noframes&gt; 标签的文本：

```HTML
<html>

<frameset cols="25%,50%,25%">
  <frame src="frame_a.htm">
  <frame src="frame_b.htm">
  <frame src="frame_c.htm">
  <noframes>Sorry, your browser does not handle frames!</noframes>
</frameset>

</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_noframes)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;noframes&gt; 标签。

--------

## 标签定义及使用说明

HTML5 不支持 &lt;noframes&gt; 标签。

&lt;noframes&gt; 元素可为那些不支持框架的浏览器显示文本。noframes 元素位于 frameset 元素内部。

&lt;noframes&gt; 元素插入在 &lt;frameset&gt; 元素中使用。

**注意：**  如果您希望验证包含框架的页面，请确保 DTD 被设置为 "Frameset DTD"。

--------

## HTML 4.01 与 HTML5 的差异

HTML5不支持 &lt;noframes&gt; 标签，HTML 4.01 支持该标签。

--------

## HTML 与 XHTML 的差异

**重要：**  在 XHTML Frameset DTD，位于 &lt;noframes&gt; 元素中的文本信息必须有关闭标签。

--------

## 标准属性

在 HTML 4.01 中，&lt;noframes&gt; 支持如下标准属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| class | _classname_ | 规定元素的类名 |
| dir | rtl<br/>ltr | 规定元素中内容的文本方向 |
| id | _id_ | 规定元素的唯一 id |
| lang | _language_code_ | 规定元素中内容的语言代码 |
| style | _style_definition_ | 规定元素的行内样式 |
| title | _text_ | 规定元素的额外信息 |
| xml:lang | _language_code_ | 规定 XHTML 文档中元素内容的语言代码 |

如需完整的描述，请访问[标准属性](003_ref-standardattributes.md)。

--------

## 事件属性

在 HTML 4.01 中，&lt;noframes&gt; 标签支持如下事件属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| onclick | _script_ | 当鼠标被单击时执行脚本 |
| ondblclick | _script_ | 当鼠标被双击时执行脚本 |
| onmousedown | _script_ | 当鼠标按钮被按下时执行脚本 |
| onmousemove | _script_ | 当鼠标指针移动时执行脚本 |
| onmouseout | _script_ | 当鼠标指针移出某元素时执行脚本 |
| onmouseover | _script_ | 当鼠标指针悬停于某元素之上时执行脚本 |
| onmouseup | _script_ | 当鼠标按钮被松开时执行脚本 |
| onkeydown | _script_ | 当键盘被按下时执行脚本 |
| onkeypress | _script_ | 当键盘被按下后又松开时执行脚本 |
| onkeyup | _script_ | 当键盘被松开时执行脚本 |

如需完整的描述，请访问[事件属性](004_ref-eventattributes.md)。

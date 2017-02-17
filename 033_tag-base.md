# HTML &lt;base&gt; 标签

## 实例

规定页面上所有链接的默认 URL 和默认目标：

```HTML
<head>
<base href="http://www.runoob.com/images/" target="_blank">
</head>

<body>
<img src="logo.png" width="24" height="39" alt="Stickman">
<a href="http://www.runoob.com">runoob.com</a>
</body>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_base_test)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;base&gt; 标签。

--------

## 标签定义及使用说明

&lt;base&gt; 标签为页面上的所有的相对链接规定默认 URL 或默认目标。

在一个文档中，最多能使用一个 &lt;base&gt; 元素。&lt;base&gt; 标签必须位于 &lt;head&gt; 元素内部。

--------

## 提示和注释

**提示：** 请把 &lt;base&gt; 标签排在 &lt;head&gt; 元素中 _第一个_ 元素的位置，这样 head 区域中其他元素就可以使用 &lt;base&gt; 元素中的信息了。

**注释：** 如果使用了 &lt;base&gt; 标签，则必须具备 href 属性或者 target 属性或者两个属性都具备。

--------

## HTML 4.01 与 HTML5之间的差异

无。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;base&gt; 标签没有结束标签。

在 XHTML 中，&lt;base&gt; 标签必须被正确地关闭。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [href](att-base-href.html) | _URL_ | 规定页面中所有相对链接的基准 URL。 |
| [target](att-base-target.html) | _blank<br/>_parent<br/>_self<br/>_top<br/>_framename_ | 规定页面中所有的超链接和表单在何处打开。该属性会被每个链接中的 target 属性覆盖。 |

--------

## 全局属性

&lt;base&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;base&gt; 标签不支持任何的事件属性。

--------

## 相关文章

HTML DOM 参考手册： [Base 对象](http://www.runoob.com/jsref/dom-obj-base.html)

# HTML &lt;datalist&gt; 标签

## 实例

下面是一个 &lt;input&gt; 元素，&lt;datalist&gt; 中描述了其可能的值：

```HTML
<input list="browsers">
 
<datalist id="browsers">
  <option value="Internet Explorer">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_datalist)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/incompatible_safari.gif)

IE 10、Firefox、Opera 和 Chrome 支持 &lt;datalist&gt; 标签。

**注释：** IE 9 和更早版本的 IE 浏览器 以及 Safari 不支持 &lt;datalist&gt; 标签。

--------

## 标签定义及使用说明

&lt;datalist&gt; 标签规定了 &lt;input&gt; 元素可能的选项列表。

&lt;datalist&gt; 标签被用来在为 &lt;input&gt; 元素提供"自动完成"的特性。用户能看到一个下拉列表，里边的选项是预先定义好的，将作为用户的输入数据。

请使用 &lt;input&gt; 元素的 list 属性来绑定 &lt;datalist&gt; 元素。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;datalist&gt; 标签是 HTML5 中的新标签。

--------

## 全局属性

&lt;datalist&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;datalist&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

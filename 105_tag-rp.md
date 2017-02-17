# HTML &lt;rp&gt; 标签

## 实例

一个 ruby 注释：

```HTML
<ruby>
漢 <rt><rp>(</rp>ㄏㄢˋ<rp>)</rp></rt>
</ruby>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_rp)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 9+、Firefox、Opera、Chrome 和 Safari 支持 &lt;rp&gt; 标签。

**注释：** IE 8 或更早版本的 IE 浏览器不支持 &lt;rp&gt; 标签。

--------

## 标签定义及使用说明

&lt;rp&gt; 标签在 ruby 注释中使用，以定义不支持 ruby 元素的浏览器所显示的内容。

ruby 注释是中文注音或字符。在东亚使用，显示的是东亚字符的发音。

将 &lt;rp&gt; 标签与 [&lt;ruby&gt;](107_tag-ruby.md) 和 [&lt;rt&gt;](106_tag-rt.md) 标签一起使用： 

 &lt;ruby&gt; 元素由一个或多个需要解释/发音的字符和一个提供该信息的 &lt;rt&gt; 元素组成，还包括可选的 &lt;rp&gt; 元素，定义当浏览器不支持 &quot;ruby&quot; 元素时显示的内容。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;rp&gt; 标签是 HTML5 中的新标签。

--------

## 全局属性

&lt;rp&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;rp&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

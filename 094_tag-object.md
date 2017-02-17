# HTML &lt;object&gt; 标签

## 实例

使用&lt;object&gt; 元素在 HTML 加入 Flash 文件：

```HTML
<object width="400" height="400" data="helloworld.swf"></object>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_object)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;object&gt; 标签。

--------

## 标签定义及使用说明

定义一个嵌入的对象。请使用此元素向您的 XHTML 页面添加多媒体。此元素允许您规定插入 HTML 文档中的对象的数据和参数，以及可用来显示和操作数据的代码。

&lt;object&gt; 标签用于包含对象，比如图像、音频、视频、Java applets、ActiveX、PDF 以及 Flash。

object 的初衷是取代 img 和 applet 元素。不过由于漏洞以及缺乏浏览器支持，这一点并未实现。

浏览器的对象支持有赖于对象类型。不幸的是，主流浏览器都使用不同的代码来加载相同的对象类型。

而幸运的是，object 对象提供了解决方案。如果未显示 object 元素，就会执行位于 &lt;object&gt; 和 &lt;/object&gt; 之间的代码。通过这种方式，我们能够嵌套多个 object 元素（每个对应一个浏览器）。

--------

## HTML 4.01 与 HTML5中的差异

一些 HTML 4.01 属性在 HTML5 中不被支持。

"form" 是 HTML5 定义的新属性。

在 HTML5 中，objects 可以在form表单中提交。

在 HTML5 中，objects 不再出现在 &lt;head&gt; 元素区域内。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-object-align.html) | top bottom middle left right | HTML5 不支持。HTML 4.01 已废弃。 规定 &lt;object&gt; 元素相对于周围元素的对齐方式。 |
| archive | _URL_ | HTML5 不支持。由空格分隔的指向档案文件的 URL 列表。这些档案文件包含了与对象相关的资源。 |
| [border](att-object-border.html) | _pixels_ | HTML5 不支持。HTML 4.01 已废弃。 规定 &lt;object&gt; 周围的边框宽度。 |
| classid | _class_ID_ | HTML5 不支持。定义嵌入 Windows Registry 中或某个 URL 中的类的 ID 值，此属性可用来指定浏览器中包含的对象的位置，通常是一个 Java 类。 |
| codebase | _URL_ | HTML5 不支持。定义在何处可找到对象所需的代码，提供一个基准 URL。 |
| codetype | _MIME_type_ | HTML5 不支持。通过 classid 属性所引用的代码的 MIME 类型。 |
| [data](att-object-data.html) | _URL_ | 规定对象使用的资源的 URL。 |
| declare | declare | HTML5 不支持。定义该对象仅可被声明，但不能被创建或例示，直到该对象得到应用为止。 |
| [form](att-object-form.html) (New) | _form_id_ | 规定对象所属的一个或多个表单。 |
| [height](att-object-height.html) | _pixels_ | 规定对象的高度。 |
| [hspace](att-object-hspace.html) | _pixels_ | HTML5 不支持。HTML 4.01 已废弃。 规定对象左侧和右侧的空白。 |
| [name](att-object-name.html) | _name_ | 为对象规定名称。 |
| standby | _text_ | HTML5 不支持。定义当对象正在加载时所显示的文本。 |
| [type](att-object-type.html) | _MIME_type_ | 规定 data 属性中规定的数据的 MIME 类型。 |
| [usemap](att-object-usemap.html) | _#mapname_ | 规定与对象一同使用的客户端图像映射的名称。 |
| [vspace](att-object-vspace.html) | _pixels_ | HTML5 不支持。HTML 4.01 已废弃。 规定对象的顶部和底部的空白。 |
| [width](att-object-width.html) | _pixels_ | 规定对象的宽度。 |

--------

## 全局属性

&lt;p&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;p&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML Object 元素](http://www.runoob.com/html/html-object.html)

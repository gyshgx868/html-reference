# HTML &lt;img&gt; 标签

## 实例

如何插入图像：

```HTML
<img src="smiley-2.gif" alt="Smiley face" width="42" height="42">
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_image_test)

（更多实例见页面底部）

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;img&gt; 标签。

--------

## 标签定义及使用说明

&lt;img&gt; 标签定义 HTML 页面中的图像。

&lt;img&gt; 标签有两个必需的属性：src 和 alt。

**注释：** 从技术上讲，图像并不会插入 HTML 页面中，而是链接到 HTML 页面上。&lt;img&gt; 标签的作用是为被引用的图像创建占位符。

**提示：** 通过在 &lt;a&gt; 标签中嵌套 &lt;img&gt; 标签，给图像添加到另一个文档的链接。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 中不支持以下属性：align、border、hspace、longdesc、vspace。

在 HTML 4.01 中，以下属性：align、border、hspace、vspace [已废弃](javascript:NewWindow('/try/deprecated.htm'))。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;img&gt; 标签没有结束标签。

在 XHTML 中，&lt;img&gt; 标签必须被正确地关闭。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [align](att-img-align.html) | top<br/>bottom<br/>middle<br/>left<br/>right | **HTML5 不支持。HTML 4.01 已废弃。** 规定如何根据周围的文本来排列图像。 |
| [alt](att-img-alt.html) | _text_ | 规定图像的替代文本。 |
| [border](att-img-border.html) | _pixels_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定图像周围的边框。 |
| crossorigin (New) | anonymous<br/>use-credentials | 设置图像的跨域属性 |
| [height](att-img-height.html) | _pixels_ | 规定图像的高度。 |
| [hspace](att-img-hspace.html) | _pixels_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定图像左侧和右侧的空白。 |
| [ismap](att-img-ismap.html) | ismap | 将图像规定为服务器端图像映射。 |
| [longdesc](att-img-longdesc.html) | _URL_ | **HTML5 不支持。HTML 4.01 已废弃。** 指向包含长的图像描述文档的 URL。 |
| [src](att-img-src.html) | _URL_ | 规定显示图像的 URL。 |
| [usemap](att-img-usemap.html) | _#mapname_ | 将图像定义为客户器端图像映射。 |
| [vspace](att-img-vspace.html) | _pixels_ | **HTML5 不支持。HTML 4.01 已废弃。** 规定图像顶部和底部的空白。 |
| [width](att-img-width.html) | _pixels_ | 规定图像的宽度。 |

--------

## 全局属性

&lt;img&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;img&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[从不同的位置插入图片](http://www.runoob.com/try/try.php?filename=tryhtml_image_diffloc)

 本例演示如何将其他文件夹或服务器的图片显示到网页中。

[制作图像链接](http://www.runoob.com/try/try.php?filename=tryhtml_image_link)

 本例演示如何将图像作为一个链接使用。

[创建图像地图](http://www.runoob.com/try/try.php?filename=tryhtml_areamap)

 本例演示如何创建带有可供点击区域的图像地图。其中的每个区域都是一个超级链接。

--------

## 相关文章

HTML 教程：[HTML 图像](http://www.runoob.com/html/html-images.html)

HTML DOM 参考手册： [Image 对象](http://www.runoob.com/jsref/dom-obj-image.html)

# HTML &lt;area&gt; 标签

## 实例

带有可点击区域的图像映射：

```HTML
<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" alt="Sun" href="sun.htm">
  <area shape="circle" coords="90,58,3" alt="Mercury" href="mercur.htm">
  <area shape="circle" coords="124,58,8" alt="Venus" href="venus.htm">
</map>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_areamap)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;area&gt; 标签。

--------

## 标签定义及使用说明

&lt;area&gt; 标签定义图像映射内部的区域（图像映射指的是带有可点击区域的图像）。

&lt;area&gt; 元素始终嵌套在 &lt;map&gt; 标签内部。

**注释：** [&lt;img&gt;](077_tag-img.md) 标签中的 usemap 属性与 [&lt;map&gt;](086_tag-map.md) 元素中的 name 相关联，以创建图像与映射之间的关系。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 提供了一些新属性，同时不再支持 HTML 4.01 中的某些属性。

--------

## HTML 与 XHTML 之间的差异

在 HTML 中，&lt;area&gt; 标签没有结束标签。

在 XHTML 中，&lt;area&gt; 标签必须正确地关闭。

--------

## 属性

NEW：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [alt](att-area-alt.html) | _text_ | 规定区域的替代文本。如果使用 href 属性，则该属性是必需的。 |
| [coords](att-area-coords.html) | _coordinates_ | 规定区域的坐标。 |
| [href](att-area-href.html) | _URL_ | 规定区域的目标 URL。 |
| [hreflang](att-area-hreflang.html) (NEW) | _language_code_ | 规定目标 URL 的语言。 |
| [media](att-area-media.html) (NEW) | _media query_ | 规定目标 URL 是为何种媒介/设备优化的。默认：all。 |
| [nohref](att-area-nohref.html) | _value_ | HTML5 不支持。 规定没有相关链接的区域。 |
| [rel](att-area-rel.html) (NEW) | alternate<br/>author<br/>bookmark<br/>help<br/>license<br/>next<br/>nofollow<br/>noreferrer<br/>prefetch<br/>prev<br/>search<br/>tag | 规定当前文档与目标 URL 之间的关系。 |
| [shape](att-area-shape.html) | default<br/>rect<br/>circle<br/>poly | 规定区域的形状。 |
| [target](att-area-target.html) | _blank<br/>_parent<br/>_self<br/>_top<br/>_framename_ | 规定在何处打开目标 URL。 |
| [type](att-area-type.html) (NEW) | _MIME_type_ | 规定目标 URL 的 MIME 类型。<br/>注：MIME = Multipurpose Internet Mail Extensions。 |

## 全局属性

&lt;area&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;area&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML DOM 参考手册： [Area 对象](028_tag-area.md)

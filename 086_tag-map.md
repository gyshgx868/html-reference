# HTML &lt;map&gt; 标签

## 实例

带有可点击区域的图像映射：

```HTML
<img src="planets.gif" width="145" height="126" alt="Planets" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
  <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
  <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
</map>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_areamap)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;map&gt;标签。

--------

## 标签定义及使用说明

&lt;map&gt; 标签用于客户端图像映射。图像映射指带有可点击区域的一幅图像。

&lt;img&gt;中的 usemap 属性可引用 &lt;map&gt; 中的 id 或 name 属性（取决于浏览器），所以我们应同时向 &lt;map&gt; 添加 id 和 name 属性。

area 元素永远嵌套在 map 元素内部。area 元素可定义图像映射中的区域。

--------

## HTML 4.01 与 HTML5之间的差异

**注意:**  在 HTML5 中, 如果 id 属性在&lt;map&gt; 标签中指定, 则你必须同样指定 name 属性。

--------

## HTML 与 XHTML 之间的差异

在 XHTML 中，name 属性已经废弃，使用 id 属性替换它。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [name](att-map-name.html) | _mapname_ | 必需。为 image-map 规定的名称。 |

--------

## 全局属性

&lt;map&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;map&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

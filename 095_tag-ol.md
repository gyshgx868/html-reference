# HTML &lt;ol&gt; 标签

## 实例

2 个不同的有序列表实例：

```HTML
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_lists)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

目前大多数浏览器支持 &lt;ol&gt; 标签。

--------

## 标签定义及使用说明

&lt;ol&gt; 标签定义了一个有序列表. 列表排序以数字来显示。

使用[&lt;li&gt;](084_tag-li.md) 标签来定义列表选项。

--------

## 提示和注释

**提示：**  如果需要无序列表，请使用 [&lt;ul&gt;](135_tag-ul.md) 标签。

**提示：** 使用 CSS 来定义列表样式。

--------

## HTML 4.01 与 HTML5中的差异

在 HTML 4.01 中"start" 和 "type" 属性已经废弃，HTML5不支持该属性。

"reversed" 属性是 HTML5 中的新属性。

在HTML 4.01中"compact" 属性已经废弃,在 HTML5中不支持该属性。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [compact](att-ol-compact.html) | compact | **HTML5中不支持，不赞成使用。** 请使用样式取代它。 规定列表呈现的效果比正常情况更小巧。 |
| [reversed](att-ol-reversed.html)New | reversed | 指定列表倒序(9,8,7...) |
| [start](att-ol-start.html) | _number_ | HTML5不支持，不赞成使用。请使用样式取代它。 规定列表中的起始点。 |
| [type](att-ol-type.html) | 1<br/>A<br/>a<br/>I<br/>i | 规定列表的类型。不赞成使用。请使用样式代替。 |

--------

## 全局属性

&lt;ol&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;ol&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML 列表](http://www.runoob.com/html/html-lists.html)

# HTML &lt;meta&gt; 标签

## 实例

描述 HTML 文档的元数据：

```HTML
<head>
<meta name="description" content="免费在线教程">
<meta name="keywords" content="HTML,CSS,XML,JavaScript">
<meta name="author" content="runoob">
<meta charset="UTF-8">
</head>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_meta)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;meta&gt; 标签。

--------

## 标签定义及使用说明

元数据（Metadata）是数据的数据信息。

&lt;meta&gt; 标签提供了 HTML 文档的元数据。元数据不会显示在客户端，但是会被浏览器解析。

META元素通常用于指定网页的描述，关键词，文件的最后修改时间，作者及其他元数据。

元数据可以被使用浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他 Web 服务调用。

--------

## 提示和注释

**注意：** &lt;meta&gt; 标签通常位于 &lt;head&gt; 区域内。

**注意：**  元数据通常以 名称/值 对出现。

**注意：**  如果没有提供 name 属性，那么名称/值对中的名称会采用 http-equiv 属性的值。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 不支持 scheme 属性。

在 HTML5 中，有一个新的 charset 属性，它使字符集的定义更加容易：

 * HTML 4.01： &lt;meta http-equiv="content-type" content="text/html; charset=UTF-8"&gt;
 * HTML5： &lt;meta charset="UTF-8"&gt;

--------

## HTML 与 XHTML 之间的差异

在 HTML 中 &lt;meta&gt; 标签没有结束标签。

在 XHTML 中 &lt;meta&gt; 标签必须包含结束标签。

--------

## 实例

**实例 1 - 定义文档关键词，用于搜索引擎：**

```HTML
<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
```

**实例 2 - 定义web页面描述：**

```HTML
<meta name="description" content="Free Web tutorials on HTML and CSS">
```

**实例 3 - 定义页面作者：**

```HTML
<meta name="author" content="Hege Refsnes">
```

**实例 4 - 每30秒刷新页面：**

```HTML
<meta http-equiv="refresh" content="30">
```

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [charset](att-meta-charset.html) (New) | _character_set_ | 定义文档的字符编码。 |
| [content](att-meta-content.html) | _text_ | 定义与 http-equiv 或 name 属性相关的元信息。 |
| [http-equiv](att-meta-http-equiv.html) | content-type<br/>default-style<br/>refresh | 把 content 属性关联到 HTTP 头部。 |
| [name](att-meta-name.html) | application-name<br/>author<br/>description<br/>generator __ keywords | 把 content 属性关联到一个名称。 |
| [scheme](att-meta-scheme.html) | _format/URI_ | **HTML5不支持。** 定义用于翻译 content 属性值的格式。 |

--------

## 事件属性

&lt;p&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

--------

## 相关文章

HTML 教程：[HTML 头部](http://www.runoob.com/html/html-head.html)

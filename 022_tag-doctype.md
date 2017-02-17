# HTML &lt;!DOCTYPE&gt; 声明

## 实例

```HTML
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>文档标题</title>
</head>

<body>
文档内容......
</body>

</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_doctype)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;!DOCTYPE&gt; 声明。

--------

## 标签定义及使用说明

&lt;!DOCTYPE&gt; 声明位于文档中的最前面的位置，处于 &lt;html&gt; 标签之前。

&lt;!DOCTYPE&gt; 声明不是一个 HTML 标签；它是用来告知 Web 浏览器页面使用了哪种 HTML 版本。

在 HTML 4.01 中，&lt;!DOCTYPE&gt; 声明需引用 DTD （文档类型声明），因为 HTML 4.01 是基于 SGML （Standard Generalized Markup Language 标准通用标记语言）。DTD 指定了标记语言的规则，确保了浏览器能够正确的渲染内容。

HTML5 不是基于 SGML，因此不要求引用 DTD。

**提示：** 总是给您的 HTML 文档添加 &lt;!DOCTYPE&gt; 声明，确保浏览器能够预先知道文档类型。

--------

## HTML 4.01 与 HTML5之间的差异

HTML 4.01 规定了三种不同的 &lt;!DOCTYPE&gt; 声明，分别是：Strict、Transitional 和 Frameset。 HTML5 中仅规定了一种：

```HTML
<!DOCTYPE html>
```

--------

## HTML 元素和 Doctypes

参阅[HTML 元素与合法的 Doctype](007_html-elementsdoctypes.md)，看看每一个 HTML 元素都出现在哪一种 Doctype 中。

--------

## 提示和注释

**注释：** &lt;!DOCTYPE&gt; 标签没有结束标签。

**提示：** &lt;!DOCTYPE&gt; 声明不区分大小写。

**提示：** 使用 [W3C 的验证](http://www.runoob.com//validator.w3.org/) 检查您是否编写了一个带有正确 DTD 的合法的 HTML / XHTML 文档！

--------

## 常见的 DOCTYPE 声明

### HTML 5

```HTML
<!DOCTYPE html>
```

### HTML 4.01 Strict

这个 DTD 包含所有 HTML 元素和属性，但不包括表象或过时的元素（如 font ）。框架集是不允许的。

```HTML
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

### HTML 4.01 Transitional

这个 DTD 包含所有 HTML 元素和属性，包括表象或过时的元素（如 font ）。框架集是不允许的。

```HTML
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```

### HTML 4.01 Frameset

这个 DTD 与 HTML 4.01 Transitional 相同，但是允许使用框架集内容。

```HTML
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
"http://www.w3.org/TR/html4/frameset.dtd">
```

### XHTML 1.0 Strict

这个 DTD 包含所有 HTML 元素和属性，但不包括表象或过时的元素（如 font ）。框架集是不允许的。结构必须按标准格式的 XML 进行书写。

```HTML
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

### XHTML 1.0 Transitional

这个 DTD 包含所有 HTML 元素和属性，包括表象或过时的元素（如 font ）。框架集是不允许的。结构必须按标准格式的 XML 进行书写。

```HTML
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

### XHTML 1.0 Frameset

这个 DTD 与 XHTML 1.0 Transitional 相同，但是允许使用框架集内容。

```HTML
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
```

### XHTML 1.1

这个 DTD 与 XHTML 1.0 Strict 相同，但是允许您添加模块（例如为东亚语言提供 ruby 支持）。

```HTML
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
"http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

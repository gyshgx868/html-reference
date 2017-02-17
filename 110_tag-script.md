# HTML &lt;script&gt; 标签

## 实例

通过 JavaScript 输出 "Hello world"：

```HTML
<script>
document.write("Hello World!")
</script>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_script)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;script&gt; 标签。

--------

## 标签定义及使用说明

&lt;script&gt; 标签用于定义客户端脚本，比如 JavaScript。

&lt;script&gt; 元素既可包含脚本语句，也可以通过 "src" 属性指向外部脚本文件。

JavaScript 通常用于图像操作、表单验证以及动态内容更改。

--------

## 提示和注释

**注释：** 如果使用 "src" 属性，则 &lt;script&gt; 元素必须是空的。

**提示：** 请参阅 [&lt;noscript&gt;](093_tag-noscript.md) 元素，对于那些在浏览器中禁用脚本或者其浏览器不支持客户端脚本的用户来说，该元素非常有用。

**注释：**  有多种执行外部脚本的方法：

 * 如果 async=&quot;async&quot;：脚本相对于页面的其余部分异步地执行（当页面继续进行解析时，脚本将被执行）
 * 如果不使用 async 且 defer=&quot;defer&quot;：脚本将在页面完成解析时执行
 * 如果既不使用 async 也不使用 defer：在浏览器继续解析页面之前，立即读取并执行脚本

--------

## HTML 4.01 与 HTML5之间的差异

在 HTML 4 中，&quot;type&quot; 属性是必需的，但在 HTML5 中是可选的。

&quot;async&quot; 属性是 HTML5 中的新属性。

HTML5 中不再支持 HTML 4.01 中的某些属性：&quot;xml:space&quot;。

--------

## HTML 与 XHTML 之间的差异

在 XHTML 中，脚本中的内容类型声明为 #PCDATA（代替 CDATA），就是说会对实体进行解析。

这意味着，在 XHTML 中，应该编码所有特殊的字符，或者把所有内容嵌套在 CDATA 部分中：

```HTML
<script type="text/javascript">
//<![CDATA[
var i=10;
if (i<5)
  {
  // some code
  }
//]]>
</script>
```

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [async](att-script-async.html) (New) | async | 规定异步执行脚本（仅适用于外部脚本）。 |
| [charset](att-script-charset.html) | _charset_ | 规定在脚本中使用的字符编码（仅适用于外部脚本）。 |
| [defer](att-script-defer.html) | defer | 规定当页面已完成解析后，执行脚本（仅适用于外部脚本）。 |
| [src](att-script-src.html) | _URL_ | 规定外部脚本的 URL。 |
| [type](att-script-type.html) | _MIME-type_ | 规定脚本的 MIME 类型。 |
| xml:space | preserve | **HTML5 不支持。** 规定是否保留代码中的空白。 |

--------

## 全局属性

&lt;script&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 相关文章

HTML 教程：[HTML 脚本](http://www.runoob.com/html/html-scripts.html)

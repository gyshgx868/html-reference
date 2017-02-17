# HTML &lt;address&gt; 标签

## 实例

Example.com 的联系信息：

```HTML
<address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_address)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

所有主流浏览器都支持 &lt;address&gt; 标签。

--------

## 标签定义及使用说明

&lt;address&gt; 标签定义文档作者/所有者的联系信息。

如果 &lt;address&gt; 元素位于 &lt;body&gt; 元素内部，则它表示该文档作者/所有者的联系信息。

如果 &lt;address&gt; 元素位于 &lt;article&gt; 元素内部，则它表示该文章作者/所有者的联系信息。

&lt;address&gt; 元素的文本通常呈现为 _斜体_ 。大多数浏览器会在该元素的前后添加换行。

--------

## 提示和注释

**提示：** 不应该使用 &lt;address&gt; 标签来描述邮政地址，除非这些信息是联系信息的组成部分。

**提示：** &lt;address&gt; 元素通常被包含在 [&lt;footer&gt;](066_tag-footer.md) 元素的其他信息中。

--------

## HTML 4.01 与 HTML5之间的差异

HTML 4.01 不支持 &lt;article&gt; 标签，因此在 HTML 4.01 中 &lt;address&gt; 标签总是定义 _文档_ 的作者/所有者的联系信息。

--------

## 全局属性

&lt;address&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;address&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

# HTML5 &lt;progress&gt; 标签

## 实例

标记"下载进度"：

```HTML
<progress value="22" max="100"></progress> 
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_progress)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 10、Firefox、Opera、Chrome 和 Safari 6 支持 &lt;progress&gt; 标签。

**注释：** IE 9 或者更早版本的 IE 浏览器不支持 &lt;progress&gt; 标签。

--------

## 标签定义及使用说明

&lt;progress&gt; 标签定义运行中的任务进度（进程）。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;progress&gt; 标签是 HTML5 中的新标签。

--------

## 提示和注释

**提示：** 请将 &lt;progress&gt; 标签与 JavaScript 一起使用来显示任务的进度。

**注释：** &lt;progress&gt; 标签不适合用来表示度量衡（例如，磁盘空间使用情况或相关的查询结果）。表示度量衡，请使用 [&lt;meter&gt;](090_tag-meter.md) 标签代替。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [max](att-progress-max.html) (New) | _number_ | 规定需要完成的值。 |
| [value](att-progress-value.html) (New) | _number_ | 规定进程的当前值。 |

## 全局属性

&lt;progress&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;progress&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

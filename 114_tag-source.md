# HTML &lt;source&gt; 标签

## 实例

带有两个源文件的音频播放器。浏览器需要选择它所支持的源文件（如果都支持则任选一个）：

```HTML
<audio controls>
<source src="horse.ogg" type="audio/ogg">
<source src="horse.mp3" type="audio/mpeg">
您的浏览器不支持 audio 元素。
</audio>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_source_src)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 9+、Firefox、Opera、Chrome 和 Safari 都支持 &lt;source&gt; 标签。

**注释：** IE 8 或更早版本的 IE 浏览器都不支持 &lt;source&gt; 标签。

--------

## 标签定义及使用说明

&lt;source&gt; 标签为媒体元素（比如 &lt;video&gt; 和 &lt;audio&gt;）定义媒体资源。

&lt;source&gt; 标签允许您规定两个视频/音频文件共浏览器根据它对媒体类型或者编解码器的支持进行选择。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;source&gt; 标签是 HTML5 中的新标签。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [media](att-source-media.html) (New) | _media_query_ | 规定媒体资源的类型，供浏览器决定是否下载。 |
| [src](att-source-src.html) (New) | _URL_ | 规定媒体文件的 URL。 |
| [type](att-source-type.html) (New) | _MIME_type_ | 规定媒体资源的 MIME 类型。 |

## 全局属性

&lt;source&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;source&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

# HTML &lt;track&gt; 标签

## 实例

带有两个字幕轨道的视频：

```HTML
<video width="320" height="240" controls>
<source src="forrest_gump.mp4" type="video/mp4">
<source src="forrest_gump.ogg" type="video/ogg">
<track src="subtitles_en.vtt" kind="subtitles" srclang="en"
label="English">
<track src="subtitles_no.vtt" kind="subtitles" srclang="no"
label="Norwegian">
</video>
```

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/incompatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/incompatible_safari.gif)

IE 10、Opera 和 Chrome 浏览器支持 &lt;track&gt; 标签。

--------

## 标签定义及使用说明

&lt;track&gt; 标签为媒体元素（比如 &lt;audio&gt; and &lt;video&gt;）规定外部文本轨道。

这个元素用于规定字幕文件或其他包含文本的文件，当媒体播放时，这些文件是可见的。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;track&gt; 标签是 HTML5 中的新标签。

--------

## 可选的属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [default](att-track-default.html) (New) | default | 规定该轨道是默认的。如果用户没有选择任何轨道，则使用默认轨道。 |
| [kind](att-track-kind.html) (New) | captions<br/>chapters<br/>descriptions<br/>metadata<br/>subtitles | 规定文本轨道的文本类型。 |
| [label](att-track-label.html) (New) | _text_ | 规定文本轨道的标签和标题。 |
| [src](att-track-src.html) (New) | _URL_ | 必需的。规定轨道文件的 URL。 |
| [srclang](att-track-srclang.html) (New) | _language_code_ | 规定轨道文本数据的语言。如果 kind 属性值是 "subtitles"，则该属性是必需的。 |

## 全局属性

&lt;track&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;track&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

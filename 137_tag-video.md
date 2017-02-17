# HTML &lt;video&gt; 标签

## 实例

播放录像：

```HTML
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
    您的浏览器不支持 video 标签。
</video>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_video)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 9+、Firefox、Opera、Chrome 和 Safari 都支持 &lt;video&gt; 标签。

**注释：** IE 8 或更早版本的 IE 浏览器不支持 &lt;video&gt; 标签。

--------

## 标签定义及使用说明

&lt;video&gt; 标签定义视频，比如电影片段或其他视频流。

目前，&lt;video&gt; 元素支持三种视频格式：MP4、WebM、Ogg。

| 浏览器 | MP4 | WebM | Ogg |
| ---- | ---- | ---- | ---- |
| Internet Explorer | YES | NO | NO |
| Chrome | YES | YES | YES |
| Firefox | YES<br/>从 Firefox 21 版本开始<br/>Linux 系统从 Firefox 30 开始 | YES | YES |
| Safari | YES | NO | NO |
| Opera | YES<br/>从 Opera 25 版本开始 | YES | YES |

 * MP4 = MPEG 4文件使用 H264 视频编解码器和AAC音频编解码器
 * WebM = WebM 文件使用 VP8 视频编解码器和 Vorbis 音频编解码器
 * Ogg = Ogg 文件使用 Theora 视频编解码器和 Vorbis音频编解码器

--------

## 音频格式的 MIME 类型

| 格式 | MIME-type |
| ---- | ---- |
| MP4 | video/mp4 |
| WebM | video/webm |
| Ogg | video/ogg |

--------

## HTML 4.01 与 HTML5之间的差异

&lt;video&gt; 标签是 HTML5 的新标签。

--------

## 提示和注释

**提示：** 可以在 &lt;video&gt; 和 &lt;/video&gt; 标签之间放置文本内容，这样不支持 &lt;video&gt; 元素的浏览器就可以显示出该标签的信息。

--------

## 可选属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autoplay](att-video-autoplay.html) (New) | autoplay | 如果出现该属性，则视频在就绪后马上播放。 |
| [controls](att-video-controls.html) (New) | controls | 如果出现该属性，则向用户显示控件，比如播放按钮。 |
| [height](att-video-height.html) (New) | _pixels_ | 设置视频播放器的高度。 |
| [loop](att-video-loop.html) (New) | loop | 如果出现该属性，则当媒介文件完成播放后再次开始播放。 |
| [muted](att-video-muted.html) (New) | muted | 如果出现该属性，视频的音频输出为静音。 |
| [poster](att-video-poster.html) (New) | _URL_ | 规定视频正在下载时显示的图像，直到用户点击播放按钮。 |
| [preload](att-video-preload.html) (New) | auto<br/>metadata<br/>none | 如果出现该属性，则视频在页面加载时进行加载，并预备播放。如果使用 "autoplay"，则忽略该属性。 |
| [src](att-video-src.html) (New) | _URL_ | 要播放的视频的 URL。 |
| [width](att-video-width.html) (New) | _pixels_ | 设置视频播放器的宽度。 |

## 全局属性

&lt;video&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;video&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

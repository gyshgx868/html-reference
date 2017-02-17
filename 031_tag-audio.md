# HTML &lt;audio&gt; 标签

## 实例

播放声音：

```HTML
<audio controls>
<source src="horse.ogg" type="audio/ogg">
<source src="horse.mp3" type="audio/mpeg">
您的浏览器不支持 audio 元素。
</audio>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_audio)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 9+、Firefox、Opera、Chrome 和 Safari 都支持 &lt;audio&gt; 标签。

**注释：**  IE 8 或更早版本的 IE 浏览器不支持 &lt;audio&gt; 标签。

--------

## 标签定义及使用说明

&lt;audio&gt; 标签定义声音，比如音乐或其他音频流。

目前，&lt;audio&gt; 元素支持的3种文件格式：MP3、Wav、Ogg。

| 浏览器 | MP3 | Wav | Ogg |
| ---- | ---- | ---- | ---- |
| Internet Explorer | YES | NO | NO |
| Chrome | YES | YES | YES |
| Firefox | YES | YES | YES |
| Safari | YES | YES | NO |
| Opera | YES | YES | YES |

--------

## HTML 4.01 与 HTML5之间的差异

&lt;audio&gt; 标签是 HTML5 的新标签。

--------

## 提示和注释

**提示：** 可以在 &lt;audio&gt; 和 &lt;/audio&gt; 之间放置文本内容，这些文本信息将会被显示在那些不支持 &lt;audio&gt; 标签的浏览器中。

--------

## 属性

NEW：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autoplay](att-audio-autoplay.html) (NEW) | autoplay | 如果出现该属性，则音频在就绪后马上播放。 |
| [controls](att-audio-controls.html) (NEW) | controls | 如果出现该属性，则向用户显示音频控件（比如播放/暂停按钮）。 |
| [loop](att-audio-loop.html) (NEW) | loop | 如果出现该属性，则每当音频结束时重新开始播放。 |
| [muted](att-audio-muted.html) (NEW) | muted | 如果出现该属性，则音频输出为静音。 |
| [preload](att-audio-preload.html) (NEW) | auto<br/>metadata<br/>none | 规定当网页加载时，音频是否默认被加载以及如何被加载。 |
| [src](att-audio-src.html) (NEW) | _URL_ | 规定音频文件的 URL。 |

## 全局属性

&lt;audio&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;audio&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

# HTML 音频/视频 DOM 参考手册

--------

## HTML 音频/视频 DOM 参考手册

HTML5 DOM 为 &lt;audio&gt; 和 &lt;video&gt; 元素提供了方法、属性和事件。

这些方法、属性和事件允许您使用 JavaScript 来操作 &lt;audio&gt; 和 &lt;video&gt; 元素。

--------

## HTML 音频/视频 方法

| 方法 | 描述 |
| ---- | ---- |
| [addTextTrack()](av-met-addtexttrack.html) | 向音频/视频添加新的文本轨道。 |
| [canPlayType()](av-met-canplaytype.html) | 检测浏览器是否能播放指定的音频/视频类型。 |
| [load()](av-met-load.html) | 重新加载音频/视频元素。 |
| [play()](av-met-play.html) | 开始播放音频/视频。 |
| [pause()](av-met-pause.html) | 暂停当前播放的音频/视频。 |

## HTML 音频/视频属性

| 属性 | 描述 |
| ---- | ---- |
| [audioTracks](av-prop-audiotracks.html) | 返回表示可用音频轨道的 AudioTrackList 对象。 |
| [autoplay](av-prop-autoplay.html) | 设置或返回是否在加载完成后随即播放音频/视频。 |
| [buffered](av-prop-buffered.html) | 返回表示音频/视频已缓冲部分的 TimeRanges 对象。 |
| [controller](av-prop-controller.html) | 返回表示音频/视频当前媒体控制器的 MediaController 对象。 |
| [controls](av-prop-controls.html) | 设置或返回音频/视频是否显示控件（比如播放/暂停等）。 |
| crossOrigin | 设置或返回音频/视频的 CORS 设置。 |
| [currentSrc](av-prop-currentsrc.html) | 返回当前音频/视频的 URL。 |
| [currentTime](av-prop-currenttime.html) | 设置或返回音频/视频中的当前播放位置（以秒计）。 |
| [defaultMuted](av-prop-defaultmuted.html) | 设置或返回音频/视频默认是否静音。 |
| [defaultPlaybackRate](av-prop-defaultplaybackrate.html) | 设置或返回音频/视频的默认播放速度。 |
| [duration](av-prop-duration.html) | 返回当前音频/视频的长度（以秒计）。 |
| [ended](av-prop-ended.html) | 返回音频/视频的播放是否已结束。 |
| [error](av-prop-error.html) | 返回表示音频/视频错误状态的 MediaError 对象。 |
| [loop](av-prop-loop.html) | 设置或返回音频/视频是否应在结束时重新播放。 |
| [mediaGroup](av-prop-mediagroup.html) | 设置或返回音频/视频所属的组合（用于连接多个音频/视频元素）。 |
| [muted](av-prop-muted.html) | 设置或返回音频/视频是否静音。 |
| [networkState](av-prop-networkstate.html) | 返回音频/视频的当前网络状态。 |
| [paused](av-prop-paused.html) | 设置或返回音频/视频是否暂停。 |
| [playbackRate](av-prop-playbackrate.html) | 设置或返回音频/视频播放的速度。 |
| [played](av-prop-played.html) | 返回表示音频/视频已播放部分的 TimeRanges 对象。 |
| [preload](av-prop-preload.html) | 设置或返回音频/视频是否应该在页面加载后进行加载。 |
| [readyState](av-prop-readystate.html) | 返回音频/视频当前的就绪状态。 |
| [seekable](av-prop-seekable.html) | 返回表示音频/视频可寻址部分的 TimeRanges 对象。 |
| [seeking](av-prop-seeking.html) | 返回用户是否正在音频/视频中进行查找。 |
| [src](av-prop-src.html) | 设置或返回音频/视频元素的当前来源。 |
| [startDate](av-prop-startdate.html) | 返回表示当前时间偏移的 Date 对象。 |
| [textTracks](av-prop-texttracks.html) | 返回表示可用文本轨道的 TextTrackList 对象。 |
| [videoTracks](av-prop-videotracks.html) | 返回表示可用视频轨道的 VideoTrackList 对象。 |
| [volume](av-prop-volume.html) | 设置或返回音频/视频的音量。 |

## HTML 音频/视频事件

| 事件 | 描述 |
| ---- | ---- |
| [abort](av-event-abort.html) | 当音频/视频的加载已放弃时触发。 |
| [canplay](av-event-canplay.html) | 当浏览器可以开始播放音频/视频时触发。 |
| [canplaythrough](av-event-canplaythrough.html) | 当浏览器可在不因缓冲而停顿的情况下进行播放时触发。 |
| [durationchange](av-event-durationchange.html) | 当音频/视频的时长已更改时触发。 |
| emptied | 当目前的播放列表为空时触发。 |
| [ended](av-event-ended.html) | 当目前的播放列表已结束时触发。 |
| [error](av-event-error.html) | 当在音频/视频加载期间发生错误时触发。 |
| [loadeddata](av-event-loadeddata.html) | 当浏览器已加载音频/视频的当前帧时触发。 |
| [loadedmetadata](av-event-loadedmetadata.html) | 当浏览器已加载音频/视频的元数据时触发。 |
| [loadstart](av-event-loadstart.html) | 当浏览器开始查找音频/视频时触发。 |
| [pause](av-event-pause.html) | 当音频/视频已暂停时触发。 |
| [play](av-event-play.html) | 当音频/视频已开始或不再暂停时触发。 |
| [playing](av-event-playing.html) | 当音频/视频在因缓冲而暂停或停止后已就绪时触发。 |
| [progress](av-event-progress.html) | 当浏览器正在下载音频/视频时触发。 |
| [ratechange](av-event-ratechange.html) | 当音频/视频的播放速度已更改时触发。 |
| [seeked](av-event-seeked.html) | 当用户已移动/跳跃到音频/视频中的新位置时触发。 |
| [seeking](av-event-seeking.html) | 当用户开始移动/跳跃到音频/视频中的新位置时触发。 |
| [stalled](av-event-stalled.html) | 当浏览器尝试获取媒体数据，但数据不可用时触发。 |
| [suspend](av-event-suspend.html) | 当浏览器刻意不获取媒体数据时触发。 |
| [timeupdate](av-event-timeupdate.html) | 当目前的播放位置已更改时触发。 |
| [volumechange](av-event-volumechange.html) | 当音量已更改时触发。 |
| [waiting](av-event-waiting.html) | 当视频由于需要缓冲下一帧而停止时触发。 |

# HTML 事件属性

--------

## 全局事件属性

HTML 4 的新特性之一是可以使 HTML 事件触发浏览器中的行为，比方说当用户点击某个 HTML 元素时启动一段 JavaScript。

如果你想学习更多关于事件属性，请访问 [JavaScript 教程](js-tutorial.html)

下面的表格提供了标准的事件属性，可以把它们插入 HTML/XHTML 元素中，以定义事件行为。

New: HTML5新增属性事件。

--------

## 窗口事件属性（Window Event Attributes）

由窗口触发该事件 (适用于 &lt;body&gt; 标签):

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [onafterprint](ev-onafterprint.html) (New) | _script_ | 在打印文档之后运行脚本 |
| [onbeforeprint](ev-onbeforeprint.html) (New)| _script_ | 在文档打印之前运行脚本 |
| onbeforeonload (New)| _script_ | 在文档加载之前运行脚本 |
| onblur | _script_ | 当窗口失去焦点时运行脚本 |
| onerror  (New)| _script_ | 当错误发生时运行脚本 |
| onfocus | _script_ | 当窗口获得焦点时运行脚本 |
| onhaschange (New)| _script_ | 当文档改变时运行脚本 |
| [onload](ev-onload.html) | _script_ | 当文档加载时运行脚本 |
| onmessage (New)| _script_ | 当触发消息时运行脚本 |
| onoffline (New)| _script_ | 当文档离线时运行脚本 |
| ononline (New)| _script_ | 当文档上线时运行脚本 |
| onpagehide (New)| _script_ | 当窗口隐藏时运行脚本 |
| onpageshow (New)| _script_ | 当窗口可见时运行脚本 |
| onpopstate (New)| _script_ | 当窗口历史记录改变时运行脚本 |
| onredo (New)| _script_ | 当文档执行再执行操作（redo）时运行脚本 |
| [onresize](ev-onresize.html) (New)| _script_ | 当调整窗口大小时运行脚本 |
| onstorage (New)| _script_ | 当 Web Storage 区域更新时（存储空间中的数据发生变化时）运行脚本 |
| onundo (New)| _script_ | 当文档执行撤销时运行脚本 |
| [onunload](ev-onunload.html) (New)| _script_ | 当用户离开文档时运行脚本 |

--------

## 表单事件(Form Events)

表单事件在HTML表单中触发 (适用于所有 HTML 元素, 但该HTML元素需在form表单内):

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [onblur](ev-onblur.html) | _script_ | 当元素失去焦点时运行脚本 |
| [onchange](ev-onchange.html) | _script_ | 当元素改变时运行脚本 |
| oncontextmenu (New)| _script_ | 当触发上下文菜单时运行脚本 |
| [onfocus](ev-onfocus.html) | _script_ | 当元素获得焦点时运行脚本 |
| onformchange (New)| _script_ | 当表单改变时运行脚本 |
| onforminput (New)| _script_ | 当表单获得用户输入时运行脚本 |
| oninput (New)| _script_ | 当元素获得用户输入时运行脚本 |
| oninvalid (New)| _script_ | 当元素无效时运行脚本 |
| onreset | _script_ | 当表单重置时运行脚本。**HTML 5 不支持。** |
| [onselect](ev-onselect.html) | _script_ | 当选取元素时运行脚本 |
| [onsubmit](ev-onsubmit.html) | _script_ | 当提交表单时运行脚本 |

--------

## 键盘事件（Keyboard Events）

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [onkeydown](ev-onkeydown.html) | _script_ | 当按下按键时运行脚本 |
| [onkeypress](ev-onkeypress.html) | _script_ | 当按下并松开按键时运行脚本 |
| [onkeyup](ev-onkeyup.html) | _script_ | 当松开按键时运行脚本 |

--------

## 鼠标事件（Mouse Events）

通过鼠标触发事件, 类似用户的行为:

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [onclick](ev-onclick.html) | _script_ | 当单击鼠标时运行脚本 |
| [ondblclick](ev-ondblclick.html) | _script_ | 当双击鼠标时运行脚本 |
| ondrag (New)| _script_ | 当拖动元素时运行脚本 |
| ondragend (New)| _script_ | 当拖动操作结束时运行脚本 |
| ondragenter (New)| _script_ | 当元素被拖动至有效的拖放目标时运行脚本 |
| ondragleave (New)| _script_ | 当元素离开有效拖放目标时运行脚本 |
| ondragover (New)| _script_ | 当元素被拖动至有效拖放目标上方时运行脚本 |
| ondragstart (New)| _script_ | 当拖动操作开始时运行脚本 |
| ondrop (New)| _script_ | 当被拖动元素正在被拖放时运行脚本 |
| [onmousedown](ev-onmousedown.html) | _script_ | 当按下鼠标按钮时运行脚本 |
| [onmousemove](ev-onmousemove.html) | _script_ | 当鼠标指针移动时运行脚本 |
| [onmouseout](ev-onmouseout.html) | _script_ | 当鼠标指针移出元素时运行脚本 |
| [onmouseover](ev-onmouseover.html) | _script_ | 当鼠标指针移至元素之上时运行脚本 |
| [onmouseup](ev-onmouseup.html) | _script_ | 当松开鼠标按钮时运行脚本 |
| onmousewheel (New)| _script_ | 当转动鼠标滚轮时运行脚本 |
| onscroll (New)| _script_ | 当滚动元素的滚动条时运行脚本 |

--------

## 多媒体事件(Media Events)

通过视频（videos），图像（images）或者音频（audio） 触发该事件，多应用于HTML媒体元素比如 &lt;audio&gt;, &lt;embed&gt;, &lt;img&gt;, &lt;object&gt;, 和&lt;video&gt;):

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| onabort | _script_ | 当发生中止事件时运行脚本 |
| oncanplay (New)| _script_ | 当媒介能够开始播放但可能因缓冲而需要停止时运行脚本 |
| oncanplaythrough (New)| _script_ | 当媒介能够无需因缓冲而停止即可播放至结尾时运行脚本 |
| ondurationchange (New)| _script_ | 当媒介长度改变时运行脚本 |
| onemptied (New)| _script_ | 当媒介资源元素突然为空时（网络错误、加载错误等）运行脚本 |
| onended (New)| _script_ | 当媒介已抵达结尾时运行脚本 |
| onerror (New)| _script_ | 当在元素加载期间发生错误时运行脚本 |
| onloadeddata (New)| _script_ | 当加载媒介数据时运行脚本 |
| onloadedmetadata (New)| _script_ | 当媒介元素的持续时间以及其他媒介数据已加载时运行脚本 |
| onloadstart (New)| _script_ | 当浏览器开始加载媒介数据时运行脚本 |
| onpause (New)| _script_ | 当媒介数据暂停时运行脚本 |
| onplay (New)| _script_ | 当媒介数据将要开始播放时运行脚本 |
| onplaying (New)| _script_ | 当媒介数据已开始播放时运行脚本 |
| onprogress (New)| _script_ | 当浏览器正在取媒介数据时运行脚本 |
| onratechange (New)| _script_ | 当媒介数据的播放速率改变时运行脚本 |
| onreadystatechange (New)| _script_ | 当就绪状态（ready-state）改变时运行脚本 |
| onseeked (New)| _script_ | 当媒介元素的定位属性 [1] 不再为真且定位已结束时运行脚本 |
| onseeking (New)| _script_ | 当媒介元素的定位属性为真且定位已开始时运行脚本 |
| onstalled (New)| _script_ | 当取回媒介数据过程中（延迟）存在错误时运行脚本 |
| onsuspend (New)| _script_ | 当浏览器已在取媒介数据但在取回整个媒介文件之前停止时运行脚本 |
| ontimeupdate (New)| _script_ | 当媒介改变其播放位置时运行脚本 |
| onvolumechange (New)| _script_ | 当媒介改变音量亦或当音量被设置为静音时运行脚本 |
| onwaiting (New)| _script_ | 当媒介已停止播放但打算继续播放时运行脚本 |

## 其他事件

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [onshow](ev-onshow.html) (New) | _script_ | 当 &lt;menu&gt; 元素在上下文显示时触发 |
| [ontoggle](ev-ontoggle.html) (New) | _script_ | 当用户打开或关闭 &lt;details&gt; 元素时触发 |

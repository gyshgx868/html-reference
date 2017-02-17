# HTML &lt;time&gt; 标签

## 实例

如何定义时间和日期：

```HTML
<p>我们在每天早上 <time>9:00</time> 开始营业。</p>

<p>我在 <time datetime="2016-02-14">情人节</time> 有个约会。</p>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_time)

--------

## 浏览器支持

表格中的数字表示支持该属性的第一个浏览器的版本号。

| 元素 | ![Chrome](images/compatible_chrome.gif) | ![Chrome](images/compatible_ie.gif) | ![Chrome](images/compatible_firefox.gif) | ![Chrome](images/compatible_safari.gif) | ![Chrome](images/compatible_opera.gif) |
| ---- | ---- | ---- | ---- | ---- | ---- |
| &lt;time&gt; | 6.0 | 9.0 | 4.0 | 5.0 | 11.1 |

--------

## 标签定义及使用说明

&lt;time&gt; 标签定义公历的时间（24 小时制）或日期，时间和时区偏移是可选的。

该元素能够以机器可读的方式对日期和时间进行编码，这样，举例说，用户代理能够把生日提醒或排定的事件添加到用户日程表中，搜索引擎也能够生成更智能的搜索结果。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;time&gt; 标签是 HTML5 中的新标签。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [datetime](att-time-datetime.html) (New) | _datetime_ | 规定日期/时间。另一种方式，则是由元素的内容给定日期/时间。 |

## 全局属性

&lt;time&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;time&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

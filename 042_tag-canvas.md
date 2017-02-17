# HTML &lt;canvas&gt; 标签

## 实例

通过 &lt;canvas&gt; 元素来显示一个红色的矩形：

```HTML
<canvas id="myCanvas"></canvas>

<script type="text/javascript">
var canvas=document.getElementById('myCanvas');
var ctx=canvas.getContext('2d');
ctx.fillStyle='#FF0000';
ctx.fillRect(0,0,80,100);
</script>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_canvas)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

IE 9、Firefox、Opera、Chrome 和 Safari 支持 &lt;canvas&gt; 标签。

**注释：** IE 8 或更早版本的 IE 浏览器不支持 &lt;canvas&gt; 标签。

--------

## 标签定义及使用说明

&lt;canvas&gt; 标签通过脚本（通常是 JavaScript）来绘制图形（比如图表和其他图像）。

&lt;canvas&gt; 标签只是图形容器，您必须使用脚本来绘制图形。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;canvas&gt; 标签是 HTML5 中的新标签。

--------

## 提示和注释

**注释：** &lt;canvas&gt; 元素中的任何文本将会被显示在不支持 &lt;canvas&gt; 的浏览器中。

**提示：** 如想了解 canvas 对象的所有属性和方法，请参阅[HTML 画布参考手册](005_ref-canvas.md)。

--------

## 属性

New: HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [height](att-canvas-height.html) (New) | _pixels_ | 规定画布的高度。 |
| [width](att-canvas-width.html) (New) | _pixels_ | 规定画布的宽度。 |

## 全局属性

&lt;canvas&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;canvas&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

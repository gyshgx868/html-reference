# HTML5 &lt;canvas&gt; 参考手册

--------

## 描述

HTML5 &lt;canvas&gt; 标签用于绘制图像（通过脚本，通常是 JavaScript）。

不过，&lt;canvas&gt; 元素本身并没有绘制能力（它仅仅是图形的容器） - 您必须使用脚本来完成实际的绘图任务。

getContext() 方法可返回一个对象，该对象提供了用于在画布上绘图的方法和属性。

本手册提供完整的 getContext("2d") 对象的属性和方法，可用于在画布上绘制文本、线条、矩形、圆形等等。

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

Internet Explorer 9、Firefox、Opera、Chrome 和 Safari 支持 &lt;canvas&gt; 标签的属性及方法。

**注意:** Internet Explorer 8 及更早的IE版本不支持 &lt;canvas&gt; 元素。

--------

## 颜色、样式和阴影

| 属性 | 描述 |
| ---- | ---- |
| [fillStyle](canvas-fillstyle.html) | 设置或返回用于填充绘画的颜色、渐变或模式。 |
| [strokeStyle](canvas-strokestyle.html) | 设置或返回用于笔触的颜色、渐变或模式。 |
| [shadowColor](canvas-shadowcolor.html) | 设置或返回用于阴影的颜色。 |
| [shadowBlur](canvas-shadowblur.html) | 设置或返回用于阴影的模糊级别。 |
| [shadowOffsetX](canvas-shadowoffsetx.html) | 设置或返回阴影与形状的水平距离。 |
| [shadowOffsetY](canvas-shadowoffsety.html) | 设置或返回阴影与形状的垂直距离。 |

| 方法 | 描述 |
| ---- | ---- |
| [createLinearGradient()](canvas-createlineargradient.html) | 创建线性渐变（用在画布内容上）。 |
| [createPattern()](canvas-createpattern.html) | 在指定的方向上重复指定的元素。 |
| [createRadialGradient()](canvas-createradialgradient.html) | 创建放射状/环形的渐变（用在画布内容上）。 |
| [addColorStop()](canvas-addcolorstop.html) | 规定渐变对象中的颜色和停止位置。 |

## 线条样式

| 属性 | 描述 |
| ---- | ---- |
| [lineCap](canvas-linecap.html) | 设置或返回线条的结束端点样式。 |
| [lineJoin](canvas-linejoin.html) | 设置或返回两条线相交时，所创建的拐角类型。 |
| [lineWidth](canvas-linewidth.html) | 设置或返回当前的线条宽度。 |
| [miterLimit](canvas-miterlimit.html) | 设置或返回最大斜接长度。 |

## 矩形

| 方法 | 描述 |
| ---- | ---- |
| [rect()](canvas-rect.html) | 创建矩形。 |
| [fillRect()](canvas-fillrect.html) | 绘制"被填充"的矩形。 |
| [strokeRect()](canvas-strokerect.html) | 绘制矩形（无填充）。 |
| [clearRect()](canvas-clearrect.html) | 在给定的矩形内清除指定的像素。 |

## 路径

| 方法 | 描述 |
| ---- | ---- |
| [fill()](canvas-fill.html) | 填充当前绘图（路径）。 |
| [stroke()](canvas-stroke.html) | 绘制已定义的路径。 |
| [beginPath()](canvas-beginpath.html) | 起始一条路径，或重置当前路径。 |
| [moveTo()](canvas-moveto.html) | 把路径移动到画布中的指定点，不创建线条。 |
| [closePath()](canvas-closepath.html) | 创建从当前点回到起始点的路径。 |
| [lineTo()](canvas-lineto.html) | 添加一个新点，然后在画布中创建从该点到最后指定点的线条。 |
| [clip()](canvas-clip.html) | 从原始画布剪切任意形状和尺寸的区域。 |
| [quadraticCurveTo()](canvas-quadraticcurveto.html) | 创建二次贝塞尔曲线。 |
| [bezierCurveTo()](canvas-beziercurveto.html) | 创建三次贝塞尔曲线。 |
| [arc()](canvas-arc.html) | 创建弧/曲线（用于创建圆形或部分圆）。 |
| [arcTo()](canvas-arcto.html) | 创建两切线之间的弧/曲线。 |
| [isPointInPath()](canvas-ispointinpath.html) | 如果指定的点位于当前路径中，则返回 true，否则返回 false。 |

## 转换

| 方法 | 描述 |
| ---- | ---- |
| [scale()](canvas-scale.html) | 缩放当前绘图至更大或更小。 |
| [rotate()](canvas-rotate.html) | 旋转当前绘图。 |
| [translate()](canvas-translate.html) | 重新映射画布上的 (0,0) 位置。 |
| [transform()](canvas-transform.html) | 替换绘图的当前转换矩阵。 |
| [setTransform()](canvas-settransform.html) | 将当前转换重置为单位矩阵。然后运行 transform()。 |

## 文本

| 属性 | 描述 |
| ---- | ---- |
| [font](canvas-font.html) | 设置或返回文本内容的当前字体属性。 |
| [textAlign](canvas-textalign.html) | 设置或返回文本内容的当前对齐方式。 |
| [textBaseline](canvas-textbaseline.html) | 设置或返回在绘制文本时使用的当前文本基线。 |

| 方法 | 描述 |
| ---- | ---- |
| [fillText()](canvas-filltext.html) | 在画布上绘制"被填充的"文本。 |
| [strokeText()](canvas-stroketext.html) | 在画布上绘制文本（无填充）。 |
| [measureText()](canvas-measuretext.html) | 返回包含指定文本宽度的对象。 |

## 图像绘制

| 方法 | 描述 |
| ---- | ---- |
| [drawImage()](canvas-drawimage.html) | 向画布上绘制图像、画布或视频。 |

## 像素操作

| 属性 | 描述 |
| ---- | ---- |
| [width](canvas-imagedata-width.html) | 返回 ImageData 对象的宽度。 |
| [height](canvas-imagedata-height.html) | 返回 ImageData 对象的高度。 |
| [data](canvas-imagedata-data.html) | 返回一个对象，其包含指定的 ImageData 对象的图像数据。 |

| 方法 | 描述 |
| ---- | ---- |
| [createImageData()](canvas-createimagedata.html) | 创建新的、空白的 ImageData 对象。 |
| [getImageData()](canvas-getimagedata.html) | 返回 ImageData 对象，该对象为画布上指定的矩形复制像素数据。 |
| [putImageData()](canvas-putimagedata.html) | 把图像数据（从指定的 ImageData 对象）放回画布上。 |

## 合成

| 属性 | 描述 |
| ---- | ---- |
| [globalAlpha](canvas-globalalpha.html) | 设置或返回绘图的当前 alpha 或透明值。 |
| [globalCompositeOperation](canvas-globalcompositeoperation.html) | 设置或返回新图像如何绘制到已有的图像上。 |

## 其他

| 方法 | 描述 |
| ---- | ---- |
| save() | 保存当前环境的状态。 |
| restore() | 返回之前保存过的路径状态和属性。 |
| createEvent() | &nbsp; |
| getContext() | &nbsp; |
| toDataURL() | &nbsp; |

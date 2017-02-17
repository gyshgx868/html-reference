# HTML &lt;applet&gt; 标签 - HTML5 不支持

## 实例

一个嵌入的 Java applet：

```HTML
<applet code="Bubbles.class" width="350" height="350">
Java applet that draws animated bubbles.
</applet>
```

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

**注释：** 某些浏览器中依然存在对 &lt;applet&gt; 但是需要额外的插件和安装过程才能起作用。

--------

## 标签定义及使用说明

HTML5 不支持 &lt;applet&gt; 标签。请使用 [&lt;object&gt;](094_tag-object.md) 标签代替它。

在 HTML 4.01 中，&lt;applet&gt; 元素 [已废弃](javascript:NewWindow('/try/deprecated.htm'))。

&lt;applet&gt; 标签定义嵌入的 applet。

--------

## HTML 4.01 与 HTML5之间的差异

HTML5 不支持 &lt;applet&gt; 标签，HTML 4.01 已废弃 &lt;applet&gt; 标签。

--------

## 必需的属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| code | _URL_ | 规定 Java applet 的文件名。 |
| object | _name_ | 规定了包含该 applet 的一系列版本的资源名称。 |

## 可选的属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| align | left<br/>right<br/>top<br/>bottom<br/>middle<br/>baseline | 规定 applet 相对于周围元素的对齐方式。 |
| alt | _text_ | 规定 applet 的替换文本。 |
| archive | _URL_ | 规定档案文件的位置。 |
| codebase | _URL_ | 规定 code 属性中指定的 applet 的基准 URL。 |
| height | _pixels_ | 规定 applet 的高度。 |
| hspace | _pixels_ | 定义围绕 applet 的水平间隔。 |
| name | _name_ | 定义 applet 的名称（用在脚本中的）。 |
| vspace | _pixels_ | 定义围绕 applet 的垂直间隔。 |
| width | _pixels_ | 规定 applet 的宽度。 |

--------

## 标准属性

在 HTML 4.01 中，&lt;applet&gt; 标签支持如下标准属性：

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| class | _classname_ | 规定元素的类名 |
| id | _id_ | 规定元素的唯一 id |
| style | _style_definition_ | 规定元素的行内样式 |
| title | _text_ | 规定元素的额外信息 |

如需完整的描述，请访问[标准属性](003_ref-standardattributes.md)。

--------

## 事件属性

在 HTML 4.01 中，&lt;applet&gt; 标签不支持任何事件属性。

如需完整的描述，请访问[事件属性](004_ref-eventattributes.md)。

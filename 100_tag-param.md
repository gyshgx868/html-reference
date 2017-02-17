# HTML &lt;param&gt; 标签

## 实例

设置参数 "autoplay" 为 "true"，音频载入后会自动播放：

```HTML
<object data="horse.wav">
  <param name="autoplay" value="true">
</object>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_param)

--------

## 浏览器支持

![Internet Explorer](images/compatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

&lt;param&gt; 标签支持大部分主流浏览器。但是 &lt;object&gt; 定义的文件格式不是所有的浏览器都支持。

--------

## 标签定义及使用说明

&lt;param&gt;元素允许您为插入 XHTML 文档的对象规定 run-time 设置，也就是说，此标签可为包含它的 [&lt;object&gt;](094_tag-object.md) 或者 [&lt;applet&gt;](027_tag-applet.md) 标签提供参数。

--------

## 在HTML 4.01 与 HTML5 之间的差异

HTML 4.01 属性： "type" 和 "valuetype"，在 HTML5 中不支持。

--------

## Differences Between HTML and XHTML

在 HTML 中，&lt;param&gt; 标签没有结束标签。

在 XHTML 中，&lt;param&gt; 标签必须被正确地关闭。

--------

## 属性

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [name](att-param-name.html) | _name_ | 定义参数的名称（用在脚本中）。 |
| type | _MIME_type_ | **HTML5不支持。** 定义 MIME 类型参数。 |
| [value](att-param-value.html) | _value_ | 描述参数值。 |
| valuetype | data<br/>ref<br/>object | **HTML5 不支持。** 描述值的类型。 |

--------

## 全局属性

&lt;param&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;param&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

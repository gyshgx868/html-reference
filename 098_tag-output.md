# HTML &lt;output&gt; 标签

## 实例

将计算结果显示在 &lt;output&gt; 元素中：

```HTML
<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">0
  <input type="range" id="a" value="50">100
  +<input type="number" id="b" value="50">
  =<output name="x" for="a b"></output>
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_output)

--------

## 浏览器支持

![Internet Explorer](images/incompatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

Firefox、Opera、Chrome 和 Safari 浏览器都支持 &lt;output&gt; 标签。

**注意:** Internet Explorer 浏览器不支持 &lt;output&gt; 标签。

--------

## 标签定义及使用说明

&lt;output&gt; 标签作为计算结果输出显示(比如执行脚本的输出)。

--------

## 在HTML 4.01 与 HTML5中的差异

&lt;output&gt; 标签是 HTML 5 中的新标签。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [for](att-output-for.html) (New) | _element_id_ | 描述计算中使用的元素与计算结果之间的关系。 |
| [form](att-output-form.html) (New) | _form_id_ | 定义输入字段所属的一个或多个表单。 |
| [name](att-output-name.html) (New) | _name_ | 定义对象的唯一名称（表单提交时使用）。 |

## 全局属性

&lt;output&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;output&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

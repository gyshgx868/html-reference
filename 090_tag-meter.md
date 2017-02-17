# HTML &lt;meter&gt; 标签

## 实例

使用 meter 元素展示给定的数据范围：

```HTML
<meter value="2" min="0" max="10">2 out of 10</meter><br>
<meter value="0.6">60%</meter>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_meter)

--------

## 浏览器支持

![Internet Explorer](images/incompatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

Firefox、Opera、Chrome 和 Safari 6 支持 &lt;meter&gt; 标签。

--------

## 标签定义及使用说明

&lt;meter&gt; 标签定义度量衡。仅用于已知最大和最小值的度量。

比如：磁盘使用情况，查询结果的相关性等。

**注意：**  &lt;meter&gt; 不能作为一个进度条来使用， 进度条 [&lt;progress&gt;](103_tag-progress.md) 标签。

--------

## HTML 4.01 与 HTML5 之间的差异

&lt;meter&gt; 是 HTML5 的新标签。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [form](att-meter-form.html) (New) | _form_id_ | 规定 &lt;meter&gt; 元素所属的一个或多个表单。 |
| [high](att-meter-high.html) (New) | _number_ | 规定被界定为高的值的范围。 |
| [low](att-meter-low.html) (New) | _number_ | 规定被界定为低的值的范围。 |
| [max](att-meter-max.html) (New) | _number_ | 规定范围的最大值。 |
| [min](att-meter-min.html) (New) | _number_ | 规定范围的最小值。 |
| [optimum](att-meter-optimum.html) (New) | _number_ | 规定度量的最优值。 |
| [value](att-meter-value.html) (New) | _number_ | 必需。规定度量的当前值。 |

## 全局属性

&lt;meter&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;meter&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

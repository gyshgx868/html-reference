# HTML &lt;command&gt; 标签

## 实例

&lt;command&gt; 可以进行如下标记：

```HTML
<menu>
<command type="command" label="Save" onclick="save()">Save</command>
</menu>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_command)

--------

## 浏览器支持

![Internet Explorer](images/incompatible_ie.gif)![Firefox](images/incompatible_firefox.gif)![Opera](images/incompatible_opera.gif)![Google Chrome](images/incompatible_chrome.gif)![Safari](images/incompatible_safari.gif)

目前，主流浏览器都不支持 &lt;command&gt; 标签。

**注释：** 只有 IE 9 支持 &lt;command&gt; 标签，其他之前版本或者之后版本的 IE 浏览器不支持 &lt;command&gt; 标签。

--------

## 标签定义及使用说明

&lt;command&gt; 标签可以定义用户可能调用的命令（比如单选按钮、复选框或按钮）。

当使用 &lt;menu&gt; 元素时，command 元素将作为菜单或者工具栏的一部分显示出来。但是，用 command 规定键盘快捷键时，command元素能被放置在页面的任何位置，但元素不可见。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;command&gt; 标签是 HTML 5 中的新标签。

--------

## 属性

New：HTML5 中的新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [checked](att-command-checked.html) (New) | checked | 规定当页面加载时，command 是否被选中。仅用于 radio 或 checkbox 类型。 |
| [disabled](att-command-disabled.html) (New) | disabled | 规定 command 是否可用。 |
| [icon](att-command-icon.html) (New) | _URL_ | 规定作为 command 来显示的图像的 URL。 |
| [label](att-command-label.html) (New) | _text_ | 必需。规定 command 的名字，对用户可见。 |
| [radiogroup](att-command-radiogroup.html) (New) | _groupname_ | 规定可进行切换且将被切换的 command 所属的组名。仅在类型为 radio 时使用。 |
| [type](att-command-type.html) (New) | checkbox

 command

 radio | 定义 command 的类型。默认是 "command"。 |

## 全局属性

&lt;command&gt; 标签支持 [HTML 的全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;command&gt; 标签支持 [HTML 的事件属性](004_ref-eventattributes.md)。

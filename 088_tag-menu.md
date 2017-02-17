# HTML &lt;menu&gt; 标签

## 实例

两个菜单按钮系列选项实例（"File" 和 "Edit"）：

```HTML
<menu type="toolbar">
<li>
    <menu label="File">
    <button type="button" onclick="file_new()">New...</button>
    <button type="button" onclick="file_open()">Open...</button>
    <button type="button" onclick="file_save()">Save</button>
    </menu>
</li>
<li>
    <menu label="Edit">
    <button type="button" onclick="edit_cut()">Cut</button>
    <button type="button" onclick="edit_copy()">Copy</button>
    <button type="button" onclick="edit_paste()">Paste</button>
    </menu>
</li>
</menu>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_menu)

--------

## 浏览器支持

![Internet Explorer](images/incompatible_ie.gif)![Firefox](images/incompatible_firefox.gif)![Opera](images/incompatible_opera.gif)![Google Chrome](images/incompatible_chrome.gif)![Safari](images/incompatible_safari.gif)

目前主流浏览器并不支持 &lt;menu&gt; 标签。

--------

## 标签定义及使用说明

&lt;menu&gt; 标签定义了一个命令列表或菜单。

&lt;menu&gt; 标签通常用于文本菜单，工具条和命令列表选项。

--------

## 提示和注释

**提示:**  使用 CSS 来定义菜单列表样式。

--------

## HTML 4.01 与 HTML5之间的差异

HTML 4.01的 &lt;menu&gt; 元素已废弃。

HTML5 中 &lt;menu&gt; 元素已被重新定义。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [label](att-menu-label.html) (New) | _text_ | 描述菜单项的标记。 |
| [type](att-menu-type.html) (New) | context

 toolbar

 list | 描述显示菜单类型. 默认为 "list"。 |

## 全局属性

&lt;menu&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md)。

--------

## 事件属性

&lt;menu&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md)。

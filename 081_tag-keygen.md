# HTML &lt;keygen&gt; 标签

> **该标签在新的 Web 标准中已废弃。**

## 实例

带有 keygen 字段的表单：

```HTML
<form action="demo_keygen.asp" method="get">
  用户名: <input type="text" name="usr_name">
  加密: <keygen name="security">
  <input type="submit">
</form>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml5_keygen)

--------

## 浏览器支持

![Internet Explorer](images/incompatible_ie.gif)![Firefox](images/compatible_firefox.gif)![Opera](images/compatible_opera.gif)![Google Chrome](images/compatible_chrome.gif)![Safari](images/compatible_safari.gif)

Firefox、Opera、Chrome 和 Safari 6 都支持 &lt;keygen&gt; 标签。

--------

## 标签定义及使用说明

&lt;keygen&gt; 标签规定用于表单的密钥对生成器字段。

当提交表单时，私钥存储在本地，公钥发送到服务器。

--------

## HTML 4.01 与 HTML5之间的差异

&lt;keygen&gt; 元素是 HTML5 新标签。

--------

## 属性

New：HTML5 新属性。

| 属性 | 值 | 描述 |
| ---- | ---- | ---- |
| [autofocus](att-keygen-autofocus.html) (New) | autofocus | 使 &lt;keygen&gt; 字段在页面加载时获得焦点。 |
| challenge (New) | challenge | 如果使用，则将 keygen 的值设置为在提交时询问。 |
| [disabled](att-keygen-disabled.html) (New) | disabled | 禁用 &lt;keygen&gt; 元素字段。 |
| [form](att-keygen-form.html) (New) | _form_id_ | 定义该 &lt;keygen&gt; 字段所属的一个或多个表单。 |
| [keytype](att-keygen-keytype.html) (New) | rsa<br/>dsa<br/>ec | 定义密钥的安全算法。 |
| [name](att-keygen-name.html) (New) | _name_ | 定义 &lt;keygen&gt; 元素的唯一名称。 name 属性用于在提交表单时搜集字段的值。 |

## 全局属性

&lt;keygen&gt; 标签支持全局属性，查看完整属性表 [HTML全局属性](003_ref-standardattributes.md).

--------

## 事件属性

&lt;keygen&gt; 标签支持所有 [HTML事件属性](004_ref-eventattributes.md).

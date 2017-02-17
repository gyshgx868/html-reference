# HTML 字符集

--------

## HTML 字符集

如需正确地显示 HTML 页面，浏览器必须知道使用何种字符集。

万维网早期使用的字符集是 ASCII。ASCII 支持 0-9 的数字，大写和小写英文字母表，以及一些特殊字符。

[完整的 ASCII 参考手册](012_html-ascii.md)。

由于很多国家使用的字符并不属于 ASCII，现代浏览器的默认字符集是 ISO-8859-1。

[完整的 ISO-8859-1 参考手册](013_ref-entities.md)。

如果网页使用不同于 ISO-8859-1 的字符集，就应该在 &lt;meta&gt; 标签进行指定。

[尝试一下](http://www.runoob.com/try/try.php?filename=tryhtml_charsets)

--------

## ISO 字符集

ISO 字符集是国际标准组织 (ISO) 针对不同的字母表/语言定义的标准字符集。

下面列出了世界各地使用的不同字符集：

| 字符集 | 描述 | 使用范围 |
| ---- | ---- | ---- |
| ISO-8859-1 | Latin alphabet part 1 | 北美、西欧、拉丁美洲、加勒比海、加拿大、非洲 |
| ISO-8859-2 | Latin alphabet part 2 | 东欧 |
| ISO-8859-3 | Latin alphabet part 3 | SE Europe、世界语、其他杂项 |
| ISO-8859-4 | Latin alphabet part 4 | 斯堪的纳维亚/波罗的海（以及其他没有包括在 ISO-8859-1 中的部分） |
| ISO-8859-5 | Latin/Cyrillic part 5 | 使用古代斯拉夫语字母表的语言，比如保加利亚语、白俄罗斯文、俄罗斯语、马其顿语 |
| ISO-8859-6 | Latin/Arabic part 6 | 使用阿拉伯字母的语言 |
| ISO-8859-7 | Latin/Greek part 7 | 现代希腊语，以及由希腊语衍生的数学符号 |
| ISO-8859-8 | Latin/Hebrew part 8 | 使用希伯来语的语言 |
| ISO-8859-9 | Latin 5 part 9 | 土耳其语。除了土耳其字符取代了冰岛文字，其它与 ISO-8859-1 相同。 |
| ISO-8859-10 | Latin 6 | 拉普兰语、日耳曼语、爱斯基摩北欧语 |
| ISO-8859-15 | Latin 9 (aka Latin 0) | 与 ISO 8859-1 类似，欧元符号和其他一些字符取代了一些较少使用的符号 |
| ISO-2022-JP | Latin/Japanese part 1 | 日本语 |
| ISO-2022-JP-2 | Latin/Japanese part 2 | 日本语 |
| ISO-2022-KR | Latin/Korean part 1 | 韩语 |

--------

## Unicode 标准

由于上面列出的字符集都有容量限制，而且不兼容多语言环境，Unicode 联盟开发了 Unicode 标准。

Unicode 标准涵盖了世界上的所有字符、标点和符号。

不论是何种平台、程序或语言，Unicode 都能够进行文本数据的处理、存储和交换。

--------

## Unicode 联盟

Unicode 联盟开发了 Unicode 标准。他们的目标是用标准的 Unicode 转换格式 (UTF) 来取代现有的字符集。

Unicode 标准已经获得了成功，在 XML、Java、ECMAScript (JavaScript)、LDAP、CORBA 3.0、WML 中，Unicode 已经得到了实现。在许多操作系统以及所有的现代浏览器中，Unicode 同样得到了支持。

Unicode 联盟与领导性的标准发展组织进行合作，比如 ISO、W3C 以及 ECMA。

Unicode 可以被不同的字符集兼容。最常用的编码方式是 UTF-8 和 UTF-16：

| 字符集 | 描述 |
| ---- | ---- |
| UTF-8 | UTF8 中的字符可以是 1-4 个字节长。UTF-8 可以表示 Unicode 标准中的任意字符。UTF-8 向后兼容 ASCII。UTF-8 是网页和电子邮件的首选编码。 |
| UTF-16 | 16 比特的 Unicode 转换格式是一种 Unicode 可变字符编码，能够对全部 Unicode 指令表进行编码。UTF-16 主要被用于操作系统和环境中，比如微软的 Windows 2000/XP/2003/Vista/CE 以及 Java 和 .NET 字节代码环境。 |

**提示：**  最前面的 256 个 Unicode 字符集字符对应于 256 个 ISO-8859-1 字符。

**提示：**  所有 HTML 4 处理器均已支持 UTF-8，而所有 XHTML 和 XML 处理器支持 UTF-8 和 UTF-16！

---
title: "FormatFamilies"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示系统中可用的不同格式族。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

表示系统中可用的不同格式族。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [EBook](#EBook) | 表示 eBook 格式系列。 |
|
|  | [Email](#Email) | 表示 Email 格式系列。 |
|
|  | [FixedLayout](#FixedLayout) | 表示 Fixed Layout 格式系列。 |
|
|  | [Presentation](#Presentation) | 表示 Presentation 格式系列。 |
|
|  | [Spreadsheet](#Spreadsheet) | 表示 Spreadsheet 格式系列。 |
|
|  | [Textual](#Textual) | 表示 Textual 格式系列。 |
|
|  | [WordProcessing](#WordProcessing) | 表示 Word Processing 格式系列。 |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


表示 eBook 格式系列。
了解更多关于 Mobi 格式
[here](../https://docs.fileformat.com/ebook/mobi/)
,
关于 AZW3 格式
[here](../https://docs.fileformat.com/ebook/azw3/)
,
以及关于 ePub 格式
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


表示 Email 格式系列。
了解更多关于电子邮件格式
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


表示 Fixed Layout 格式系列。
各种文档查看或发布应用程序允许用户打开（Adobe Acrobat，XPS Viewer），有时编辑（Adobe InDesign）特定格式的文档。
这些应用程序通常生成所谓的 \\u201c固定页\\u201d 格式文档。
此文档格式精确描述了文档\\u2019 内容在每页上的放置位置。
在内部，PDF 或 XPS 格式包含每页的描述，以及绘图指令，指定页面上内容的布局。
这类似于图像格式，描述内容以栅格或矢量形式显示的位置。


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


表示 Presentation 格式系列。
了解更多关于演示文稿格式
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


表示 Spreadsheet 格式系列。
所有二进制、XML 和文本电子表格格式（不包括所有使用逗号、制表符、分号等分隔符的文本分隔格式，如 CSV、TSV、分号分隔等），可用于保存工作簿。


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


表示 Textual 格式系列。
封装所有文本（基于文本）格式，包括标记语言（XML、HTML）等。


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


表示 Word Processing 格式系列。
了解更多关于文字处理格式
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME 代码取自以下资源：https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />




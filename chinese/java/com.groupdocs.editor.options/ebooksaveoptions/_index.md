---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为在所有支持的电子书格式 ePub、MOBI 和 AZW3 中生成和保存文档指定自定义选项。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

允许指定用于在所有支持的电子书格式中生成和保存文档的自定义选项：ePub、MOBI 和 AZW3。

<br />

*** ** * ** ***

支持的电子书格式：

1. [ePub](../https://docs.fileformat.com/ebook/epub/)（电子出版物）
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/)（Kindle 格式 8t）

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | 此无参数构造函数创建一个 EbookSaveOptions 实例，使用 ePub 输出格式（随后可通过以下方式修改） |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) 属性)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | 创建一个 [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) 实例，使用指定的强制性电子书输出格式，其他所有参数均为默认值 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | 指定拆分电子书文件的标题最大层级。 |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | 指定拆分电子书文件的标题最大层级。 |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 指定是否在生成的文件中导出内置和自定义文档属性。 |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 指定是否在生成的文件中导出内置和自定义文档属性。 |
|
|  | [getOutputFormat()](#getOutputFormat--) | 指定生成的电子书文件的格式：IDPF ePub、MOBI 或 AZW3。 |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | 指定生成的电子书文件的格式：IDPF ePub、MOBI 或 AZW3。 |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


此无参数构造函数创建一个 EbookSaveOptions 实例，使用 ePub 输出格式（随后可通过以下方式修改）
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) 属性)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


创建一个 [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) 实例，使用指定的强制性电子书输出格式，其他所有参数均为默认值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | 强制性输出格式，电子书应保存的格式 |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


指定拆分电子书文件的标题最大层级。默认值为
2
.
将其设置为
0
将禁用拆分，因此电子书的所有内容将被合并到生成文件中的单个包中。

<br />

*** ** * ** ***

当此属性设置为 1 到 9 之间的值时，文档将在使用以下格式的段落处拆分

**Heading 1**
,
**Heading 2**
,
**Heading 3**
等样式，直至指定的标题级别。

默认情况下，仅
**Heading 1**
和
**Heading 2**
段落会导致文档被拆分。
将此属性设置为零（或小于零）将导致文档根本不会在标题段落处拆分。

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


指定拆分电子书文件的标题最大层级。默认值为
2
.
将其设置为
0
将禁用拆分，因此电子书的所有内容将被合并到生成文件中的单个包中。

<br />

*** ** * ** ***

当此属性设置为 1 到 9 之间的值时，文档将在使用以下格式的段落处拆分

**Heading 1**
,
**Heading 2**
,
**Heading 3**
等样式，直至指定的标题级别。

默认情况下，仅
**Heading 1**
和
**Heading 2**
段落会导致文档被拆分。
将此属性设置为零（或小于零）将导致文档根本不会在标题段落处拆分。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


指定是否在生成的文件中导出内置和自定义文档属性。
默认值为
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


指定是否在生成的文件中导出内置和自定义文档属性。
默认值为
false
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


指定生成的电子书文件的格式：IDPF ePub、MOBI 或 AZW3。


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


指定生成的电子书文件的格式：IDPF ePub、MOBI 或 AZW3。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |


---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定用于生成和保存聚合 HTML 文档的 MHTML MIME 封装的自定义选项"
type: docs
weight: 26
url: /zh/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

允许指定用于生成和保存 MHTML（MIME 封装聚合 HTML 文档）文档的自定义选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | 指定是否使用 CID（Content-ID）URL 来引用包含在 MHTML 文档中的资源（图像、字体、CSS）。 |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | 指定是否使用 CID（Content-ID）URL 来引用包含在 MHTML 文档中的资源（图像、字体、CSS）。 |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 指定是否将内置和自定义文档属性导出到 MHTML。 |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 指定是否将内置和自定义文档属性导出到 MHTML。 |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | 指定是否将语言信息导出到 MHTML。 |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | 指定是否将语言信息导出到 MHTML。 |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


指定是否使用 CID（Content-ID）URL 来引用包含在 MHTML 文档中的资源（图像、字体、CSS）。默认值为
false
.

<br />

*** ** * ** ***


默认情况下，MHTML 文档中的资源通过文件名（例如 \"image.png\"）进行引用，这些文件名会与 MIME 部分的 \"Content-Location\" 头匹配。此选项启用一种替代方法，将资源文件的引用写为 CID（Content-ID）URL（例如 \"cid:image.png\"），并与 \"Content-ID\" 头匹配。


理论上，两种引用方式之间应该没有区别，任意一种都应在任何浏览器或邮件客户端中正常工作。但在实际使用中，某些客户端无法通过文件名获取资源。如果您的浏览器或邮件客户端拒绝加载 MHTML 文档中包含的资源（图像不显示或 CSS 样式未加载），请尝试使用 CID URL 导出文档。

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


指定是否使用 CID（Content-ID）URL 来引用包含在 MHTML 文档中的资源（图像、字体、CSS）。默认值为
false
.

<br />

*** ** * ** ***


默认情况下，MHTML 文档中的资源通过文件名（例如 \"image.png\"）进行引用，这些文件名会与 MIME 部分的 \"Content-Location\" 头匹配。此选项启用一种替代方法，将资源文件的引用写为 CID（Content-ID）URL（例如 \"cid:image.png\"），并与 \"Content-ID\" 头匹配。


理论上，两种引用方式之间应该没有区别，任意一种都应在任何浏览器或邮件客户端中正常工作。但在实际使用中，某些客户端无法通过文件名获取资源。如果您的浏览器或邮件客户端拒绝加载 MHTML 文档中包含的资源（图像不显示或 CSS 样式未加载），请尝试使用 CID URL 导出文档。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


指定是否将内置和自定义文档属性导出到 MHTML。默认值为
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


指定是否将内置和自定义文档属性导出到 MHTML。默认值为
false
.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


指定是否将语言信息导出到 MHTML。默认值为
false
.

<br />

*** ** * ** ***

当此属性设置为 true 时，GroupDocs.Editor 会在指定语言的文档元素上输出 lang HTML 属性。这可能需要用于保留语言相关的语义。

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


指定是否将语言信息导出到 MHTML。默认值为
false
.

<br />

*** ** * ** ***

当此属性设置为 true 时，GroupDocs.Editor 会在指定语言的文档元素上输出 lang HTML 属性。这可能需要用于保留语言相关的语义。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |


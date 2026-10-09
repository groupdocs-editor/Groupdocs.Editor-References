---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定用于生成和保存 PDF 可移植文档格式文档的自定义选项"
type: docs
weight: 31
url: /zh/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

允许指定用于生成和保存 PDF（Portable
Document Format）文档

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。 |
|
|  | [getCompliance()](#getCompliance--) | 指定输出文档的 PDF 标准合规级别。 |
|
|  | [setCompliance(int value)](#setCompliance-int-) | 指定输出文档的 PDF 标准合规级别。 |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 负责将原始文档中使用的字体资源嵌入生成的 PDF 文档中。 |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 负责将原始文档中使用的字体资源嵌入生成的 PDF 文档中。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。 |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。
如果为 NULL 或为空，则不会对文档应用密码。否则，文档将使用 RC4（密钥长度 128 位）加密。
默认是 NULL \u2014 未应用密码。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。
如果为 NULL 或为空，则不会对文档应用密码。否则，文档将使用 RC4（密钥长度 128 位）加密。
默认是 NULL \u2014 未应用密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


指定输出文档的 PDF 标准合规级别。默认是 PdfCompliance.Pdf17。


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


指定输出文档的 PDF 标准合规级别。默认是 PdfCompliance.Pdf17。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


负责将原始文档中使用的字体资源嵌入生成的 PDF 文档中。默认不嵌入任何字体（NotEmbed）。


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


负责将原始文档中使用的字体资源嵌入生成的 PDF 文档中。默认不嵌入任何字体（NotEmbed）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已禁用）。


**Returns:**
布尔
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已禁用）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |


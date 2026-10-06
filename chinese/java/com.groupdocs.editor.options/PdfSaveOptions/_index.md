---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为生成和保存 PDF 可移植文档格式文档指定自定义选项"
type: docs
weight: 31
url: /zh/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

允许为生成和保存 PDF（可移植
文档格式）文档

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
|  | [getFontEmbedding()](#getFontEmbedding--) | 负责将字体资源嵌入生成的 PDF 文档中，这些资源在原始文档中使用。 |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 负责将字体资源嵌入生成的 PDF 文档中，这些资源在原始文档中使用。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。 |
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
默认情况下为 NULL \u2014 不会应用密码。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。
如果为 NULL 或为空，则不会对文档应用密码。否则，文档将使用 RC4（密钥长度 128 位）加密。
默认情况下为 NULL \u2014 不会应用密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


指定输出文档的 PDF 标准合规级别。默认值为 PdfCompliance.Pdf17。


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


指定输出文档的 PDF 标准合规级别。默认值为 PdfCompliance.Pdf17。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


负责将字体资源嵌入生成的 PDF 文档中，这些资源在原始文档中使用。默认情况下不嵌入任何字体（NotEmbed）。


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


负责将字体资源嵌入生成的 PDF 文档中，这些资源在原始文档中使用。默认情况下不嵌入任何字体（NotEmbed）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已被禁用）。


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已被禁用）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |


---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定用于生成和保存编辑后符合 WordProcessing 标准的文档的自定义选项"
type: docs
weight: 48
url: /zh/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

允许指定用于生成和保存的自定义选项
编辑后的符合 WordProcessing 标准的文档


*** ** * ** ***

当存在 EditableDocument 类的实例且其中包含已编辑的文档内容，需要将此内容保存为 WordProcessing 格式的新文档时，将使用 WordProcessingSaveOptions。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | 此无参数构造函数创建一个 WordProcessingSaveOptions 的新实例，默认使用 DOCX 输出格式（随后可以通过 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) 属性)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | 使用指定的 |
必需的 WordProcessing 输出格式，其他所有参数保持不变
默认
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 允许启用或禁用分页，分页将用于保存 |
文档。
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 允许启用或禁用分页，分页将用于保存 |
文档。
|
|  | [getPassword()](#getPassword--) | 允许指定、修改、获取或删除密码，密码将 |
用于对生成的 WordProcessing 文档进行编码。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改、获取或删除密码，密码将 |
用于对生成的 WordProcessing 文档进行编码。
|
|  | [getOutputFormat()](#getOutputFormat--) | 允许指定 WordProcessing 格式，格式将用于保存 |
文档
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | 允许指定 WordProcessing 格式，格式将用于保存 |
文档
|
|  | [getLocale()](#getLocale--) | 允许为 WordProcessing 设置覆盖默认区域设置（语言） |
文档，该设置将在创建期间应用。
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | 允许为 WordProcessing 设置覆盖默认区域设置（语言） |
文档，该设置将在创建期间应用。
|
|  | [getLocaleBi()](#getLocaleBi--) | 允许为 WordProcessing 文档设置覆盖区域设置（语言） |
用于 RTL（从右到左）文本，该设置将在其
创建时应用。
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | 允许为 WordProcessing 文档设置覆盖区域设置（语言） |
用于 RTL（从右到左）文本，该设置将在其
创建时应用。
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | 允许覆盖 WordProcessing 文档的区域设置（语言） |
用于东亚文本，该设置将在创建期间应用。
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | 允许覆盖 WordProcessing 文档的区域设置（语言） |
用于东亚文本，该设置将在创建期间应用。
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在从 |
HTML 生成文档时启用内存优化机制，这会以降低性能为代价来减少内存使用。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在从 |
HTML 生成文档时启用内存优化机制，这会以降低性能为代价来减少内存使用。
|
|  | [getProtection()](#getProtection--) | 允许控制并应用文档保护选项，针对 |
任何格式的 WordProcessing 文档，该文档支持
保护。
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | 允许控制并应用文档保护选项，针对 |
任何格式的 WordProcessing 文档，该文档支持
保护。
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 负责将字体资源嵌入输出的 WordProcessing |
文档。
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 负责将字体资源嵌入输出的 WordProcessing |
文档。
|
|  | [deepClone()](#deepClone--) | 创建并返回此实例的完整副本， |
WordProcessingSaveOptions 类
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


此无参数构造函数创建一个 WordProcessingSaveOptions 的新实例，默认使用 DOCX 输出格式（随后可以通过
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) 属性)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


使用指定的
必需的 WordProcessing 输出格式，其他所有参数保持不变
默认


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | 强制输出格式，WordProcessing 文档应以此格式保存 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


允许启用或禁用分页，分页将用于保存
文档。如果原始文档在分页模式下打开并编辑
模式下，此选项也应启用。默认情况下禁用。


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


允许启用或禁用分页，分页将用于保存
文档。如果原始文档在分页模式下打开并编辑
模式下，此选项也应启用。默认情况下禁用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改、获取或删除密码，密码将
用于对生成的 WordProcessing 文档进行编码。指定 NULL 或
空字符串以删除（清除）密码。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改、获取或删除密码，密码将
用于对生成的 WordProcessing 文档进行编码。指定 NULL 或
空字符串以删除（清除）密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


允许指定 WordProcessing 格式，格式将用于保存
文档


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


允许指定 WordProcessing 格式，格式将用于保存
文档


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


允许为 WordProcessing 设置覆盖默认区域设置（语言）
文档，在其创建期间将被应用。当未
指定（默认值），MS Word（或其他程序）将检测（或
选择）文档语言区域，根据其自身设置或其他
因素。


*** ** * ** ***

此选项强制将指定的语言区域应用于文档中的整体文本。如果文档包含用不同语言编写的不同文本部分，请勿使用此选项。

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


允许为 WordProcessing 设置覆盖默认区域设置（语言）
文档，在其创建期间将被应用。当未
指定（默认值），MS Word（或其他程序）将检测（或
选择）文档语言区域，根据其自身设置或其他
因素。

*** ** * ** ***


此选项强制将指定的语言区域应用于整体文本中
文档中。如果文档包含不同部分的
文本，这些文本使用不同语言编写。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


允许为 WordProcessing 文档设置覆盖区域设置（语言）
用于 RTL（从右到左）文本，该设置将在其
创建时。当未指定（默认值），MS Word（或其他
程序）将检测（或选择）文档的 RTL 语言区域，根据其
自身设置或其他因素。

*** ** * ** ***


此选项强制将指定的语言区域应用于整体 RTL 文本
在文档中。如果文档包含不同部分的
文本，这些文本使用不同语言编写。


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


允许为 WordProcessing 文档设置覆盖区域设置（语言）
用于 RTL（从右到左）文本，该设置将在其
创建时。当未指定（默认值），MS Word（或其他
程序）将检测（或选择）文档的 RTL 语言区域，根据其
自身设置或其他因素。

*** ** * ** ***


此选项强制将指定的语言区域应用于整体 RTL 文本
在文档中。如果文档包含不同部分的
文本，这些文本使用不同语言编写。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


允许覆盖 WordProcessing 文档的区域设置（语言）
针对东亚文本，这将在其创建期间被应用。当
未指定（默认值），MS Word（或其他程序）将检测
（或选择）文档的东亚语言区域，根据其自身设置
或其他因素。

*** ** * ** ***


此选项强制将指定的语言区域应用于整体
东亚文本在文档中。如果文档包含
不同部分的文本，这些文本使用不同的
语言。


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


允许覆盖 WordProcessing 文档的区域设置（语言）
针对东亚文本，这将在其创建期间被应用。当
未指定（默认值），MS Word（或其他程序）将检测
（或选择）文档的东亚语言区域，根据其自身设置
或其他因素。

*** ** * ** ***


此选项强制将指定的语言区域应用于整体
东亚文本在文档中。如果文档包含
不同部分的文本，这些文本使用不同的
语言。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在从
HTML 生成文档时启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设置为 true 可以显著降低内存消耗
在生成大型文档时，以较慢的保存时间为代价。
默认值为 false（为了更好的内存优化已禁用
性能）。


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在从
HTML 生成文档时启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设置为 true 可以显著降低内存消耗
在生成大型文档时，以较慢的保存时间为代价。
默认值为 false（为了更好的内存优化已禁用
性能）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


允许控制并应用文档保护选项，针对
任何格式的 WordProcessing 文档，该文档支持
保护。默认值为 NULL - 将不使用文档保护。


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


允许控制并应用文档保护选项，针对
任何格式的 WordProcessing 文档，该文档支持
保护。默认值为 NULL - 将不使用文档保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


负责将字体资源嵌入输出的 WordProcessing
文档。默认情况下不嵌入任何字体（NotEmbed）。


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


负责将字体资源嵌入输出的 WordProcessing
文档。默认情况下不嵌入任何字体（NotEmbed）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


创建并返回此实例的完整副本，
WordProcessingSaveOptions 类


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance


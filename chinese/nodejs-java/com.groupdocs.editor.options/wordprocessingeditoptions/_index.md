---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为所有支持的 WordProcessing 符合 Words 标准的格式（如 DOCX、RTF、ODT 等）指定自定义编辑选项"
type: docs
weight: 44
url: /zh/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

允许为所有支持的文档指定自定义编辑选项
WordProcessing（符合 Words 标准）格式，如 DOC(X)、RTF、ODT 等

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | 创建并返回一个新的 WordProcessingEditOptions 实例 |
类，其中所有选项均设置为默认值
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | 创建并返回一个新的 WordProcessingEditOptions 实例 |
具有指定分页且默认其他所有选项的类
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 允许在生成的 HTML 文档中启用或禁用分页。 |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 指定是否将语言信息导出到 HTML 标记中 |
以 'lang' HTML 属性的形式。
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 指定是否将语言信息导出到 HTML 标记中 |
以 'lang' HTML 属性的形式。
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | 获取或设置一个值，指示是否仅提取用于 |
文档文本内容中的字体资源。
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | 获取或设置一个值，指示是否仅提取用于 |
文档文本内容中的字体资源。
|
|  | [getFontExtraction()](#getFontExtraction--) | 负责提取在输入中使用的字体资源 |
WordProcessing 文档。
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | 负责提取在输入中使用的字体资源 |
WordProcessing 文档。
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | 允许指定一个类名，该类名将被放置到 'class' |
属性中每个 HTML 元素，表示输入中的某个字段
WordProcessing 文档。
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | 允许指定一个类名，该类名将被放置到 'class' |
属性中每个 HTML 元素，表示输入中的某个字段
WordProcessing 文档。
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | 控制将输入 WordProcessing 文档的样式和格式化数据存储在哪里：在外部样式表 ( |
false
) 或作为 HTML 标记中的内联样式 (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | 控制将输入 WordProcessing 文档的样式和格式化数据存储在哪里：在外部样式表 ( |
false
) 或作为 HTML 标记中的内联样式 (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


创建并返回一个新的 WordProcessingEditOptions 实例
类，其中所有选项均设置为默认值


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


创建并返回一个新的 WordProcessingEditOptions 实例
具有指定分页且默认其他所有选项的类


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | enablePagination | 布尔 | 分页标志，启用 HTML 输出，针对分页模式进行调整 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下
默认是禁用的（false）。


**Returns:**
布尔
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


允许在生成的 HTML 文档中启用或禁用分页。默认情况下
默认是禁用的（false）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


指定是否将语言信息导出到 HTML 标记中
一种 'lang' HTML 属性的形式。此选项在往返转换时可能有用
多语言文档的转换。默认情况下已禁用
(false)。


**Returns:**
布尔
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


指定是否将语言信息导出到 HTML 标记中
一种 'lang' HTML 属性的形式。此选项在往返转换时可能有用
多语言文档的转换。默认情况下已禁用
(false)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


获取或设置一个值，指示是否仅提取用于
文档文本内容中的字体资源。
值： true 表示仅提取文档文本内容中使用的字体资源；否则为 false。默认值为 false。


*** ** * ** ***

并非所有在 WordProcessing 文档中使用的字体都 100% 直接使用（应用于某些文本）。可能出现字体在文档中被引用甚至已嵌入，但未应用于任何文本的情况。例如，某些字体可能附加到某个样式上，但该样式未应用于任何文本部分。此选项控制如何处理此类情况。

<br />



**Returns:**
布尔
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


获取或设置一个值，指示是否仅提取用于
文档文本内容中的字体资源。
值： true 表示仅提取文档文本内容中使用的字体资源；否则为 false。默认值为 false。


*** ** * ** ***

并非所有在 WordProcessing 文档中使用的字体都 100% 直接使用（应用于某些文本）。可能出现字体在文档中被引用甚至已嵌入，但未应用于任何文本的情况。例如，某些字体可能附加到某个样式上，但该样式未应用于任何文本部分。此选项控制如何处理此类情况。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


负责提取在输入中使用的字体资源
WordProcessing 文档。默认情况下不提取任何字体
(NotExtract)。


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


负责提取在输入中使用的字体资源
WordProcessing 文档。默认情况下不提取任何字体
(NotExtract)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


允许指定一个类名，该类名将被放置到 'class'
属性中每个 HTML 元素，表示输入中的某个字段
WordProcessing 文档。默认情况下为 NULL——'class' 属性不会
应用。


*** ** * ** ***

几乎所有来自 WordProcessing 格式系列的格式都包含字段——特定的文档实体，允许从用户获取输入数据。字段种类繁多：文本框、复选框、组合框、下拉列表、按钮、日期/时间选择器等。所有这些字段都会被转换为最合适的 HTML 结构和元素，并保留输入文档中存在的用户数据。在特定使用场景下，仅需在客户端收集已输入的数据，而不是编辑整个文档内容。为此，需要以某种方式标识输入控件，以便在客户端获取其数据。此属性允许指定一个类名，该类名将应用于 HTML 标记中的每个输入控件，从而使客户端代码能够遍历 HTML 文档结构并收集数据。

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


允许指定一个类名，该类名将被放置到 'class'
属性中每个 HTML 元素，表示输入中的某个字段
WordProcessing 文档。默认情况下为 NULL——'class' 属性不会
应用。


*** ** * ** ***

几乎所有来自 WordProcessing 格式系列的格式都包含字段——特定的文档实体，允许从用户获取输入数据。字段种类繁多：文本框、复选框、组合框、下拉列表、按钮、日期/时间选择器等。所有这些字段都会被转换为最合适的 HTML 结构和元素，并保留输入文档中存在的用户数据。在特定使用场景下，仅需在客户端收集已输入的数据，而不是编辑整个文档内容。为此，需要以某种方式标识输入控件，以便在客户端获取其数据。此属性允许指定一个类名，该类名将应用于 HTML 标记中的每个输入控件，从而使客户端代码能够遍历 HTML 文档结构并收集数据。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


控制将输入 WordProcessing 文档的样式和格式化数据存储在哪里：在外部样式表 (
false
) 或作为 HTML 标记中的内联样式 (
true
). 默认情况下使用外部样式 (
false
).


**Returns:**
布尔
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


控制将输入 WordProcessing 文档的样式和格式化数据存储在哪里：在外部样式表 (
false
) 或作为 HTML 标记中的内联样式 (
true
). 默认情况下使用外部样式 (
false
).


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |


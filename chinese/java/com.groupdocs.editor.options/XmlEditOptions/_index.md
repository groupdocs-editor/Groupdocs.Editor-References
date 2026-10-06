---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定加载 XML（可扩展标记语言）文档并将其转换为 HTML 的自定义选项"
type: docs
weight: 51
url: /zh/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

允许指定加载 XML（可扩展标记语言）的自定义选项
文档并将其转换为 HTML

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 文本文件的字符编码，将用于其 |
打开。
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 文本文件的字符编码，将用于其 |
打开。
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | 允许启用或禁用修复损坏 XML 结构的机制。 |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | 允许启用或禁用修复损坏 XML 结构的机制。 |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | 允许启用 URI 识别算法 |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | 允许启用 URI 识别算法 |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | 允许启用属性中电子邮件地址的识别算法 |
值
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | 允许启用属性中电子邮件地址的识别算法 |
值
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | 允许启用对内部标签中尾随空格的截断 |
文本。
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | 允许启用对内部标签中尾随空格的截断 |
文本。
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | 允许为属性值指定引号类型（单引号或双引号）。 |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 允许为属性值指定引号类型（单引号或双引号）。 |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | 允许调整在 HTML 中呈现时应用于 XML 结构的 XML 高亮显示。 |
|
|  | [getFormatOptions()](#getFormatOptions--) | 允许调整在 HTML 中呈现时应用于 XML 结构的 XML 格式化。 |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


文本文件的字符编码，将用于其
打开。默认值为 null \\u2014 将使用内部文档编码。


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


文本文件的字符编码，将用于其
打开。默认值为 null \\u2014 将使用内部文档编码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


允许启用或禁用修复损坏 XML 结构的机制。
默认情况下已禁用（false）。

*** ** * ** ***


默认情况下，仅适用于正确有效且结构良好的 XML 文档
可接受。当启用此选项时，GroupDocs.Editor 将尝试修复
如果可能，损坏的 XML 结构。


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


允许启用或禁用修复损坏 XML 结构的机制。
默认情况下已禁用（false）。

*** ** * ** ***


默认情况下，仅适用于正确有效且结构良好的 XML 文档
可接受。当启用此选项时，GroupDocs.Editor 将尝试修复
如果可能，损坏的 XML 结构。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


允许启用 URI 识别算法


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


允许启用 URI 识别算法


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


允许启用属性中电子邮件地址的识别算法
值


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


允许启用属性中电子邮件地址的识别算法
值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


允许启用对内部标签中尾随空格的截断
文本。默认情况下已禁用（false） \\u2014 将保留尾随空格
保留。


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


允许启用对内部标签中尾随空格的截断
文本。默认情况下已禁用（false） \\u2014 将保留尾随空格
保留。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


允许为属性值指定引号类型（单引号或双引号）。双引号为默认值。


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


允许为属性值指定引号类型（单引号或双引号）。双引号为默认值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


允许调整在 HTML 中呈现时应用于 XML 结构的 XML 高亮显示。使用默认高亮并且可以调整。不能为空。


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


允许调整在 HTML 中呈现时应用于 XML 结构的 XML 格式化。使用默认格式并且可以调整。不能为空。


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)

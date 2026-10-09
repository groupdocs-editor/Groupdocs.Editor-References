---
title: "QuoteType"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示引号字符——单引号和双引号"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

表示引号字符——单引号 (') 和双引号 (\")

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | 单引号（U+0027 APOSTROPHE 字符） |
|
|  | [DoubleQuote](#DoubleQuote) | 双引号（U+0022 QUOTATION MARK 字符） |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCode()](#getCode--) | 当前字符的代码点（U+0027 或 U+0022） |
|
|  | [getCharacter()](#getCharacter--) | 要加引号的字符 |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML 编码字符 |
|
|  | [toString()](#toString--) | 根据当前值返回 \"SingleQuote\" 或 \"DoubleQuote\" 字符串 |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 指示此引号类型实例是否等于指定的对象 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 指示此引号类型实例是否等于指定的未强制转换对象 |
|
|  | [hashCode()](#hashCode--) | 返回此字符的哈希码 |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 检查两个 \"QuoteType\" 值是否相等 |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 检查两个 \"QuoteType\" 值是否不相等 |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 将指定的 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 实例转换为 char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | 将特定的 char 转换为相应的 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)，如果转换无效则抛出异常 |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


单引号（U+0027 APOSTROPHE 字符）


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


双引号（U+0022 QUOTATION MARK 字符）


### getCode() {#getCode--}
```
public final int getCode()
```


当前字符的代码点（U+0027 或 U+0022）


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


要加引号的字符


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML 编码字符


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


根据当前值返回 \"SingleQuote\" 或 \"DoubleQuote\" 字符串


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


指示此引号类型实例是否等于指定的对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要检查的其他 QuoteType 实例 |
|

**Returns:**
boolean - 如果相等则为 true，若不相等则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示此引号类型实例是否等于指定的未强制转换对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 未转换的对象，期望其为 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 类型 |
|

**Returns:**
boolean - 如果相等则为 true，若不相等则为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此字符的哈希码


**Returns:**
int - 哈希码，作为有符号整数

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


检查两个 \"QuoteType\" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要检查的第一个值 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


检查两个 \"QuoteType\" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要检查的第一个值 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 false，否则为 true

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


将指定的 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 实例转换为 char


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 要转换的 QuoteType 实例 |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


将特定的 char 转换为相应的 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)，如果转换无效则抛出异常


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 字符 | char | 单引号（U+0027 APOSTROPHE）或双引号（U+0022 QUOTATION MARK）字符。如果指定其他字符，将抛出异常。 |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)

---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示文本装饰线的类型：underline、underscore、overline、line-through、strikethrough。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

表示文本装饰线的类型：下划线（underscore）、上划线和删除线（strikethrough）。

<br />

*** ** * ** ***

不可变结构体。类似于 https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | 不产生文本装饰。 |
|
|  | [Underline](#Underline) | 每行文本都有下划线。 |
|
|  | [Overline](#Overline) | 每行文本上方都有一条线。 |
|
|  | [LineThrough](#LineThrough) | 每行文本中间都有一条线。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 指示此实例是否具有初始值 \\\\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | 指示是否启用了下划线（underscore） |
|
|  | [isOverline()](#isOverline--) | 指示是否启用了上划线 |
|
|  | [isLineThrough()](#isLineThrough--) | 指示是否启用了删除线（strikethrough） |
|
|  | [getValue()](#getValue--) | 返回此实例中所有标志的文本值 |
|
|  | [toString()](#toString--) | 返回此实例中所有标志的文本值 |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 指示此 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例是否等于指定的 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 指示此 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例是否等于未强制转换的指定值 |
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码 |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 检查两个 "TextDecorationLineType" 值是否相等 |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 检查两个 "TextDecorationLineType" 值是否不相等 |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | 创建并返回一个带有标志的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例，这些标志由指定的参数定义 |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | 尝试解析指定的字符串并返回有效的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例 |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 合并（合并）两个指定的线类型并生成新的结果线类型，其中标志被合并（并集） |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 从第一个指定的线类型中减去第二个指定的线类型，并生成新的结果线类型，仅保留第一个操作数中未在第二个操作数中出现的标志（差集） |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 返回第一个和第二个线类型的交集，仅在两个操作数中同时启用的标志才会被启用 |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | 将特定字节（8 位八位字节）转换为相应的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)，如果转换无效则抛出异常 |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


不产生文本装饰。初始值。


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


每行文本都有下划线。


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


每行文本上方都有一条线。


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


每行文本中间都有一条线。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


指示此实例是否具有初始值 \\\\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


指示是否启用了下划线（underscore）


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


指示是否启用了上划线


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


指示是否启用了删除线（strikethrough）


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


返回此实例中所有标志的文本值


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


返回此实例中所有标志的文本值


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


指示此 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例是否等于指定的


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 其他 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例 |
|

**Returns:**
布尔型 -  true  如果相等，  false  否则

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


指示此 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例是否等于未强制转换的指定值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | java.lang.Object | 其他 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例，已转换为对象 |
|

**Returns:**
布尔型 -  true  如果相等，  false  否则

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码


**Returns:**
int - 有符号整数哈希码

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


检查两个 "TextDecorationLineType" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 要检查的第一个操作数 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 要检查的第二个操作数 |
|

**Returns:**
布尔型 -  true  如果相等，  false  否则

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


检查两个 "TextDecorationLineType" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 要检查的第一个操作数 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 要检查的第二个操作数 |
|

**Returns:**
boolean -  true  如果不相等，则为 true；否则为 false

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


创建并返回一个带有标志的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例，这些标志由指定的参数定义


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isUnderline | boolean | 确定是否启用了下划线标志 |
|
|  | isOverline | boolean | 确定是否启用了上划线标志 |
|
|  | isLineThrough | boolean | 确定是否启用了删除线标志 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


尝试解析指定的字符串并返回有效的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 输入 | java.lang.String | 输入字符串 |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 结果。如果解析无效，则为 #None.None 值 |
|

**Returns:**
boolean -  true  如果解析成功，则为 true；失败时为 false

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


合并（合并）两个指定的线类型并生成新的结果线类型，其中标志被合并（并集）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第一个线类型操作数 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第二个线类型操作数 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


从第一个指定的线类型中减去第二个指定的线类型，并生成新的结果线类型，仅保留第一个操作数中未在第二个操作数中出现的标志（差集）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第一个线类型操作数 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第二个线类型操作数 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


返回第一和第二线类型的交集，仅在两个操作数中同时启用的标志才会被启用。该操作在所有运算符中具有最高优先级（高于并集和差集）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第一个线类型操作数 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 第二个线类型操作数 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


将特定字节（8 位八位字节）转换为相应的 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)，如果转换无效则抛出异常


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 八位字节 | 字节 | 一个 8 位八位字节（位字段），其中前 5 位为零，后 3 位指示标志 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)

---
title: "FontWeight"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "Font-weight 属性设置字体的粗细或加粗程度。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight 属性设置字体的粗细（或加粗程度）。可用的粗细取决于当前设置的 font-family。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Lighter](#Lighter) | 相对于父元素轻一档的字体粗细 |
|
|  | [Bolder](#Bolder) | 相对于父元素重一档的字体粗细 |
|
|  | [Normal](#Normal) | 正常字体粗细。 |
|
|  | [Bold](#Bold) | 粗体字体粗细。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 指示此 font-size 是否具有初始值（Medium） |
|
|  | [getNumber()](#getNumber--) | 返回一个数字——介于 1 到 1000（含）的整数值，描述字体的粗细，或者在当前粗细不是绝对值而是相对值时抛出异常 |
|
|  | [isAbsolute()](#isAbsolute--) | 指示此 font-weight 实例是否以整数形式存储字体粗细（加粗度）的绝对值 |
|
|  | [isRelative()](#isRelative--) | 指示此 font-weight 实例是否存储相对于父元素粗细的相对值 |
|
|  | [getValue()](#getValue--) | 返回此 font-weight 的字符串值 |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 确定指定的 FontWeight 实例是否相等 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此 FontWeight 实例是否等于指定的未转换实例 |
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码 |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 检查两个 "FontWeight" 值是否相等 |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 检查两个 "FontWeight" 值是否不相等 |
|
|  | [fromNumber(int number)](#fromNumber-int-) | 从指定的数字创建一个 font-weight |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | 尝试解析指定的字符串，并在成功时返回有效的 FontWeight 实例 |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


相对于父元素轻一档的字体粗细


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


相对于父元素重一档的字体粗细


### Normal {#Normal}
```
public static final FontWeight Normal
```


普通字体粗细。等同于 400。


### Bold {#Bold}
```
public static final FontWeight Bold
```


粗体字体粗细。等同于 700。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


指示此 font-size 是否具有初始值（Medium）


**Returns:**
布尔
### getNumber() {#getNumber--}
```
public final int getNumber()
```


返回一个数字——介于 1 到 1000（含）的整数值，描述字体的粗细，或者在当前粗细不是绝对值而是相对值时抛出异常


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


指示此 font-weight 实例是否以整数形式存储字体粗细（加粗度）的绝对值


**Returns:**
布尔
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


指示此 font-weight 实例是否存储相对于父元素粗细的相对值


**Returns:**
布尔
### getValue() {#getValue--}
```
public final String getValue()
```


返回此 font-weight 的字符串值


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


确定指定的 FontWeight 实例是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 用于检查相等性的其他 FontWeight 实例 |
|

**Returns:**
boolean - 如果相等则为 true，若不相等则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此 FontWeight 实例是否等于指定的未转换实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他未转换的 FontWeight 实例，可能为 null |
|

**Returns:**
布尔 - 相等时为 true，不相等、为 null 或其他类型时为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码


**Returns:**
int - 哈希码，作为有符号整数

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


检查两个 "FontWeight" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 要检查的第一个值 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


检查两个 "FontWeight" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 要检查的第一个值 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 false，否则为 true

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


从指定的数字创建一个 font-weight


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | number | int | 无符号整数，必须在 [1..1000] 范围内 |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


尝试解析指定的字符串，并在成功时返回有效的 FontWeight 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 输入 | java.lang.String | 要解析的输入字符串 |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 成功时返回有效的 FontWeight 值，失败时返回 #Normal.Normal |
|

**Returns:**
boolean - 解析成功为 true，失败为 false


---
title: "FontStyle"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "定义字体应如何使用其字体族中的普通、斜体或倾斜体进行样式设置。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

定义字体应如何使用其 font-family 中的普通、斜体或倾斜体进行样式设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Normal](#Normal) | 选择在字体族中被归类为普通的字体。 |
|
|  | [Italic](#Italic) | 选择被归类为斜体的字体。 |
|
|  | [Oblique](#Oblique) | 选择被归类为倾斜体的字体。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 指示此 font-style 是否具有初始值（Normal） |
|
|  | [getValue()](#getValue--) | 返回此字体样式的字符串值 |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 确定此 font-style 实例是否等于指定的对象 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此 font-style 实例是否等于未强制转换的指定对象 |
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码 |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 检查两个 "FontStyle" 值是否相等 |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 检查两个 "FontStyle" 值是否不相等 |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | 尝试将指定的关键字识别为 'font-style' 的正确关键字值，成功时返回它，失败时返回 NULL。 |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


选择在字体族中被归类为普通的字体。初始值。


### Italic {#Italic}
```
public static final FontStyle Italic
```


选择被归类为斜体的字体。如果没有可用的斜体版本，则使用被归类为倾斜体的版本。如果两者都不可用，则人工模拟该样式。


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


选择被归类为倾斜体的字体。如果没有可用的倾斜体版本，则使用被归类为斜体的版本。如果两者都不可用，则人工模拟该样式。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


指示此 font-style 是否具有初始值（Normal）


**Returns:**
布尔
### getValue() {#getValue--}
```
public final String getValue()
```


返回此字体样式的字符串值


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


确定此 font-style 实例是否等于指定的对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 其他 font-style 实例 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此 font-style 实例是否等于未强制转换的指定对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他未转换的 font-style 实例，可能为 null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


检查两个 "FontStyle" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 要检查的第一个值 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


检查两个 "FontStyle" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 要检查的第一个值 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 false，否则为 true

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


尝试将指定的关键字识别为 'font-style' 的正确关键字值，成功时返回它，失败时返回 NULL。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 关键字 | java.lang.String | 要解析的关键字 |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 结果，解析成功时为 #Normal.Normal，否则为 #Normal.Normal |
|

**Returns:**
布尔 - 解析成功时为 true，否则为 false


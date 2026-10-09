---
title: "字体大小"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示字体大小，作为一种特殊单位或长度值，指定字体的大小，历史上等同于大写字母 M 的宽度。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

表示字体大小，作为特殊单位或长度值，指定字体的大小（历史上是大写字母 "M" 的宽度）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Medium](#Medium) | 中等大小。 |
|
|  | [XxSmall](#XxSmall) | 极小的绝对尺寸 |
|
|  | [XSmall](#XSmall) | 中等偏小的绝对尺寸 |
|
|  | [Small](#Small) | 常规小的绝对尺寸 |
|
|  | [Large](#Large) | 常规大的绝对尺寸 |
|
|  | [XLarge](#XLarge) | 中等偏大的绝对尺寸 |
|
|  | [XxLarge](#XxLarge) | 极大的绝对尺寸 |
|
|  | [Larger](#Larger) | 更大的相对尺寸 - 字体相对于父元素的 font-size 将更大，大致按上述绝对尺寸关键字之间的比例进行。 |
|
|  | [Smaller](#Smaller) | 更小的相对尺寸 - 字体相对于父元素的 font-size 将更小，大致按上述绝对尺寸关键字之间的比例进行。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 指示此 font-size 是否具有初始值（Medium） |
|
|  | [getValue()](#getValue--) | 返回此字体大小的字符串值 |
|
|  | [isLengthDefined()](#isLengthDefined--) | 指示此 font-size 是否使用 [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 值定义 |
|
|  | [getLength()](#getLength--) | 如果此 font-size 是用长度定义，则返回长度值；否则抛出异常 |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | 指示此 font-size 是否基于用户默认字体大小（即 medium）使用绝对大小关键字定义 |
|
|  | [isRelativeSize()](#isRelativeSize--) | 指示此 font-size 是否使用相对大小关键字定义。 |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 确定此 font-size 实例是否等于指定的值 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此 font-size 实例是否等于指定的未转换值 |
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码 |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 检查两个 "FontSize" 值是否相等 |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 检查两个 "FontSize" 值是否不相等 |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 根据指定的长度创建 font-size |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | 尝试将指定关键字识别为 'font-size' 的有效关键字值，成功则返回，失败则返回 NULL。 |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


中等大小。初始值。


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


极小的绝对尺寸


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


中等偏小的绝对尺寸


### Small {#Small}
```
public static final FontSize Small
```


常规小的绝对尺寸


### Large {#Large}
```
public static final FontSize Large
```


常规大的绝对尺寸


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


中等偏大的绝对尺寸


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


极大的绝对尺寸


### Larger {#Larger}
```
public static final FontSize Larger
```


更大的相对尺寸 - 字体相对于父元素的 font-size 将更大，大致按上述绝对尺寸关键字之间的比例进行。


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


更小的相对尺寸 - 字体相对于父元素的 font-size 将更小，大致按上述绝对尺寸关键字之间的比例进行。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


指示此 font-size 是否具有初始值（Medium）


**Returns:**
布尔
### getValue() {#getValue--}
```
public final String getValue()
```


返回此字体大小的字符串值


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


指示此 font-size 是否使用 [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 值定义


**Returns:**
布尔
### getLength() {#getLength--}
```
public final Length getLength()
```


如果此 font-size 是用长度定义，则返回长度值；否则抛出异常


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


指示此 font-size 是否基于用户默认字体大小（即 medium）使用绝对大小关键字定义


**Returns:**
布尔
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


指示此 font-size 是否使用相对大小关键字定义。字体相对于父元素的字体大小会更大或更小，大致按照区分绝对大小关键字的比例进行。


**Returns:**
布尔
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


确定此 font-size 实例是否等于指定的值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 其他 font-size 实例 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此 font-size 实例是否等于指定的未转换值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他未转换的 font-size 实例，可能为 null |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


检查两个 "FontSize" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 要检查的第一个值 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 true，否则为 false

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


检查两个 "FontSize" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 要检查的第一个值 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 要检查的第二个值 |
|

**Returns:**
布尔 - 相等时为 false，否则为 true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


根据指定的长度创建 font-size


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 长度值，不能无单位或为负数 |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


尝试将指定关键字识别为 'font-size' 的有效关键字值，成功则返回，失败则返回 NULL。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 关键字 | java.lang.String | 要解析的关键字 |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 解析成功时的结果，若不成功则为 #Medium.Medium |
|

**Returns:**
布尔 - 解析成功时为 true，否则为 false


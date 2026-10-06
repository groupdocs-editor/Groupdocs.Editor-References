---
title: "比例"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示一种 ratio CSS 数据类型，用于在媒体查询中描述宽高比，并通过表示两个无单位值（称为 numerator 和 denominator）之间的比例来描述栅格图像。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

表示一种 "ratio" CSS 数据类型，用于描述方面
媒体查询中的比例以及通过表示比例的栅格图像
在两个无单位值（称为 "numerator" 和 "denominator"）之间。不可变
结构体。


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Single](#Single) | 单一默认比例 1/1 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | 返回此 ratio 的 numerator |
|
|  | [getDenominator()](#getDenominator--) | 返回此 ratio 的 denominator |
|
|  | [calculate()](#calculate--) | 计算并返回此 ratio 为单个浮点数 |
|
|  | [getInverseRatio()](#getInverseRatio--) | 生成并返回此 ratio 的逆（倒数）ratio |
|
|  | [serializeDefault()](#serializeDefault--) | 将此 ratio 序列化为字符串并返回 |
|
|  | [toString()](#toString--) | 返回此 ratio 的字符串表示形式；相当于 |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | 确定此 ratio 是否具有默认值或为 "1/1"（单一） |
|
|  | [deepClone()](#deepClone--) | 返回此 ratio 的完整副本 |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 确定此实例是否与指定的 "Ratio" 实例相等 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 确定此实例是否等于指定的未强制转换对象， |
这可能是另一个 "Ratio" 实例
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 比较两个比例并返回一个布尔值，指示这两个是否匹配。 |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 比较两个比例并返回一个布尔值，指示这两个是否不 |
匹配。
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码，在其 |
生命周期内不可更改
|
|  | [create(int numerator, int denominator)](#create-int-int-) | 创建并返回一个 Ratio 实例，使用指定的分子和 |
分母
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


单一默认比例 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


返回此 ratio 的 numerator


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


返回此 ratio 的 denominator


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


计算并返回此 ratio 为单个浮点数


**Returns:**
double - 双精度浮点数

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


生成并返回此 ratio 的逆（倒数）ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


将此 ratio 序列化为字符串并返回


**Returns:**
java.lang.String - 以 "numerator/denominator" 格式表示的字符串

### toString() {#toString--}
```
public String toString()
```


返回此 ratio 的字符串表示形式；相当于
"SerializeDefault()"


**Returns:**
java.lang.String - 以 "numerator/denominator" 格式表示的字符串

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


确定此 ratio 是否具有默认值或为 "1/1"（单一）


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


返回此 ratio 的完整副本


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


确定此实例是否与指定的 "Ratio" 实例相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 其他 Ratio 实例，用于检查与此的相等性 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


确定此实例是否等于指定的未强制转换对象，
这可能是另一个 "Ratio" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 其他 | java.lang.Object | 其他 System.Object 实例，假定为 Ratio 类型，用于检查与此的相等性 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


比较两个比例并返回一个布尔值，指示这两个是否匹配。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 要使用的第一个比例。 |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 要使用的第二个比例。 |
|

**Returns:**
boolean - 如果两个比例相等则为 true，否则为 false。

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


比较两个比例并返回一个布尔值，指示这两个是否不
匹配。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 要使用的第一个比例。 |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 要使用的第二个比例。 |
|

**Returns:**
boolean - 如果两个比例不相等则为 true，否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码，在其
生命周期内不可更改


**Returns:**
int - 有符号 4 字节整数，对此实例是不可变的

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


创建并返回一个 Ratio 实例，使用指定的分子和
分母


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 分子 | int | 比例的分子。应为严格正整数。 |
|
|  | 分母 | int | 比例的分母。应为严格正整数。 |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance


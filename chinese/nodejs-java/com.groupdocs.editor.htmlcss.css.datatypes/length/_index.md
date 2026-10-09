---
title: "Length"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 CSS 长度值，可使用任何支持的单位，包括百分比和无单位类型。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

表示 CSS 长度值，可使用任何支持的单位，包括百分比
以及无单位类型。值可以是整数或浮点数、负数、零和
正数。不可变结构。

*** ** * ** ***


此类型涵盖以下 CSS 数据类型：

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Length()](#Length--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | 无单位整数零 - 默认值，与默认的无参数构造函数相同 |
构造函数
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | 通过指定的浮点数创建并返回 Length 类型的实例 |
以及单位
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | 通过指定的 double 数字创建并返回 Length 类型的实例 |
以及单位
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | 通过指定的整数创建并返回 Length 类型的实例 |
数字和单位
|
|  | [isUnitlessZero()](#isUnitlessZero--) | 确定此实例是否为无单位零。 |
|
|  | [isDefault()](#isDefault--) | 指示此 Length 实例是否具有默认值 \\u2014 无单位 |
零。
|
|  | [getUnitType()](#getUnitType--) | 返回此 Length 实例的单位类型。 |
|
|  | [isInteger()](#isInteger--) | 指示此 Length 实例的数值是否已 |
最初指定并存储为整数 (INT32) 数字
|
|  | [isFloat()](#isFloat--) | 指示此 Length 实例的数值是否已 |
最初指定并存储为浮点数 (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | 返回 Length 实例的浮点数值。 |
|
|  | [getIntegerValue()](#getIntegerValue--) | 返回此 Length 实例的整数数值，如果它是 |
内部存储为整数，或在它是
最初存储为浮点数。
|
|  | [isAbsolute()](#isAbsolute--) | 获取长度是否以绝对单位给出。 |
|
|  | [isRelative()](#isRelative--) | 获取长度是否以相对单位给出。 |
|
|  | [isZero()](#isZero--) | 确定此长度的数值是否为零 |
|
|  | [isNegative()](#isNegative--) | 确定此长度的数值是否为负数 |
|
|  | [isPositive()](#isPositive--) | 确定此长度的数值是否为正数 |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | 该值为无单位类型，但不是零——是正数或负数 |
number
|
|  | [toPixel()](#toPixel--) | 将长度转换为像素数（如果可能）。 |
|
|  | [to(int unit)](#to-int-) | 将长度转换为给定单位（如果可能）。 |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | 返回此长度在指定单位类型下的字符串表示。 |
|
|  | [serializeDefault()](#serializeDefault--) | 返回此长度在其原始本地 |
形式（如其存储方式），而不将长度值转换为其他
单位类型
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 定义此值是否等于另一个指定的长度 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此长度是否等于指定的对象 |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | 将给定的 Length 乘以给定的因子 |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 检查两个给定长度的相等性。 |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 检查两个给定长度的不等性。 |
|
|  | [hashCode()](#hashCode--) | 通过组合计算并返回此 Length 实例的哈希码 |
值和单位类型的哈希码
|
|  | [deepClone()](#deepClone--) | 返回此 Length 实例的完整副本 |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | 尝试解析指定的单位名称并返回相应的值 |
单位枚举。
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | 尝试将指定字符串解析为 Length 值，包括其 |
数值和单位名称
|
|  | [parse(String input)](#parse-java.lang.String-) | 解析并返回指定字符串为 Length 值，包括其 |
数值和单位名称，或在失败时抛出异常
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


无单位整数零 - 默认值，与默认的无参数构造函数相同
构造函数


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


通过指定的浮点数创建并返回 Length 类型的实例
以及单位


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | \>任意浮点数 (FP32) |
|
|  | 单位 | int | 任何有效的单位类型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


通过指定的 double 数字创建并返回 Length 类型的实例
以及单位


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 任意 double (FP64) 数字，将被转换为 float (FP32) |
|
|  | 单位 | int | 任何有效的单位类型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


通过指定的整数创建并返回 Length 类型的实例
数字和单位


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 任意整数 |
|
|  | 单位 | int | 任何有效的单位类型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


确定此实例是否为无单位零。无单位零
是此类型的默认值。等同于 IsDefault 属性。


**Returns:**
布尔
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


指示此 Length 实例是否具有默认值 \\u2014 无单位
零。等同于 IsUnitlessZero 属性。


**Returns:**
布尔
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


返回此 Length 实例的单位类型。


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


指示此 Length 实例的数值是否已
最初指定并存储为整数 (INT32) 数字


**Returns:**
布尔
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


指示此 Length 实例的数值是否已
最初指定并存储为浮点数 (FP32)


**Returns:**
布尔
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


返回 Length 实例的 float 数值。永不抛出
异常——如有必要，将 Integer 值转换为 Float。


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


返回此 Length 实例的整数数值，如果它是
内部存储为整数，或在它是
最初存储为浮点数。


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


获取长度是否以绝对单位给出。此类长度可能会
转换为像素。


**Returns:**
布尔
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


获取长度是否以相对单位给出。此类长度不能
转换为像素。


**Returns:**
布尔
### isZero() {#isZero--}
```
public final boolean isZero()
```


确定此长度的数值是否为零


**Returns:**
布尔
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


确定此长度的数值是否为负数


**Returns:**
布尔
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


确定此长度的数值是否为正数


**Returns:**
布尔
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


该值为无单位类型，但不是零——是正数或负数
number


**Returns:**
布尔
### toPixel() {#toPixel--}
```
public final float toPixel()
```


将长度转换为像素数量（如果可能）。如果当前
单位是相对的，则会抛出异常。


**Returns:**
float - 当前长度所表示的像素数量。

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


将长度转换为给定单位（如果可能）。如果当前或
给定单位是相对的，则会抛出异常。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 单位 | int | 要转换到的单位。 |
|

**Returns:**
float - 当前长度在给定单位中的值。

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


返回此长度在指定单位类型下的字符串表示。
数值将在对应单位类型更改时进行转换。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 单位 | int | 指定单位，在将此实例序列化为字符串之前应转换到该单位。应为有效单位。不能是无单位的。 |
|

**Returns:**
java.lang.String - 字符串表示

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


返回此长度在其原始本地
形式（如其存储方式），而不将长度值转换为其他
单位类型


**Returns:**
java.lang.String - 字符串实例

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


定义此值是否等于另一个指定的长度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 其他 Length 类型的实例 |
|

**Returns:**
boolean - 相等则为 true，否则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此长度是否等于指定的对象


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他 Length 类型的实例，已装箱为 System.Object 或任何其他抽象类型或接口 |
|

**Returns:**
boolean - 相等则为 true，否则为 false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


将给定的 Length 乘以给定的因子


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - 乘数 |
|
|  | 因子 | int | 任意整数 - 因子 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


检查两个给定长度的相等性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 左侧长度操作数。 |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 右侧长度操作数。 |
|

**Returns:**
boolean - 两个长度相等则为 true，否则为 false。

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


检查两个给定长度的不等性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 左侧长度操作数。 |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 右侧长度操作数。 |
|

**Returns:**
boolean - 两个长度不相等则为 true，否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


通过组合计算并返回此 Length 实例的哈希码
值和单位类型的哈希码


**Returns:**
int - 整数

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


返回此 Length 实例的完整副本


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


尝试解析指定的单位名称并返回相应的值
Unit 枚举。如果找不到合适的 LengthUnit，则返回 LengthUnit.Unitless。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | unitName | java.lang.String | 字符串，表示单位名称 |
|

**Returns:**
int - Unit 枚举的值，无论如何；若找不到合适的单位，则为 LengthUnit.Unitless

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


尝试将指定字符串解析为 Length 值，包括其
数值和单位名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 输入 | java.lang.String | 输入字符串，需解析 |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 输出参数，包含解析结果。如果解析不成功，则包含默认的 Length 值 \\u2014 一个无单位的零。 |
|

**Returns:**
布尔值 - 如果解析成功则为 True，解析失败则为 false

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


解析并返回指定字符串为 Length 值，包括其
数值和单位名称，或在失败时抛出异常


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 输入 | java.lang.String | 输入字符串，需解析 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance


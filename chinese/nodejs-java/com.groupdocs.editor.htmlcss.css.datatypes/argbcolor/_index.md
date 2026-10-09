---
title: "ArgbColor"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 ARGB 格式的单个颜色值，包含转换器和序列化器。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

表示 ARGB 格式的单个颜色值，包含转换器和序列化器。

<br />

*** ** * ** ***

此类型旨在用于（但不限于）CSS 操作。查看更多：https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | 从指定的红色、绿色、蓝色和 Alpha 通道创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值 |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | 从指定的红色、绿色、蓝色通道创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值，Alpha 通道为完全不透明 |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | 从单个值创建一个完全不透明 (A=255) 的颜色，该值将应用于所有通道 |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | 从指定的 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值 |
|
|  | [getValue()](#getValue--) | 获取颜色的 Int32 值。 |
|
|  | [getA()](#getA--) | 获取颜色的 alpha 部分。 |
|
|  | [getAlpha()](#getAlpha--) | 获取颜色的 alpha 部分，以百分比表示 (0..1)。 |
|
|  | [getR()](#getR--) | 获取颜色的红色部分。 |
|
|  | [getG()](#getG--) | 获取颜色的绿色部分。 |
|
|  | [getB()](#getB--) | 获取颜色的蓝色部分。 |
|
|  | [isEmpty()](#isEmpty--) | 未初始化的颜色 - 所有 4 个通道均设为 0。 |
|
|  | [isDefault()](#isDefault--) | 指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否为默认（透明） - 所有 4 个通道均设为 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | 指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否完全透明 - 其 Alpha 通道的值为最小值 (0)，因此其他 R、G、B 通道没有可见效果。 |
|
|  | [isTranslucent()](#isTranslucent--) | 指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否为半透明（既不完全透明，也不完全不透明） |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | 指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否完全不透明，且没有透明度（其 Alpha 通道为最大值） |
|
|  | [toSystemColor()](#toSystemColor--) | 将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例的值转换为 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 实例并返回 |
|
|  | [toRGBA()](#toRGBA--) | 将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为 'rgba' CSS 函数表示法 |
|
|  | [toRGB()](#toRGB--) | 将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为 'rgb' CSS 函数表示法 |
|
|  | [serializeDefault()](#serializeDefault--) | 根据透明度，将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为最合适的 CSS 函数表示法 |
|
|  | [toString()](#toString--) | 与 #serializeDefault.serializeDefault 相同 |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 比较两个颜色并返回一个布尔值，指示两者是否匹配。 |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 比较两个颜色并返回一个布尔值，指示两者是否不匹配。 |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 检查两个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色是否相等 |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | 检查两个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色是否相等 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 测试另一个对象是否等于此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例。 |
|
|  | [hashCode()](#hashCode--) | 返回定义当前颜色的哈希码。 |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


从指定的红色、绿色、蓝色和 Alpha 通道创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 红色 | int | 红色通道值 |
|
|  | 绿色 | int | 绿色通道值 |
|
|  | 蓝色 | int | 蓝色通道值 |
|
|  | alpha | int | Alpha 通道值 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


从指定的红色、绿色、蓝色通道创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值，Alpha 通道为完全不透明


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 红色 | int | 红色通道值 |
|
|  | 绿色 | int | 绿色通道值 |
|
|  | 蓝色 | int | 蓝色通道值 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


从单个值创建一个完全不透明 (A=255) 的颜色，该值将应用于所有通道


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | 字节 | 字节值，适用于红色、绿色和蓝色通道 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


从指定的 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 创建一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 值


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


获取颜色的 Int32 值。


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


获取颜色的 alpha 部分。


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


获取颜色的 alpha 部分，以百分比表示 (0..1)。


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


获取颜色的红色部分。


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


获取颜色的绿色部分。


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


获取颜色的蓝色部分。


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


未初始化的颜色 - 所有 4 个通道均设为 0。相当于默认和透明。


**Returns:**
布尔
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否为默认（透明） - 所有 4 个通道均设为 0


**Returns:**
布尔
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否完全透明 - 其 Alpha 通道的值为最小值 (0)，因此其他 R、G、B 通道没有可见效果。


**Returns:**
布尔
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否为半透明（既不完全透明，也不完全不透明）


**Returns:**
布尔
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


指示此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例是否完全不透明，且没有透明度（其 Alpha 通道为最大值）


**Returns:**
布尔
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例的值转换为 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 实例并返回


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为 'rgba' CSS 函数表示法


**Returns:**
java.lang.String - 使用 'rgba(r, g, b, a)' 格式的字符串

### toRGB() {#toRGB--}
```
public final String toRGB()
```


将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为 'rgb' CSS 函数表示法


**Returns:**
java.lang.String - 使用 'rgb(r, g, b)' 格式的字符串

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


根据透明度，将此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例序列化为最合适的 CSS 函数表示法


**Returns:**
java.lang.String - 使用 'rgba(r, g, b, a)' 或 'rgb(r, g, b)' 格式的字符串

### toString() {#toString--}
```
public String toString()
```


与 #serializeDefault.serializeDefault 相同


**Returns:**
java.lang.String - 与 #serializeDefault.serializeDefault 中的返回值相同

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


比较两个颜色并返回一个布尔值，指示两者是否匹配。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 要使用的第一种颜色。 |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 要使用的第二种颜色。 |
|

**Returns:**
boolean - 如果两个颜色相等则为 true，否则为 false。

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


比较两个颜色并返回一个布尔值，指示两者是否不匹配。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 要使用的第一种颜色。 |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 要使用的第二种颜色。 |
|

**Returns:**
boolean - 如果两个颜色不相等，则返回 true，否则返回 false。

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


检查两个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 另一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色 |
|

**Returns:**
boolean - 如果两个颜色相等，则返回 true，否则返回 false。

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


检查两个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | 另一个 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 颜色，转换为 ICssDataType |
|

**Returns:**
boolean - 如果两个颜色相等，则返回 true，否则返回 false。

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


测试另一个对象是否等于此 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 其他 | java.lang.Object | 用于测试的对象。 |
|

**Returns:**
boolean - 如果两个对象相等，则返回 true，否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回定义当前颜色的哈希码。


**Returns:**
int - 哈希码的整数值。


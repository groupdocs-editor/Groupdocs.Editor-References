---
title: "Dimensions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示以任意单位的栅格矩形图像的线性尺寸宽度和高度。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

表示一个栅格矩形的线性尺寸（宽度和高度）
图像，以任意单位。不可变结构体。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | 根据指定的宽度和高度创建一个新实例 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 返回图像的宽度 |
|
|  | [getHeight()](#getHeight--) | 返回图像的高度 |
|
|  | [isSquare()](#isSquare--) | 确定指定的 'Dimensions' 是否表示正方形，即 |
|
|  | [getArea()](#getArea--) | 返回面积（宽度 × 高度） |
|
|  | [isEmpty()](#isEmpty--) | 确定此 "Dimensions" 实例是否为空且为默认，即 |
|
|  | [getAspectRatio()](#getAspectRatio--) | 此尺寸的宽高比，计算方式为宽度/高度 |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | 创建并返回新的 "Dimensions" 实例，该实例按比例 |
从当前尺寸按指定宽度进行缩放
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | 创建并返回新的 "Dimensions" 实例，该实例按比例 |
从当前尺寸按指定高度进行缩放
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 确定此实例是否等于指定的 "Dimensions" |
实例
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的未转换对象， |
它可能是另一个 "Dimensions" 实例
|
|  | [hashCode()](#hashCode--) | 返回此实例的哈希码，在其 |
生命周期
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 检查两个 "Dimensions" 值是否相等，即 |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 检查两个 "Dimensions" 值是否不相等，即 |
|
|  | [toString()](#toString--) | 返回此 "Dimensions" 的字符串表示 |
|
|  | [deepClone()](#deepClone--) | 返回此实例的完整副本 |
|
|  | [getEmpty()](#getEmpty--) | 返回一个空的 Dimensions 实例 |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


根据指定的宽度和高度创建一个新实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 宽度 | int | 图像的宽度 |
|
|  | 高度 | int | 图像的高度 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


返回图像的宽度


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


返回图像的高度


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


确定指定的 'Dimensions' 是否为正方形，即如果
宽度等于高度


**Returns:**
布尔
### getArea() {#getArea--}
```
public final long getArea()
```


返回面积（宽度 × 高度）


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


确定此 "Dimensions" 实例是否为空且为默认，即
它未存储正确的宽度和高度


**Returns:**
布尔
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


此尺寸的宽高比，计算方式为宽度/高度


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


创建并返回新的 "Dimensions" 实例，该实例按比例
从当前尺寸按指定宽度进行缩放


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | targetWidth | int | 新的目标宽度，将出现在结果维度中 |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


创建并返回新的 "Dimensions" 实例，该实例按比例
从当前尺寸按指定高度进行缩放


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | targetHeight | int | 新的目标高度，将出现在结果维度中 |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


确定此实例是否等于指定的 "Dimensions"
实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 用于检查相等性的其他 \"Dimensions\" 实例 |
|

**Returns:**
boolean - 相等时为 True，不相等时为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的未转换对象，
它可能是另一个 "Dimensions" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他对象，可能是 \"Dimensions\" 类型，应与此对象检查相等性 |
|

**Returns:**
boolean - 相等时为 True，不相等时为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码，在其
生命周期


**Returns:**
int - 对此实例不可变的哈希码，作为有符号的 4 字节整数

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


检查两个 \"Dimensions\" 值是否相等，即它们具有相等的
宽度和高度，或两者均为空


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 要检查的第一个实例 |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 要检查的第二个实例 |
|

**Returns:**
boolean - 相等时为 True，不相等时为 false

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


检查两个 \"Dimensions\" 值是否不相等，即它们的
对应的宽度和/或高度不同


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 要检查的第一个实例 |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 要检查的第二个实例 |
|

**Returns:**
布尔型 - 如果不相等则为 True，若相等则为 false

### toString() {#toString--}
```
public String toString()
```


返回此 "Dimensions" 的字符串表示

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - 包含宽度和高度的字符串实例，格式为 W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


返回此实例的完整副本


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


返回一个空的 Dimensions 实例


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)

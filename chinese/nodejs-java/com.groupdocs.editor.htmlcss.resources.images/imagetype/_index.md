---
title: "ImageType"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一种可支持的图像类型格式，支持光栅和矢量格式"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

表示一种可支持的图像类型（格式），支持光栅和矢量格式。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 未定义的图像类型 - 特殊值，通常不应出现 |
|
|  | [getJpeg()](#getJpeg--) | JPEG 图像类型 |
|
|  | [getPng()](#getPng--) | PNG 图像类型 |
|
|  | [getBmp()](#getBmp--) | BMP 图像类型 |
|
|  | [getGif()](#getGif--) | GIF 图像类型 |
|
|  | [getIcon()](#getIcon--) | ICON 图像类型 |
|
|  | [getSvg()](#getSvg--) | SVG 矢量图像类型 |
|
|  | [getWmf()](#getWmf--) | WMF（Windows MetaFile）矢量图像类型 |
|
|  | [getEmf()](#getEmf--) | EMF（Enhanced MetaFile）矢量图像类型 |
|
|  | [getTiff()](#getTiff--) | TIFF（Tagged Image File Format）光栅图像类型 |
|
|  | [getFormalName()](#getFormalName--) | 返回此图像格式的正式名称。 |
|
|  | [isVector()](#isVector--) | 指示此特定格式是矢量（true）还是光栅 |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | 特定图像类型的文件扩展名（不含前导点字符） |
小写。
|
|  | [toString()](#toString--) | 返回 FormalName 属性 |
|
|  | [getMimeCode()](#getMimeCode--) | 特定图像类型的 MIME 代码，字符串形式。 |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 确定此实例是否与指定的 \"ImageType\" 相等 |
实例
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的未转换对象， |
它可能是另一个 \"ImageType\" 实例
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 定义两个特定 ImageType 实例是否相等 |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 定义两个特定 ImageType 实例是否不相等 |
|
|  | [hashCode()](#hashCode--) | 返回哈希码，这是此特定对象的不可变数字 |
实例
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 返回 ImageType 值，它等同于文件扩展名， |
从指定的文件名中提取
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 返回 ImageType 值，它等同于指定的 MIME 代码 |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


未定义的图像类型 - 特殊值，通常不应出现


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG 图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG 图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP 图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF 图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON 图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG 矢量图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF（Windows MetaFile）矢量图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF（Enhanced MetaFile）矢量图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF（Tagged Image File Format）光栅图像类型


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


返回此图像格式的正式名称。永不返回 NULL。如果
实例未损坏时，永不抛出异常。


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


指示此特定格式是矢量（true）还是光栅
(false)


**Returns:**
布尔
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


特定图像类型的文件扩展名（不含前导点字符）
小写。对于 Undefined 类型返回字符串 'unsefined'。


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


返回 FormalName 属性


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定图像类型的 MIME 代码，字符串形式。对于 Undefined 类型
返回字符串 'unsefined'。


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


确定此实例是否与指定的 \"ImageType\" 相等
实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 用于与此检查相等性的其他 ImageType 实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的未转换对象，
它可能是另一个 \"ImageType\" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 其他 System.Object 实例，可能是 ImageType 类型，用于与此检查相等性 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


定义两个特定 ImageType 实例是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 要检查的第一个 ImageType 实例 |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 要检查的第二个 ImageType 实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


定义两个特定 ImageType 实例是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 要检查的第一个 ImageType 实例 |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 要检查的第二个 ImageType 实例 |
|

**Returns:**
布尔型 - 如果不相等则为 True，若相等则为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回哈希码，这是此特定对象的不可变数字
实例


**Returns:**
int - 有符号 4 字节整数

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


返回 ImageType 值，它等同于文件扩展名，
从指定的文件名中提取


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件名 | java.lang.String | 任意文件名，可以是相对路径或完整路径 |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


返回 ImageType 值，它等同于指定的 MIME 代码


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | 任意 MIME 代码 |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.


---
title: "IconImage"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 ICON 格式的单个图像及其元数据和附加方法"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

表示 ICON 格式的单个图像及其元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | 从内容创建新的 IconImage 实例，内容表示为 |
base64 编码的字符串，并使用指定的名称
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 IconImage 实例，内容表示为字节流， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 ICON 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 ICON 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | 返回此 ICON 文件中存在的图像数量 |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


从内容创建新的 IconImage 实例，内容表示为
base64 编码的字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | ICON 图像的名称。不能为空、空字符串或仅包含空白。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码的字符串。不能为空、空字符串或仅包含空白。如果它不是 ICON 内容，将抛出异常。 |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


从内容创建新的 IconImage 实例，内容表示为字节流，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | ICON 图像的名称。不能为空、空字符串或仅包含空白。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，此流也将被释放。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 ICON 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 ICON 图像 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 ICON 图像，则为 True，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 ICON 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 ICON 图像内容，以 base64 编码字符串形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 ICON 图像，则为 True，否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


返回此 ICON 文件中存在的图像数量


**Returns:**
int

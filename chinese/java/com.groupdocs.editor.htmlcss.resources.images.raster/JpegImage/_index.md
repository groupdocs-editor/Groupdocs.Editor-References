---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 JPEG 联合摄影专家组（Joint Photographic Experts Group）格式中的单个图像及其元数据和附加方法"
type: docs
weight: 13
url: /zh/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

表示 JPEG（联合摄影专家组）格式中的单个图像及其
其元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | 从内容创建新的 JpegImage 实例，表示为 |
base64 编码的字符串，并使用指定的名称
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 JpegImage 实例，表示为字节流， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 JPEG 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 JPEG 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


从内容创建新的 JpegImage 实例，表示为
base64 编码的字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | JPEG 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码的字符串。不能为空、为空或仅包含空白字符。如果内容不是 JPEG，则会抛出异常。 |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


从内容创建新的 JpegImage 实例，表示为字节流，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | JPEG 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，则此流也将被释放。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 JPEG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 JPEG 图像 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 JPEG 图像则为 true，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 JPEG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 JPEG 图像内容，以 base64 编码的字符串形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 JPEG 图像则为 true，否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

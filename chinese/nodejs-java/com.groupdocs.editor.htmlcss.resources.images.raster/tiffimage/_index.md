---
title: "TiffImage"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 TIFF 标记图像文件格式（Tagged Image File Format）中的单个图像，包含其元数据和附加方法"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

表示 TIFF（Tagged Image File Format）格式中的单个图像，包含其
元数据和附加方法


*** ** * ** ***

请参阅 https://en.wikipedia.org/wiki/TIFF 获取详细信息。 在极少数情况下，TIFF 会出现在 WordProcessing 文档中。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | 从内容创建新的 TiffImage 实例，表示为 |
base64 编码的字符串，并使用指定的名称
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 GifImage 实例，内容以字节流表示， |
并使用指定的名称
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 TIFF 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 TIFF 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | 返回此 TIFF 图像中的帧（图像）数量。 |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


从内容创建新的 TiffImage 实例，表示为
base64 编码的字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | TIFF 图像的名称。不能为空、空字符串或仅包含空白。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、空字符串或仅包含空白。如果不是 TIFF 内容，将抛出异常。 |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


从内容创建新的 GifImage 实例，内容以字节流表示，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | GIF 图像的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，此流也将被释放。 |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| 二进制内容 | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 TIFF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 TIFF 图像 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 TIFF 图像则为 True，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 TIFF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 TIFF 图像内容，以 base64 编码字符串形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 TIFF 图像则为 True，否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


返回此 TIFF 图像中的帧（图像）数量。不能是
小于 1。


**Returns:**
int -

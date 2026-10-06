---
title: "PngImage"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 PNG 便携式网络图形（Portable Network Graphics）格式的单个图像，包括其元数据和附加方法"
type: docs
weight: 14
url: /zh/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

表示 PNG（Portable Network Graphics）格式的单个图像，包括其
元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | 从内容创建新的 PngImage 实例，内容以 base64 编码表示 |
字符串，并使用指定的名称
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 PngImage 实例，内容以字节流表示， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 PNG 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 PNG 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


从内容创建新的 PngImage 实例，内容以 base64 编码表示
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | PNG 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、为空或仅包含空白字符。如果不是 PNG 内容，将抛出异常。 |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


从内容创建新的 PngImage 实例，内容以字节流表示，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | PNG 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，则此流也将被释放。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 PNG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 字节流，可能包含 PNG 图像 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 PNG 图像，则为 True；否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 PNG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 可能的 PNG 图像的内容，以 base64 编码字符串形式 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 PNG 图像，则为 True；否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

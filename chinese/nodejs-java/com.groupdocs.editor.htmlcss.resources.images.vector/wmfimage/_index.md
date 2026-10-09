---
title: "WmfImage"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 WMF Windows MetaFile 格式中的一个矢量图像，包含其元数据和附加方法"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)，[com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

表示 WMF（Windows MetaFile）格式中的一个矢量图像，包含其
元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | 从内容创建新的 WmfImage 实例，内容以 base64 编码表示 |
字符串，并使用指定的名称
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 WmfImage 实例，内容以字节流表示， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 WMF 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 WMF 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | 以二进制流返回此 WMF 图像的内容 |
|
|  | [getTextContent()](#getTextContent--) | 以纯文本返回此 WMF 图像的内容 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此 WMF 图像保存到文件 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 将此矢量 WMF 图像保存为栅格 PNG 图像 |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 将此矢量 WMF 图像保存为矢量 SVG 图像 |
|
|  | [dispose()](#dispose--) | 通过释放其内容来处理此 WMF 图像，并使其大多数 |
方法和属性不可用
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


从内容创建新的 WmfImage 实例，内容以 base64 编码表示
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | WMF 图像的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、空字符串或仅包含空白字符。如果不是 WMF 内容，将抛出异常。 |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


从内容创建新的 WmfImage 实例，内容以字节流表示，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | WMF 图像的名称。不能为空、空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，此流也将被释放。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 WMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 输入字节流。不能为空，且应支持读取和定位。 |
|

**Returns:**
布尔值 - 如果指定的流包含有效的 WMF 图像则为 true，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 WMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 输入字符串，其中 WMF 图像的内容以 base64 编码存储。不能为空或空字符串。 |
|

**Returns:**
布尔值 - 如果指定的字符串包含有效的 WMF 图像则为 true，否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


以二进制流返回此 WMF 图像的内容


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


以纯文本返回此 WMF 图像的内容


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


将此 WMF 图像保存到文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件完整路径 | java.lang.String | 文件的完整路径，将使用此 WMF 图像的内容创建（如果不存在）或覆盖（如果已存在）该文件 |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


将此矢量 WMF 图像保存为栅格 PNG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 输出流，将写入 PNG 图像的内容。不能为空且应可写。 |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


将此矢量 WMF 图像保存为矢量 SVG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 输出流，将写入 SVG 图像的内容。不能为空且应可写。 |
|

### dispose() {#dispose--}
```
public void dispose()
```


通过释放其内容来处理此 WMF 图像，并使其大多数
方法和属性不可用



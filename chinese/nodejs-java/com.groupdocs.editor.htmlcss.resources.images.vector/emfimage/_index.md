---
title: "EmfImage"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一种增强型图元文件（EMF）格式的矢量图像，包含其元数据和附加方法"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)，[com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

表示一种增强型图元文件（EMF）格式的矢量图像，包含其
元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | 从内容创建新的 EmfImage 实例，表示为 base64 编码 |
字符串，并使用指定的名称
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 EmfImage 实例，表示为字节流， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 检查指定的流是否为有效的 EMF 图像 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 检查指定的 base64 编码字符串是否为有效的 EMF 图像 |
|
|  | [getType()](#getType--) | 返回 ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | 返回此 EMF 图像的内容，作为二进制流 |
|
|  | [getTextContent()](#getTextContent--) | 返回此 EMF 图像的内容，作为纯文本 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此 EMF 图像保存到文件 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 将此矢量 EMF 图像保存为栅格 PNG 图像 |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 将此矢量 EMF 图像保存为矢量 SVG 图像 |
|
|  | [dispose()](#dispose--) | 通过释放其内容来处理此 EMF 图像，并使其大部分 |
方法和属性不可用
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


从内容创建新的 EmfImage 实例，表示为 base64 编码
字符串，并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | EMF 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | contentInBase64 | java.lang.String | 内容为 base64 编码字符串。不能为空、为空或仅包含空白字符。如果它不是 EMF 内容，将抛出异常。 |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


从内容创建新的 EmfImage 实例，表示为字节流，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | EMF 图像的名称。不能为空、为空或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，此流也将被释放。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


检查指定的流是否为有效的 EMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 二进制内容 | java.io.InputStream | 输入字节流。不能为空，且应支持读取和定位。 |
|

**Returns:**
boolean - 如果指定的流包含有效的 EMF 图像则为 True，否则为 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


检查指定的 base64 编码字符串是否为有效的 EMF 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 输入字符串，其中存储了以 base64 编码的 EMF 图像内容。不能为 NULL 或为空。 |
|

**Returns:**
boolean - 如果指定的字符串包含有效的 EMF 图像则为 True，否则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


返回此 EMF 图像的内容，作为二进制流


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


返回此 EMF 图像的内容，作为纯文本


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


将此 EMF 图像保存到文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件完整路径 | java.lang.String | 文件的完整路径，如果不存在将创建（如果不存在），若已存在将被覆盖（如果已存在），内容为此 EMF 图像的内容 |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


将此矢量 EMF 图像保存为栅格 PNG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 输出流，将写入 PNG 图像的内容。不能为空且应可写。 |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


将此矢量 EMF 图像保存为矢量 SVG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 输出流，将写入 SVG 图像的内容。不能为空且应可写。 |
|

### dispose() {#dispose--}
```
public void dispose()
```


通过释放其内容来处理此 EMF 图像，并使其大部分
方法和属性不可用



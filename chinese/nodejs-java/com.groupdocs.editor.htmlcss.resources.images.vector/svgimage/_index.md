---
title: "SvgImage"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一种 SVG（可缩放矢量图形）格式的矢量图像，包含其元数据和附加方法"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

表示一种 SVG（可缩放矢量图形）格式的矢量图像，包含其
元数据和附加方法

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | 从内容创建新的 SvgImage 实例，表示为普通字符串， |
并使用指定的名称
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | 从内容创建新的 SvgImage 实例，表示为字节流， |
并使用指定的名称
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | 执行表面检查，以确定指定的文本 XML 兼容内容 |
表示一个 SVG 图像
|
|  | [getType()](#getType--) | 返回 ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | 返回此 SVG 图像的内容，作为二进制流 |
|
|  | [getTextContent()](#getTextContent--) | 返回此 SVG 图像的内容，作为纯文本（XML 格式） |
|
|  | [getXmlContent()](#getXmlContent--) | 返回此 SVG 图像的内容，以其原始符合 XML 的形式 |
文本形式
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此 SVG 图像保存到文件 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 将此矢量 SVG 图像保存为栅格 PNG 图像 |
|
|  | [dispose()](#dispose--) | 释放此栅格图像，释放其内容并使大多数方法 |
以及属性不可用
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


从内容创建新的 SvgImage 实例，表示为普通字符串，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | SVG 图像的名称。不能为空、为空字符串或仅包含空白字符。 |
|
|  | 内容 | java.lang.String | 内容为普通字符串，包含有效的符合 XML 的 SVG 图像内容。不能为空、为空字符串或仅包含空白字符。如果不是 SVG 内容，将抛出异常。 |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


从内容创建新的 SvgImage 实例，表示为字节流，
并使用指定的名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | SVG 图像的名称。不能为空、为空字符串或仅包含空白字符。 |
|
|  | 二进制内容 | java.io.InputStream | 内容为字节流。读取从原始位置开始。不能为空。应当可读且可定位。如果此实例被释放，此流也将被释放。 |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


执行表面检查，以确定指定的文本 XML 兼容内容
表示一个 SVG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 内容 | java.lang.String | SVG 图像的 XML 内容，以纯文本形式，而非 base64 编码的内容 |
|

**Returns:**
布尔值 - 如果指定的字符串初步可以视为有效 SVG，则为 True；如果肯定不是 SVG，则为 false

### getType() {#getType--}
```
public ImageType getType()
```


返回 ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


返回此 SVG 图像的内容，作为二进制流


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


返回此 SVG 图像的内容，作为纯文本（XML 格式）


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


返回此 SVG 图像的内容，以其原始符合 XML 的形式
文本形式


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


将此 SVG 图像保存到文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件完整路径 | java.lang.String | 文件的完整路径，将使用此 SVG 图像的内容创建（如果不存在）或覆盖（如果已存在） |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


将此矢量 SVG 图像保存为栅格 PNG 图像


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 输出流，将写入 PNG 图像的内容。不能为空且应可写。 |
|

### dispose() {#dispose--}
```
public void dispose()
```


释放此栅格图像，释放其内容并使大多数方法
以及属性不可用



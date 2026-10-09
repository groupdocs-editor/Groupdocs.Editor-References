---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "任何受支持的矢量图像的基类"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

任何受支持的矢量图像的基类

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 返回此矢量图像的名称。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 返回此矢量图像的正确文件名，由名称和 |
扩展名组成。
|
|  | [getAspectRatio()](#getAspectRatio--) | 返回此矢量图像的宽高比 |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 返回此矢量图像的线性尺寸（宽度和高度） |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 检查此实例与指定对象的引用相等性。 |
|
|  | [isDisposed()](#isDisposed--) | 确定此光栅图像是否已释放 |
|
|  | [getType()](#getType--) | 在实现时应返回有关矢量类型的信息 |
图像
|
|  | [getByteContent()](#getByteContent--) | 在实现时应以字节形式返回此矢量图像的内容 |
流
|
|  | [getTextContent()](#getTextContent--) | 在实现时应以文本形式返回此矢量图像的内容 |
形式：关于图像类型的 XML 的 base64 编码
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 在实现时应按指定路径将此图像保存到磁盘 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 在实现时应将当前矢量图像保存为光栅 PNG |
格式化为指定的字节流
|
|  | [dispose()](#dispose--) | 在实现时应释放此实例 |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


返回此矢量图像的名称。通常不包含文件名
扩展名，理论上可能与文件名不同。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


返回此矢量图像的正确文件名，由名称和
扩展名。理论上可能与名称不同。


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


返回此矢量图像的宽高比


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


返回此矢量图像的线性尺寸（宽度和高度）


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


检查此实例与指定对象的引用相等性。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 其他矢量图像实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


确定此光栅图像是否已释放


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


在实现时应返回有关矢量类型的信息
图像


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


在实现时应以字节形式返回此矢量图像的内容
流


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


在实现时应以文本形式返回此矢量图像的内容
形式：关于图像类型的 XML 的 base64 编码


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


在实现时应按指定路径将此图像保存到磁盘


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件完整路径 | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


在实现时应将当前矢量图像保存为光栅 PNG
格式化为指定的字节流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 字节流，PNG 版本的栅格图像将存储在其中。不得为 NULL，且应支持写入。 |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


在实现时应释放此实例



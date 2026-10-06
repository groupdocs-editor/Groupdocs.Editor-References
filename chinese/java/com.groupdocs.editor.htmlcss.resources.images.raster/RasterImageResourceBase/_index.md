---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for Java API 参考"
description: "任何受支持的光栅图像的基类，具有固定的名称、尺寸、宽高比、类型、大小和内容。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

任何受支持的光栅图像的基类，具有固定的名称、尺寸、宽高比
宽高比、类型、大小和内容。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 返回此光栅图像的名称。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 返回此光栅图像的正确文件名，由名称和 |
扩展名组成。
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 返回此光栅图像的线性尺寸（宽度和高度） |
|
|  | [getAspectRatio()](#getAspectRatio--) | 返回此图像的宽高比，作为宽度与高度的比例 |
|
|  | [getLength()](#getLength--) | 返回此光栅图像文件的字节长度 |
|
|  | [getByteContent()](#getByteContent--) | 以字节流形式返回此光栅图像的内容 |
|
|  | [getTextContent()](#getTextContent--) | 以 base64 编码字符串形式返回此光栅图像的内容 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 将此光栅图像保存到指定文件 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 检查此实例与指定的在引用相等性上相等。 |
|
|  | [dispose()](#dispose--) | 释放此光栅图像，释放其内容并使大多数方法 |
以及属性不可用
|
|  | [isDisposed()](#isDisposed--) | 确定此光栅图像是否已释放 |
|
|  | [getType()](#getType--) | 在实现时，类型应返回有关光栅类型的信息。 |
图像
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


返回此光栅图像的名称。通常不包含文件名
扩展名，理论上可能与文件名不同。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


返回此光栅图像的正确文件名，由名称和
扩展名。理论上可能与名称不同。


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


返回此光栅图像的线性尺寸（宽度和高度）


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


返回此图像的宽高比，作为宽度与高度的比例


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


返回此光栅图像文件的字节长度


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


以字节流形式返回此光栅图像的内容


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


以 base64 编码字符串形式返回此光栅图像的内容


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


将此光栅图像保存到指定文件


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 将要创建或重写的文件的完整路径 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


检查此实例与指定的在引用相等性上相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 其他 IHtmlResource 继承者 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false

### dispose() {#dispose--}
```
public final void dispose()
```


释放此光栅图像，释放其内容并使大多数方法
以及属性不可用


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


在实现时，类型应返回有关光栅类型的信息。
图像


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

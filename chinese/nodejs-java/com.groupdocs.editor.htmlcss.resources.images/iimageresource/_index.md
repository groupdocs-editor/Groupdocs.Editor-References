---
title: "IImageResource"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示任何类型（光栅或矢量）的图像资源"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

表示任意类型的图像资源，无论是光栅还是矢量。


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getType()](#getType--) | 在实现类型时应返回特定图像的类型作为 |
特定 ImageType 的实例，封装了所有类型特定的信息
|
|  | [getAspectRatio()](#getAspectRatio--) | 在实现类型时应返回特定图像的宽高比 |
无论其类型如何。
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 在实现类型时应返回图像的线性尺寸。 |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


在实现类型时应返回特定图像的类型作为
特定 ImageType 的实例，封装了所有类型特定的信息


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


在实现类型时应返回特定图像的宽高比
无论其类型如何。矢量和光栅图像都有固有的
宽度与高度之间的宽高比。


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


在实现类型时应返回图像的线性尺寸。对于
光栅图像，它们是以像素为单位的固有尺寸。矢量图像，在
相对地，没有固定尺寸，但它们的元数据可以包含
一些不同计量单位的基本尺寸。


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 

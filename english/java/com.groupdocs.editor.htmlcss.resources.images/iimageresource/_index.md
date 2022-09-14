---
title: IImageResource
second_title: GroupDocs.Editor for Java API Reference
description: Represents image resource of any type raster or vector
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Represents image resource of any type, raster or vector

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/image
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | In implementing type should return a type of specific image as an instance of specific ImageType, which encapsulates all type-specific info |
| [getAspectRatio()](#getAspectRatio--) | In implementing type should return an aspect ratio of particular image regardless of its type. |
| [getLinearDimensions()](#getLinearDimensions--) | In implementing type should return linear dimensions of the image. |
### getType() {#getType--}
```
public abstract ImageType getType()
```


In implementing type should return a type of specific image as an instance of specific ImageType, which encapsulates all type-specific info

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


In implementing type should return an aspect ratio of particular image regardless of its type. Both vector and raster images have intrinsic aspect ratio between its width and height.

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


In implementing type should return linear dimensions of the image. For raster images they are intrinsic dimensions in pixels. Vector images, in counterpart, have no fixed dimensions, but their metadata can contain some basic dimensions in different measurement units.

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 

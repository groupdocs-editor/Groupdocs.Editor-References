---
title: RasterImageResourceBase
second_title: GroupDocs.Editor for Java API Reference
description: Base class for any supported raster image with fixed name dimensions aspect ratio type size and content.
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Base class for any supported raster image with fixed name, dimensions, aspect ratio, type, size, and content.
## Constructors

| Constructor | Description |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns name of this raster image. |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this raster image, which consists of name and extension. |
| [getLinearDimensions()](#getLinearDimensions--) | Returns linear dimensions of this raster image (width and height) |
| [getAspectRatio()](#getAspectRatio--) | Returns an aspect ratio of this image as the width-to-height relation |
| [getLength()](#getLength--) | Returns the length of this raster image file in bytes |
| [getByteContent()](#getByteContent--) | Returns content of this raster image as byte stream |
| [getTextContent()](#getTextContent--) | Returns content of this raster image as base64-encoded string |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this raster image to the specified file |
| [generateBitmap()](#generateBitmap--) | Generates and returns a new instance of the 'System.Drawing.Bitmap' from this raster image. |
| [reduceToNewHeight(int targetHeightInPixels)](#reduceToNewHeight-int-) | Creates and returns a new reduced image resource of the same type, but with specified new reduced height and proportionally reduced width. |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified on reference equality. |
| [dispose()](#dispose--) | Disposes this raster image, disposing its content and making most methods and properties non-working |
| [isDisposed()](#isDisposed--) | Determines whether this raster image is disposed or not |
| [getType()](#getType--) | In implementing type should return information about type of the raster image |
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


Returns name of this raster image. Usually doesn't contain filename extension and theoretically can differ from filename.

**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returns correct filename of this raster image, which consists of name and extension. Theoretically can differ from the name.

**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Returns linear dimensions of this raster image (width and height)

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Returns an aspect ratio of this image as the width-to-height relation

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Returns the length of this raster image file in bytes

**Returns:**
int - 
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returns content of this raster image as byte stream

**Returns:**
java.io.InputStream - 
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returns content of this raster image as base64-encoded string

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Saves this raster image to the specified file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created or rewritten |

### generateBitmap() {#generateBitmap--}
```
public final BufferedImage generateBitmap()
```


Generates and returns a new instance of the 'System.Drawing.Bitmap' from this raster image.

**Returns:**
java.awt.image.BufferedImage - New instance of 'System.Drawing.Bitmap'

--------------------

'System.Drawing.Bitmap' is not cached and thus will be generated every time this method will be called
### reduceToNewHeight(int targetHeightInPixels) {#reduceToNewHeight-int-}
```
public RasterImageResourceBase reduceToNewHeight(int targetHeightInPixels)
```


Creates and returns a new reduced image resource of the same type, but with specified new reduced height and proportionally reduced width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetHeightInPixels | int | Height of the desired image in pixels. Should be strictly lesser than original height. |

**Returns:**
[RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase) - New instance with specified height, that is inheritor of RasterImageResourceBase
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Checks this instance with specified on reference equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Other IHtmlResource inheritor |

**Returns:**
boolean - True if are equal, false if are unequal
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this raster image, disposing its content and making most methods and properties non-working

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determines whether this raster image is disposed or not

**Returns:**
boolean - 
### getType() {#getType--}
```
public abstract ImageType getType()
```


In implementing type should return information about type of the raster image

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

---
title: VectorImageResourceBase
second_title: GroupDocs.Editor for Java API Reference
description: Base class for any supported vector image
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Base class for any supported vector image
## Constructors

| Constructor | Description |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns name of this vector image. |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this vector image, which consists of name and extension. |
| [getAspectRatio()](#getAspectRatio--) | Returns aspect ratio of this vector image |
| [getLinearDimensions()](#getLinearDimensions--) | Returns linear dimensions of this vector image (width and height) |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified on reference equality. |
| [isDisposed()](#isDisposed--) | Determines whether this raster image is disposed or not |
| [getType()](#getType--) | In implementing type should return information about type of the vector image |
| [getByteContent()](#getByteContent--) | In implementing type should return a content of this vector image as byte stream |
| [getTextContent()](#getTextContent--) | In implementing type should return a content of this vector image in text form: base64-encoded of XML regarding of image type |
| [save(String fullPathToFile)](#save-java.lang.String-) | In implementing type should save this image to the disk by specified path |
| [saveToPng(InputStream outputPngContent)](#saveToPng-java.io.InputStream-) | In implementing type should save a current vector image to the raster PNG format into specified byte stream |
| [dispose()](#dispose--) | In implementing type should dispose this instance |
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


Returns name of this vector image. Usually doesn't contain filename extension and theoretically can differ from filename.

**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returns correct filename of this vector image, which consists of name and extension. Theoretically can differ from the name.

**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Returns aspect ratio of this vector image

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Returns linear dimensions of this vector image (width and height)

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Checks this instance with specified on reference equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Other instance of vector image |

**Returns:**
boolean - True if are equal, false if are unequal
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


In implementing type should return information about type of the vector image

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


In implementing type should return a content of this vector image as byte stream

**Returns:**
java.io.InputStream - 
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


In implementing type should return a content of this vector image in text form: base64-encoded of XML regarding of image type

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


In implementing type should save this image to the disk by specified path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(InputStream outputPngContent) {#saveToPng-java.io.InputStream-}
```
public abstract void saveToPng(InputStream outputPngContent)
```


In implementing type should save a current vector image to the raster PNG format into specified byte stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPngContent | java.io.InputStream | Byte stream, into which the PNG version of this raster image will be stored. Should not be NULL and should support writing. |

### dispose() {#dispose--}
```
public abstract void dispose()
```


In implementing type should dispose this instance


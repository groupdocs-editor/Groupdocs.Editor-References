---
title: PngImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one image in PNG Portable Network Graphics format with its metadata and additional methods
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Represents one image in PNG (Portable Network Graphics) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Creates new PngImage instance from content, represented as base64-encoded string, and with specified name |
| [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Creates new PngImage instance from content, represented as byte stream, and with specified name |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid PNG image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid PNG image |
| [getType()](#getType--) | Returns ImageType.Png |
| [reduceToNewHeight(int targetHeightInPixels)](#reduceToNewHeight-int-) | Creates and returns a new reduced PNG image, but with specified new reduced height and proportionally reduced width. |
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Creates new PngImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the PNG image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a PNG content, exception will be thrown. |

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Creates new PngImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the PNG image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid PNG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a PNG image |

**Returns:**
boolean - True if specified stream contains valid PNG image, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid PNG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably PNG image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid PNG image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Png

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### reduceToNewHeight(int targetHeightInPixels) {#reduceToNewHeight-int-}
```
public final PngImage reduceToNewHeight(int targetHeightInPixels)
```


Creates and returns a new reduced PNG image, but with specified new reduced height and proportionally reduced width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetHeightInPixels | int | Height of the desired PNG image in pixels. Should be strictly lesser than original height. |

**Returns:**
[PngImage](../../com.groupdocs.editor.htmlcss.resources.images.raster/pngimage) - New PngImage instance with specified height

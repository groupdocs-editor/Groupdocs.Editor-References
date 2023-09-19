---
title: TiffImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one image in TIFF Tagged Image File Format format with its metadata and additional methods
type: docs
weight: 16
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Represents one image in TIFF (Tagged Image File Format) format with its metadata and additional methods

--------------------

See https://en.wikipedia.org/wiki/TIFF for details. In very rare cases TIFF is present inside WordProcessing documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Creates new TiffImage instance from content, represented as base64-encoded string, and with specified name |
| [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Creates new GifImage instance from content, represented as byte stream, and with specified name |
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid TIFF image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid TIFF image |
| [getType()](#getType--) | Returns ImageType.Tiff |
| [getFramesCount()](#getFramesCount--) | Returns a number of frames (images) inside this TIFF image. |
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Creates new TiffImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the TIFF image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a TIFF content, exception will be thrown. |

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Creates new GifImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the GIF image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid TIFF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a TIFF image |

**Returns:**
boolean - True if specified stream contains valid TIFF image, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid TIFF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably TIFF image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid TIFF image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Tiff

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Returns a number of frames (images) inside this TIFF image. Cannot be lesser then 1.

**Returns:**
int - 

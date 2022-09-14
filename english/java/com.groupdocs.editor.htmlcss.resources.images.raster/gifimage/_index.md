---
title: GifImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one image in GIF Graphics Interchange Format format with its metadata and additional methods
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Represents one image in GIF (Graphics Interchange Format) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Creates new GifImage instance from content, represented as base64-encoded string, and with specified name |
| [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Creates new GifImage instance from content, represented as byte stream, and with specified name |
| [GifImage(String name, System.IO.Stream binaryContent)](#GifImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid GIF image |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid GIF image |
| [getType()](#getType--) | Returns ImageType.Gif |
| [reduceToNewHeight(int targetHeightInPixels)](#reduceToNewHeight-int-) | Creates and returns a new reduced GIF image, but with specified new reduced height and proportionally reduced width. |
| [getVersion()](#getVersion--) | Returns internal version of this GIF image (version is extracted from header) |
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Creates new GifImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the GIF image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a GIF content, exception will be thrown. |

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Creates new GifImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the GIF image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### GifImage(String name, System.IO.Stream binaryContent) {#GifImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public GifImage(String name, System.IO.Stream binaryContent)
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


Checks whether specified stream is a valid GIF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a GIF image |

**Returns:**
boolean - True if specified stream contains valid GIF image, false otherwise
### isValidInternal(System.IO.Stream binaryContent) {#isValidInternal-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValidInternal(System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid GIF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably GIF image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid GIF image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Gif

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### reduceToNewHeight(int targetHeightInPixels) {#reduceToNewHeight-int-}
```
public final GifImage reduceToNewHeight(int targetHeightInPixels)
```


Creates and returns a new reduced GIF image, but with specified new reduced height and proportionally reduced width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetHeightInPixels | int | Height of the desired GIF image in pixels. Should be strictly lesser than original height. |

**Returns:**
[GifImage](../../com.groupdocs.editor.htmlcss.resources.images.raster/gifimage) - New GifImage instance with specified height
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Returns internal version of this GIF image (version is extracted from header)

**Returns:**
java.lang.String

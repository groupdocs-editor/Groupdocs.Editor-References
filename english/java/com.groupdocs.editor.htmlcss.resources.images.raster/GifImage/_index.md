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
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid GIF image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid GIF image |
| [getType()](#getType--) | Returns ImageType.Gif |
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
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Returns internal version of this GIF image (version is extracted from header)

**Returns:**
java.lang.String

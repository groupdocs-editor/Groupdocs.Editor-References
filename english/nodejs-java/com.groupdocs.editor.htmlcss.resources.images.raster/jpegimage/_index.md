---
title: JpegImage
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one image in JPEG Joint Photographic Experts Group format with its metadata and additional methods
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Represents one image in JPEG (Joint Photographic Experts Group) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Creates new JpegImage instance from content, represented as base64-encoded string, and with specified name |
| [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Creates new JpegImage instance from content, represented as byte stream, and with specified name |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid JPEG image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid JPEG image |
| [getType()](#getType--) | Returns ImageType.Jpeg |
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Creates new JpegImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the JPEG image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a JPEG content, exception will be thrown. |

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Creates new JpegImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the JPEG image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid JPEG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a JPEG image |

**Returns:**
boolean - True if specified stream contains valid JPEG image, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid JPEG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably JPEG image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid JPEG image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Jpeg

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

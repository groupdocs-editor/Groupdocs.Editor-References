---
title: BmpImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one image in BMP BitMap Picture format with its metadata and additional methods
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Represents one image in BMP (BitMap Picture) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Creates new BmpImage instance from content, represented as base64-encoded string, and with specified name |
| [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Creates new BmpImage instance from content, represented as byte stream, and with specified name |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid BMP image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid BMP image |
| [getType()](#getType--) | Returns ImageType.Bmp |
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Creates new BmpImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the BMP image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a BMP content, exception will be thrown. |

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Creates new BmpImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the BMP image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid BMP image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a BMP image |

**Returns:**
boolean - True if specified stream contains valid BMP image, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid BMP image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably BMP image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid BMP image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Bmp

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)

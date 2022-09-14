---
title: IconImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one image in ICON format with its metadata and additional methods
type: docs
weight: 12
url: /java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Represents one image in ICON format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Creates new IconImage instance from content, represented as base64-encoded string, and with specified name |
| [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Creates new IconImage instance from content, represented as byte stream, and with specified name |
| [IconImage(String name, System.IO.Stream binaryContent)](#IconImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid ICON image |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid ICON image |
| [getType()](#getType--) | Returns ImageType.Icon |
| [reduceToNewHeight_IconImage_New(int targetHeightInPixels)](#reduceToNewHeight-IconImage-New-int-) | Creates and returns a new reduced Icon image, but with specified new reduced height and proportionally reduced width. |
| [getNumberOfImages()](#getNumberOfImages--) | Returns number of images, which are present in this ICON file |
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Creates new IconImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the ICON image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a ICON content, exception will be thrown. |

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Creates new IconImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the ICON image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### IconImage(String name, System.IO.Stream binaryContent) {#IconImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public IconImage(String name, System.IO.Stream binaryContent)
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


Checks whether specified stream is a valid ICON image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a ICON image |

**Returns:**
boolean - True if specified stream contains valid ICON image, false otherwise
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


Checks whether specified base64-encoded string is a valid ICON image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably ICON image in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid ICON image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Icon

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### reduceToNewHeight_IconImage_New(int targetHeightInPixels) {#reduceToNewHeight-IconImage-New-int-}
```
public final IconImage reduceToNewHeight_IconImage_New(int targetHeightInPixels)
```


Creates and returns a new reduced Icon image, but with specified new reduced height and proportionally reduced width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetHeightInPixels | int | Height of the desired Icon image in pixels. Should be strictly lesser than original height. |

**Returns:**
[IconImage](../../com.groupdocs.editor.htmlcss.resources.images.raster/iconimage) - New IconImage instance with specified height
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Returns number of images, which are present in this ICON file

**Returns:**
int

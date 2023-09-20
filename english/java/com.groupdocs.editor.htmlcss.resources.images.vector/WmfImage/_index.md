---
title: WmfImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one vector image in WMF Windows MetaFile format with its metadata and additional methods
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Represents one vector image in WMF (Windows MetaFile) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Creates new WmfImage instance from content, represented as base64-encoded string, and with specified name |
| [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Creates new WmfImage instance from content, represented as byte stream, and with specified name |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid WMF image |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid WMF image |
| [getType()](#getType--) | Returns ImageType.Wmf |
| [getByteContent()](#getByteContent--) | Returns a content of this WMF image as a binary stream |
| [getTextContent()](#getTextContent--) | Returns a content of this WMF image as a plain text |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this WMF image to the file |
| [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Saves this vector WMF image into raster PNG image |
| [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Saves this vector WMF image into vector SVG image |
| [dispose()](#dispose--) | Disposes this WMF image by disposing its content and making most its methods and properties non-working |
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Creates new WmfImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WMF image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a WMF content, exception will be thrown. |

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Creates new WmfImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WMF image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid WMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Input byte stream. Cannot be NULL, should support reading and seeking. |

**Returns:**
boolean - True if specified stream holds a valid WMF image, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid WMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Input string, where content of WMF image is stored in base64 encoding. Cannot be NULL or empty. |

**Returns:**
boolean - True if specified string holds a valid WMF image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Wmf

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returns a content of this WMF image as a binary stream

**Returns:**
java.io.InputStream - 
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returns a content of this WMF image as a plain text

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Saves this WMF image to the file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created (if it doesn't exist) or overwritten (if exists) with the content of this WMF image |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Saves this vector WMF image into raster PNG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPngContent | java.io.OutputStream | Output stream, into which the content of PNG image will be written. Cannot be NULL and should be writable. |

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Saves this vector WMF image into vector SVG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputSvgContent | java.io.OutputStream | Output stream, into which the content of SVG image will be written. Cannot be NULL and should be writable. |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes this WMF image by disposing its content and making most its methods and properties non-working


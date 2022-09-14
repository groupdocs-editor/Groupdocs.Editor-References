---
title: EmfImage
second_title: GroupDocs.Editor for Java API Reference
description: Represents one vector image in Enhanced metafile format EMF format with its metadata and additional methods
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Represents one vector image in Enhanced metafile format (EMF) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Creates new EmfImage instance from content, represented as base64-encoded string, and with specified name |
| [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Creates new EmfImage instance from content, represented as byte stream, and with specified name |
| [EmfImage(String name, System.IO.Stream binaryContent)](#EmfImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid EMF image |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid EMF image |
| [getType()](#getType--) | Returns ImageType.Emf |
| [getByteContent()](#getByteContent--) | Returns a content of this EMF image as a binary stream |
| [getByteContentInternal()](#getByteContentInternal--) |  |
| [getTextContent()](#getTextContent--) | Returns a content of this EMF image as a plain text |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this EMF image to the file |
| [saveToPng(InputStream outputPngContent)](#saveToPng-java.io.InputStream-) | Saves this vector EMF image into raster PNG image |
| [saveToPngInternal(System.IO.Stream outputPngContent)](#saveToPngInternal-com.aspose.ms.System.IO.Stream-) |  |
| [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Saves this vector EMF image into vector SVG image |
| [dispose()](#dispose--) | Disposes this EMF image by disposing its content and making most its methods and properties non-working |
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Creates new EmfImage instance from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the EMF image. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a EMF content, exception will be thrown. |

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Creates new EmfImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the EMF image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### EmfImage(String name, System.IO.Stream binaryContent) {#EmfImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public EmfImage(String name, System.IO.Stream binaryContent)
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


Checks whether specified stream is a valid EMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Input byte stream. Cannot be NULL, should support reading and seeking. |

**Returns:**
boolean - True if specified stream holds a valid EMF image, false otherwise
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


Checks whether specified base64-encoded string is a valid EMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Input string, where content of EMF image is stored in base64 encoding. Cannot be NULL or empty. |

**Returns:**
boolean - True if specified string holds a valid EMF image, false otherwise
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Emf

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returns a content of this EMF image as a binary stream

**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returns a content of this EMF image as a plain text

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Saves this EMF image to the file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created (if it doesn't exist) or overwritten (if exists) with the content of this EMF image |

### saveToPng(InputStream outputPngContent) {#saveToPng-java.io.InputStream-}
```
public void saveToPng(InputStream outputPngContent)
```


Saves this vector EMF image into raster PNG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPngContent | java.io.InputStream | Output stream, into which the content of PNG image will be written. Cannot be NULL and should be writable. |

### saveToPngInternal(System.IO.Stream outputPngContent) {#saveToPngInternal-com.aspose.ms.System.IO.Stream-}
```
public void saveToPngInternal(System.IO.Stream outputPngContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPngContent | com.aspose.ms.System.IO.Stream |  |

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Saves this vector EMF image into vector SVG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputSvgContent | java.io.OutputStream | Output stream, into which the content of SVG image will be written. Cannot be NULL and should be writable. |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes this EMF image by disposing its content and making most its methods and properties non-working


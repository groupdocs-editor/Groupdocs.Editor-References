---
title: SvgImage
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one vector image in SVG Scalable Vector Graphics format with its
 metadata and additional methods
type: docs
weight: 12
url: /java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Represents one vector image in SVG (Scalable Vector Graphics) format with its metadata and additional methods
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Creates new SvgImage instance from content, represented as usual string, and with specified name |
| [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Creates new SvgImage instance from content, represented as byte stream, and with specified name |
| [SvgImage(String name, System.IO.Stream binaryContent)](#SvgImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(String content)](#isValid-java.lang.String-) | Performs a surface check whether specified textual XML-compliant content represents a SVG image |
| [getType()](#getType--) | Returns ImageType.Svg |
| [getByteContent()](#getByteContent--) | Returns a content of this SVG image as a binary stream |
| [getByteContentInternal()](#getByteContentInternal--) |  |
| [getTextContent()](#getTextContent--) | Returns a content of this SVG image as a plain text (in XML format) |
| [getXmlContent()](#getXmlContent--) | Returns a content of this SVG image int its original XML-compliant textual form |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this SVG image to the file |
| [saveToPng(InputStream outputPngContent)](#saveToPng-java.io.InputStream-) | Saves this vector SVG image into raster PNG image |
| [dispose()](#dispose--) | Disposes this raster image, disposing its content and making most methods and properties non-working |
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Creates new SvgImage instance from content, represented as usual string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the SVG image. Cannot be null, empty or whitespaces. |
| content | java.lang.String | Content as a usual string, which contains a valid XML-compliant content of SVG image. Cannot be null, empty or whitespaces. If it is not a SVG content, exception will be thrown. |

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Creates new SvgImage instance from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the SVG image. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### SvgImage(String name, System.IO.Stream binaryContent) {#SvgImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public SvgImage(String name, System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Performs a surface check whether specified textual XML-compliant content represents a SVG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | XML content of an SVG image as simple text, not a base64-encoded content |

**Returns:**
boolean - True if specified string can be treated as valid SVG at first look, false if it is not SVG for sure
### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Svg

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returns a content of this SVG image as a binary stream

**Returns:**
java.io.InputStream - 
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


Returns a content of this SVG image as a plain text (in XML format)

**Returns:**
java.lang.String - 
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Returns a content of this SVG image int its original XML-compliant textual form

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Saves this SVG image to the file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created (if it doesn't exist) or overwritten (if exists) with the content of this SVG image |

### saveToPng(InputStream outputPngContent) {#saveToPng-java.io.InputStream-}
```
public void saveToPng(InputStream outputPngContent)
```


Saves this vector SVG image into raster PNG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputPngContent | java.io.InputStream | Output stream, into which the content of PNG image will be written. Cannot be NULL and should be writable. |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes this raster image, disposing its content and making most methods and properties non-working


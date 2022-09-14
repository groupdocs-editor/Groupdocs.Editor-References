---
title: UniversalImageParser
second_title: GroupDocs.Editor for Java API Reference
description:  Contains an image parser which obtains an input image of unknown type as a
 byte stream or base64-encoded text and returns its type-defined object
 representation.
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.resources.images/universalimageparser/
---
**Inheritance:**
java.lang.Object
```
public class UniversalImageParser
```

Contains an image parser, which obtains an input image of unknown type as a byte stream or base64-encoded text and returns its type-defined object representation. Full analog of old RasterImageParser
## Constructors

| Constructor | Description |
| --- | --- |
| [UniversalImageParser()](#UniversalImageParser--) |  |
## Methods

| Method | Description |
| --- | --- |
| [parseFromFile(String fullFilePath)](#parseFromFile-java.lang.String-) | Returns an instance of the image-representing class by opening a file using specified path and parsing its content |
| [parse(String dataUri, String name, boolean excludeVector)](#parse-java.lang.String-java.lang.String-boolean-) | Returns an instance of the image-representing class, which is obtained from specified base-encoded textual representation of an image in according to the RFC 2397. |
| [parse(String base64Content, String name, ImageType assumptiveType, boolean excludeVector)](#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.images.ImageType-boolean-) | Returns an instance of the image-representing class, parsing specified base64-encoded content and detecting image type from its header. |
| [parse(System.IO.Stream binaryContent, String name, ImageType assumptiveType, boolean excludeVector)](#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.htmlcss.resources.images.ImageType-boolean-) | Returns an instance of the image-representing class, parsing specified binary content and detecting image type from its header. |
### UniversalImageParser() {#UniversalImageParser--}
```
public UniversalImageParser()
```


### parseFromFile(String fullFilePath) {#parseFromFile-java.lang.String-}
```
public static IImageResource parseFromFile(String fullFilePath)
```


Returns an instance of the image-representing class by opening a file using specified path and parsing its content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullFilePath | java.lang.String |  |

**Returns:**
[IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource) - Instance of raster or vector image on success, NULL on failure
### parse(String dataUri, String name, boolean excludeVector) {#parse-java.lang.String-java.lang.String-boolean-}
```
public static IImageResource parse(String dataUri, String name, boolean excludeVector)
```


Returns an instance of the image-representing class, which is obtained from specified base-encoded textual representation of an image in according to the RFC 2397. Returns NULL if something is wrong or input data is invalid. Supports both raster and vector images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataUri | java.lang.String |  |
| name | java.lang.String |  |
| excludeVector | boolean | Set true in order to allow only raster formats and exclude vector formats from parsing

--------------------

https://ru.wikipedia.org/wiki/Data:\_URL https://en.wikipedia.org/wiki/Data\_URI\_scheme |

**Returns:**
[IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource) - Instance of raster or vector image on success, NULL on failure
### parse(String base64Content, String name, ImageType assumptiveType, boolean excludeVector) {#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.images.ImageType-boolean-}
```
public static IImageResource parse(String base64Content, String name, ImageType assumptiveType, boolean excludeVector)
```


Returns an instance of the image-representing class, parsing specified base64-encoded content and detecting image type from its header. Returns NULL, if image format cannot be parsed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| base64Content | java.lang.String | String, which contains a content of an input image in base-64 encoding. Cannot NULL, empty or whitespaces. |
| name | java.lang.String | Image name (assuming filename), which will be used for creating the instance of a resultant image resource type. Cannot be null or empty. |
| assumptiveType | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Assumed type of the input image, which is useful for achieving the best performance. If completely unknown, use the 'Undefined' value. |
| excludeVector | boolean | Set true in order to allow only raster formats and exclude vector formats from parsing |

**Returns:**
[IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource) - Non-null inheritor of IImageResource on success or NULL on failure
### parse(System.IO.Stream binaryContent, String name, ImageType assumptiveType, boolean excludeVector) {#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.htmlcss.resources.images.ImageType-boolean-}
```
public static IImageResource parse(System.IO.Stream binaryContent, String name, ImageType assumptiveType, boolean excludeVector)
```


Returns an instance of the image-representing class, parsing specified binary content and detecting image type from its header. Returns NULL, if image format cannot be parsed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream | Byte stream with content of the image of undetected format |
| name | java.lang.String | Image name (assuming filename), which will be used for creating the instance of a resultant image resource type. Cannot be null or empty. |
| assumptiveType | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Assumed type of the input image, which is useful for achieving the best performance. If completely unknown, use the 'Undefined' value. |
| excludeVector | boolean | Set true in order to allow only raster formats and exclude vector formats from parsing |

**Returns:**
[IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource) - Non-null inheritor of IImageResource on success or NULL on failure

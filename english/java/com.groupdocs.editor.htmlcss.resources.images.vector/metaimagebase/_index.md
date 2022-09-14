---
title: MetaImageBase
second_title: GroupDocs.Editor for Java API Reference
description:  Base abstract class for WMF and EMF image formats
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Base abstract class for WMF and EMF image formats
## Constructors

| Constructor | Description |
| --- | --- |
| [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Common constructor, which prepares a creating a WMF or EMF instance from base64-encoded string |
| [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Common constructor, which prepares a creating a WMF or EMF instance from byte stream |
| [MetaImageBase(String name, System.IO.Stream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Determines whether specified byte stream contains a valid WMF image |
| [isValidWmfInternal(System.IO.Stream binaryContent)](#isValidWmfInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Determines whether specified string contains a valid WMF image, which is encoded with base64 |
| [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Determines whether specified byte stream contains a valid EMF image |
| [isValidEmfInternal(System.IO.Stream binaryContent)](#isValidEmfInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Determines whether specified string contains a valid EMF image, which is encoded with base64 |
| [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | In implementing type should save a current vector meta-image to the vector SVG format into specified byte stream |
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Common constructor, which prepares a creating a WMF or EMF instance from base64-encoded string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Mandatory name |
| contentInBase64 | java.lang.String | Content as base64 string. Should be not NULL or empty. |
| isWmf | boolean | true for WMF, false for EMF |

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Common constructor, which prepares a creating a WMF or EMF instance from byte stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Mandatory name |
| binaryContent | java.io.InputStream | Content as byte stream. Should be valid. |
| isWmf | boolean | true for WMF, false for EMF |

### MetaImageBase(String name, System.IO.Stream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public MetaImageBase(String name, System.IO.Stream binaryContent, boolean isWmf)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |
| isWmf | boolean |  |

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Determines whether specified byte stream contains a valid WMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Input byte stream. Should be valid. |

**Returns:**
boolean - Returns 'true' if valid and 'false' if invalid
### isValidWmfInternal(System.IO.Stream binaryContent) {#isValidWmfInternal-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValidWmfInternal(System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Determines whether specified string contains a valid WMF image, which is encoded with base64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | String, which is assumed to contain a base64-encoded WMF image |

**Returns:**
boolean - Returns 'true' if valid and 'false' if invalid
### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Determines whether specified byte stream contains a valid EMF image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Input byte stream. Should be valid. |

**Returns:**
boolean - Returns 'true' if valid and 'false' if invalid
### isValidEmfInternal(System.IO.Stream binaryContent) {#isValidEmfInternal-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValidEmfInternal(System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Determines whether specified string contains a valid EMF image, which is encoded with base64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | String, which is assumed to contain a base64-encoded EMF image |

**Returns:**
boolean - Returns 'true' if valid and 'false' if invalid
### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


In implementing type should save a current vector meta-image to the vector SVG format into specified byte stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputSvgContent | java.io.OutputStream | Byte stream, into which the SVG version of this vector meta-image will be stored. Should not be NULL and should support writing. |


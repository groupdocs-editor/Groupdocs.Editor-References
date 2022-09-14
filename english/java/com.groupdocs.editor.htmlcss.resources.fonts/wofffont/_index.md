---
title: WoffFont
second_title: GroupDocs.Editor for Java API Reference
description: Represents one font in the WOFF Web Open Font Format format
type: docs
weight: 17
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Represents one font in the WOFF (Web Open Font Format) format
## Constructors

| Constructor | Description |
| --- | --- |
| [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Creates new WoffFont class from content, represented as base64-encoded string, and with specified name |
| [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Creates new WoffFont class from content, represented as byte stream, and with specified name |
| [WoffFont(String name, System.IO.Stream binaryContent)](#WoffFont-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | WOFF header size (in bytes), which is required for its validation |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid WOFF font |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid WOFF font |
| [getType()](#getType--) | Returns FontType.Woff |
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Creates new WoffFont class from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WOFF font. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a WOFF content, exception will be thrown. |

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Creates new WoffFont class from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WOFF font. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seakable. If this instance will be disposed, this stream will be disposed too. |

### WoffFont(String name, System.IO.Stream binaryContent) {#WoffFont-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public WoffFont(String name, System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF header size (in bytes), which is required for its validation

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid WOFF font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a WOFF resource |

**Returns:**
boolean - True if specified stream contains valid WOFF font, false otherwise
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


Checks whether specified base64-encoded string is a valid WOFF font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably WOFF font in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid WOFF font, false otherwise
### getType() {#getType--}
```
public FontType getType()
```


Returns FontType.Woff

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

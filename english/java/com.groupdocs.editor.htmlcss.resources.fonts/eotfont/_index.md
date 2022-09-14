---
title: EotFont
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one font in the EOT Embedded OpenType format
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Represents one font in the EOT (Embedded OpenType) format
## Constructors

| Constructor | Description |
| --- | --- |
| [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Creates new EotFont class from content, represented as base64-encoded string, and with specified name |
| [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Creates new EotFont class from content, represented as byte stream, and with specified name |
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | EOT header size (in bytes), which is required for its validation |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid EOT font |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid EOT font |
| [getType()](#getType--) | Returns FontType.Eot |
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Creates new EotFont class from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the EOT font. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a EOT content, exception will be thrown. |

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Creates new EotFont class from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the EOT font. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT header size (in bytes), which is required for its validation

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid EOT font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a EOT resource |

**Returns:**
boolean - True if specified stream contains valid EOT font, false otherwise
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


Checks whether specified base64-encoded string is a valid EOT font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably EOT font in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid EOT font, false otherwise
### getType() {#getType--}
```
public FontType getType()
```


Returns FontType.Eot

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

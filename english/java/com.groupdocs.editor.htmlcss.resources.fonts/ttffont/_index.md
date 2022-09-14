---
title: TtfFont
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one font in the TTF TrueType Font format
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Represents one font in the TTF (TrueType Font) format
## Constructors

| Constructor | Description |
| --- | --- |
| [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Creates new TtfFont class from content, represented as base64-encoded string, and with specified name |
| [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Creates new TtfFont class from content, represented as byte stream, and with specified name |
| [TtfFont(String name, System.IO.Stream binaryContent)](#TtfFont-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | TTF header size (in bytes), which is required for its validation |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid TTF font |
| [isValidInternal(System.IO.Stream binaryContent)](#isValidInternal-com.aspose.ms.System.IO.Stream-) |  |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid TTF font |
| [getType()](#getType--) | Returns FontType.Ttf |
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Creates new TtfFont class from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the TTF font. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a TTF content, exception will be thrown. |

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Creates new TtfFont class from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the TTF font. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### TtfFont(String name, System.IO.Stream binaryContent) {#TtfFont-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TtfFont(String name, System.IO.Stream binaryContent)
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


TTF header size (in bytes), which is required for its validation

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid TTF font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a TTF resource |

**Returns:**
boolean - True if specified stream contains valid TTF font, false otherwise
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


Checks whether specified base64-encoded string is a valid TTF font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably TTF font in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid TTF font, false otherwise
### getType() {#getType--}
```
public FontType getType()
```


Returns FontType.Ttf

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

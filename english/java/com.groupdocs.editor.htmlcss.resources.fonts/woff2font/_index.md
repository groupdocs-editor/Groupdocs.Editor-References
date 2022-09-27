---
title: Woff2Font
second_title: GroupDocs.Editor for Java API Reference
description: Represents one font in the WOFF2 Web Open Font Format format
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Represents one font in the WOFF2 (Web Open Font Format) format
## Constructors

| Constructor | Description |
| --- | --- |
| [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Creates new Woff2Font class from content, represented as base64-encoded string, and with specified name |
| [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Creates new Woff2Font class from content, represented as byte stream, and with specified name |
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2 header size (in bytes), which is required for its validation |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid WOFF2 font |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid WOFF2 font |
| [getType()](#getType--) | Returns FontType.Woff2 |
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Creates new Woff2Font class from content, represented as base64-encoded string, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WOFF2 font. Cannot be null, empty or whitespaces. |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a WOFF2 content, exception will be thrown. |

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Creates new Woff2Font class from content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the WOFF2 font. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seakable. If this instance will be disposed, this stream will be disposed too. |

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2 header size (in bytes), which is required for its validation

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid WOFF2 font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a WOFF2 resource |

**Returns:**
boolean - True if specified stream contains valid WOFF2 font, false otherwise
### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid WOFF2 font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably WOFF2 font in a form of base64-encoded string |

**Returns:**
boolean - True if specified string contains valid WOFF2 font, false otherwise
### getType() {#getType--}
```
public FontType getType()
```


Returns FontType.Woff2

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

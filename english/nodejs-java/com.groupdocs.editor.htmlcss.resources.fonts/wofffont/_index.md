---
title: WoffFont
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one font in the WOFF Web Open Font Format format
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
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
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | WOFF header size (in bytes), which is required for its validation |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid WOFF font |
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

---
title: TtcFont
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one font in the TTC TrueType Collection format
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Represents one font in the TTC (TrueType Collection) format


See more: https://docs.fileformat.com/font/ttc/

## Constructors

| Constructor | Description |
| --- | --- |
| [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Creates new TtcFont class from content, represented as base64-encoded
string, and with specified name
 |
| [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Creates new TtcFont class from content, represented as byte stream, and
with specified name
 |
## Fields

| Field | Description |
| --- | --- |
| [RequiredHeaderSize](#RequiredHeaderSize) | TTC header size (in bytes), which is required for its validation
 |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid TTC font
 |
| [isValid(String contentInBase64)](#isValid-java.lang.String-) | Checks whether specified base64-encoded string is a valid TTC font
 |
| [getType()](#getType--) | Returns FontType.Ttc
 |
| [getHeaderVersion()](#getHeaderVersion--) | TTC Header Version, may be "1" or "2"
 |
| [getFontsNumber()](#getFontsNumber--) | Number of fonts in this TTC
 |
| [getHasDsigTable()](#getHasDsigTable--) | Indicates whether this TTC has a DSIG table.
 |
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Creates new TtcFont class from content, represented as base64-encoded
string, and with specified name


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the TTC font. Cannot be null, empty or whitespaces.
 |
| contentInBase64 | java.lang.String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a TTC content, exception will be thrown.
 |

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Creates new TtcFont class from content, represented as byte stream, and
with specified name


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the TTC font. Cannot be null, empty or whitespaces.
 |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too.
 |

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC header size (in bytes), which is required for its validation


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid TTC font


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a TTC resource
 |

**Returns:**
boolean - True if specified stream contains valid TTC font, false otherwise

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Checks whether specified base64-encoded string is a valid TTC font


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentInBase64 | java.lang.String | Content of the presumably TTC font in a form of base64-encoded string
 |

**Returns:**
boolean - True if specified string contains valid TTC font, false otherwise

### getType() {#getType--}
```
public FontType getType()
```


Returns FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC Header Version, may be "1" or "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Number of fonts in this TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Indicates whether this TTC has a DSIG table. DSIG table may be present
only if TTC has a Header version 2.0.


**Returns:**
boolean

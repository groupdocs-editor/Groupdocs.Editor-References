---
title: FontParser
second_title: GroupDocs.Editor for Java API Reference
description:  Contains a font parser which obtains an input font of unknown type as a byte
 stream or base64-encoded text and returns its type-defined object
 representation
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/fontparser/
---
**Inheritance:**
java.lang.Object
```
public class FontParser
```

Contains a font parser, which obtains an input font of unknown type as a byte stream or base64-encoded text and returns its type-defined object representation
## Constructors

| Constructor | Description |
| --- | --- |
| [FontParser()](#FontParser--) |  |
## Methods

| Method | Description |
| --- | --- |
| [fromFile(String filePath)](#fromFile-java.lang.String-) | Returns an instance of the font-representing class, parsing a file by specified file path. |
| [parse(String base64Content, String name, FontType assumptiveType)](#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Returns an instance of the font-representing class, parsing specified base64-encoded content and detecting font type from its header. |
| [parse(System.IO.Stream binaryContent, String name, FontType assumptiveType)](#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Returns an instance of the font-representing class, parsing specified binary content and detecting font type from its header. |
### FontParser() {#FontParser--}
```
public FontParser()
```


### fromFile(String filePath) {#fromFile-java.lang.String-}
```
public static FontResourceBase fromFile(String filePath)
```


Returns an instance of the font-representing class, parsing a file by specified file path. Determines font type automatically and applies filename as a font name. Returns NULL, if font format cannot be parsed or file is not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the file. If doesn't exist, the method will return NULL. |

**Returns:**
[FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) - 
### parse(String base64Content, String name, FontType assumptiveType) {#parse-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static FontResourceBase parse(String base64Content, String name, FontType assumptiveType)
```


Returns an instance of the font-representing class, parsing specified base64-encoded content and detecting font type from its header. Returns NULL, if font format cannot be parsed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| base64Content | java.lang.String |  |
| name | java.lang.String |  |
| assumptiveType | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) |  |

**Returns:**
[FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) - 
### parse(System.IO.Stream binaryContent, String name, FontType assumptiveType) {#parse-com.aspose.ms.System.IO.Stream-java.lang.String-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static FontResourceBase parse(System.IO.Stream binaryContent, String name, FontType assumptiveType)
```


Returns an instance of the font-representing class, parsing specified binary content and detecting font type from its header. Returns NULL, if font format cannot be parsed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream | Byte stream with content of the font of undetected format. Cannot be NULL, should be readable, seakable, should not be empty and with valid position, which doesn't point to the last byte. |
| name | java.lang.String | Font name (assuming filename), which extension will be analyzed for making an assumption about font format. Cannot be null, empty or whitespaced. |
| assumptiveType | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) |  |

**Returns:**
[FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) - 

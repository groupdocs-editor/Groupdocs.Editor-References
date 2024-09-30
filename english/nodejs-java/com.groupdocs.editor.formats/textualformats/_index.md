---
title: TextualFormats
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates all textual text-based formats including markup XML HTML and others.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Encapsulates all textual (text-based) formats, including markup (XML, HTML) and others. Includes the following formats: [Html](../../com.groupdocs.editor.formats/textualformats\#Html), [Txt](../../com.groupdocs.editor.formats/textualformats\#Txt), [Xml](../../com.groupdocs.editor.formats/textualformats\#Xml). [Md](../../com.groupdocs.editor.formats/textualformats\#Md), [Json](../../com.groupdocs.editor.formats/textualformats\#Json).
## Fields

| Field | Description |
| --- | --- |
| [Html](#Html) | HyperText Markup Language document (HTML) is the extension for web pages created for display in browsers. |
| [Xml](#Xml) | eXtensible Markup Language document (XML) that is similar to HTML but different in using tags for defining objects. |
| [Txt](#Txt) | Plain Text Document (TXT) represents a text document that contains plain text in the form of lines. |
| [Md](#Md) | Markdown is a lightweight markup language for creating formatted text using a plain-text editor. |
| [Json](#Json) | JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. |
| [Mhtml](#Mhtml) | MIME encapsulation of aggregate HTML documents is a web page archive format used to combine, in a single computer file, the HTML code and its companion resources. |
| [Chm](#Chm) | Microsoft Compiled HTML Help is a Microsoft proprietary online help binary format, consisting of a collection of HTML pages, an index and other navigation tools. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets an enumerable collection of all [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Retrieves an instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) that has the specified file extension. |
| [fromString(String extension)](#fromString-java.lang.String-) | Converts a string representing a file extension to a [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object. |
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language document (HTML) is the extension for web pages created for display in browsers. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/web/html

### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language document (XML) that is similar to HTML but different in using tags for defining objects. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/web/xml

### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) represents a text document that contains plain text in the form of lines. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final TextualFormats Md
```


Markdown is a lightweight markup language for creating formatted text using a plain-text editor. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/md/

### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/json/

### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME encapsulation of aggregate HTML documents is a web page archive format used to combine, in a single computer file, the HTML code and its companion resources. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/mhtml/

### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help is a Microsoft proprietary online help binary format, consisting of a collection of HTML pages, an index and other navigation tools. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/chm/

### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Gets an enumerable collection of all [TextualFormats](../../com.groupdocs.editor.formats/textualformats).

Value: An  IEnumerable\{TextualFormats\}  containing all instances of [TextualFormats](../../com.groupdocs.editor.formats/textualformats).

**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Retrieves an instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) that has the specified file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension of the document format. |

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.
### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Converts a string representing a file extension to a [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension to convert. If the extension contains multiple periods, the part after the last period is used. |

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

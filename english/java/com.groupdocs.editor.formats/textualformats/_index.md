---
title: TextualFormats
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates all textual text-based formats including markup XML HTML and others.
type: docs
weight: 14
url: /java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat)
```
public class TextualFormats implements IDocumentFormat
```

Encapsulates all textual (text-based) formats, including markup (XML, HTML) and others. Includes the following formats: [Html](../../com.groupdocs.editor.formats/textualformats\#Html), [Txt](../../com.groupdocs.editor.formats/textualformats\#Txt), [Xml](../../com.groupdocs.editor.formats/textualformats\#Xml). [Md](../../com.groupdocs.editor.formats/textualformats\#Md), [Json](../../com.groupdocs.editor.formats/textualformats\#Json).
## Constructors

| Constructor | Description |
| --- | --- |
| [TextualFormats()](#TextualFormats--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Html](#Html) | HyperText Markup Language document (HTML) is the extension for web pages created for display in browsers. |
| [Xml](#Xml) | eXtensible Markup Language document (XML) that is similar to HTML but different in using tags for defining objects. |
| [Txt](#Txt) | Plain Text Document (TXT) represents a text document that contains plain text in the form of lines. |
| [Md](#Md) | Markdown is a lightweight markup language for creating formatted text using a plain-text editor. |
| [Json](#Json) | JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. |
| [All](#All) | Returns an internal class, that provides enumerable possibilities over all existing Textual formats. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a formal full name of this textual format |
| [getExtension()](#getExtension--) | Returns an extension (without leading dot character) of this textual format in lower case |
| [getMime()](#getMime--) | Returns a MIME code for this format |
| [toString()](#toString--) | Returns the name of this particular format, same as 'Name' property |
| [op_Equality(TextualFormats first, TextualFormats second)](#op-Equality-com.groupdocs.editor.formats.TextualFormats-com.groupdocs.editor.formats.TextualFormats-) | Checks two given TextualFormats instances on equality |
| [op_Inequality(TextualFormats first, TextualFormats second)](#op-Inequality-com.groupdocs.editor.formats.TextualFormats-com.groupdocs.editor.formats.TextualFormats-) | Checks two given TextualFormats instances on inequality |
| [equals(TextualFormats other)](#equals-com.groupdocs.editor.formats.TextualFormats-) | Determines whether this instance is equal to the other specified TextualFormats instance |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.IDocumentFormat-) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the other specified object, that is presumably of boxed TextualFormats |
| [hashCode()](#hashCode--) | Returns a hash-code, that is immutable for this instance |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Returns instance of [TextualFormats](../../com.groupdocs.editor.formats/textualformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
### TextualFormats() {#TextualFormats--}
```
public TextualFormats()
```


### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language document (HTML) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language document (XML) that is similar to HTML but different in using tags for defining objects. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/xml

### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document (TXT) represents a text document that contains plain text in the form of lines. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final TextualFormats Md
```


Markdown is a lightweight markup language for creating formatted text using a plain-text editor. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/word-processing/md/

### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/json/

### All {#All}
```
public static final TextualFormats.AllEnumerable All
```


Returns an internal class, that provides enumerable possibilities over all existing Textual formats.

### getName() {#getName--}
```
public final String getName()
```


Returns a formal full name of this textual format

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Returns an extension (without leading dot character) of this textual format in lower case

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public final String getMime()
```


Returns a MIME code for this format

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns the name of this particular format, same as 'Name' property

**Returns:**
java.lang.String - A String that represents this instance
### op_Equality(TextualFormats first, TextualFormats second) {#op-Equality-com.groupdocs.editor.formats.TextualFormats-com.groupdocs.editor.formats.TextualFormats-}
```
public static boolean op_Equality(TextualFormats first, TextualFormats second)
```


Checks two given TextualFormats instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) | First TextualFormats instance to check |
| second | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) | Second TextualFormats instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(TextualFormats first, TextualFormats second) {#op-Inequality-com.groupdocs.editor.formats.TextualFormats-com.groupdocs.editor.formats.TextualFormats-}
```
public static boolean op_Inequality(TextualFormats first, TextualFormats second)
```


Checks two given TextualFormats instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) | First TextualFormats instance to check |
| second | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) | Second TextualFormats instance to check |

**Returns:**
boolean - True if are not equal, false if are equal
### equals(TextualFormats other) {#equals-com.groupdocs.editor.formats.TextualFormats-}
```
public final boolean equals(TextualFormats other)
```


Determines whether this instance is equal to the other specified TextualFormats instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) | Other TextualFormats instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determines whether this instance is equal to the other specified IDocumentFormat instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) | Other IDocumentFormat instance. If it is not a TextualFormats, method will return 'false' |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the other specified object, that is presumably of boxed TextualFormats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other boxed TextualFormats instance |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, that is immutable for this instance

**Returns:**
int - Signed 4-byte integer
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Returns instance of [TextualFormats](../../com.groupdocs.editor.formats/textualformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Filename extension of any supportable textual format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - Instance of TextualFormats structure on success or thrown exception on failure

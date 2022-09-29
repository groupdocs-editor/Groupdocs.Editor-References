---
title: TextualFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all textual textbased formats including markup XML HTML and others. Includes the following formats Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml. Md./textualformats/md Json./textualformats/json.
type: docs
weight: 150
url: /net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Encapsulates all textual (text-based) formats, including markup (XML, HTML) and others. Includes the following formats: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml). [`Md`](./md), [`Json`](./json).

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Returns an extension (without leading dot character) of this textual format in lower case |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Returns a MIME code for this format |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Returns a formal full name of this textual format |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Returns instance of [`TextualFormats`](../textualformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Determines whether this instance is equal to the other specified object, that is presumably of boxed TextualFormats |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Determines whether this instance is equal to the other specified TextualFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Returns a hash-code, that is immutable for this instance |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Returns the name of this particular format, same as 'Name' property |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Checks two given TextualFormats instances on equality |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Checks two given TextualFormats instances on inequality |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help is a Microsoft proprietary online help binary format, consisting of a collection of HTML pages, an index and other navigation tools. Learn more about this file format [here](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language document (HTML) is the extension for web pages created for display in browsers. Learn more about this file format [here](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) is an open standard file format for sharing data that uses human-readable text to store and transmit data. Learn more about this file format [here](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown is a lightweight markup language for creating formatted text using a plain-text editor. Learn more about this file format [here](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME encapsulation of aggregate HTML documents is a web page archive format used to combine, in a single computer file, the HTML code and its companion resources. Learn more about this file format [here](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) represents a text document that contains plain text in the form of lines. Learn more about this file format [here](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language document (XML) that is similar to HTML but different in using tags for defining objects. Learn more about this file format [here](https://wiki.fileformat.com/web/xml). |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Returns an internal class, that provides enumerable possibilities over all existing Textual formats. |

## Other Members

| Name | Description |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implements IEnumerable generic interface, that enables a 'foreach' possibility for the TextualFormats type |

### See Also

* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

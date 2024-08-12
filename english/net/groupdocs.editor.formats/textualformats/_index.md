---
title: TextualFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all textual textbased formats including markup XML HTML and others. Includes the following formats Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm.
type: docs
weight: 140
url: /net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Encapsulates all textual (text-based) formats, including markup (XML, HTML) and others. Includes the following formats: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Gets the file extension of the document format. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Gets the format family to which the document format belongs. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Gets the unique identifier for the format family. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Gets the MIME type of the document format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Gets the name of the format family. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Gets an enumerable collection of all [`TextualFormats`](../textualformats). |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Retrieves an instance of the specified type [`TextualFormats`](../textualformats) that has the specified file extension. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instance. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determines whether this instance is equal to the specified [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instance. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determines whether this instance is equal to the specified [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instance. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returns a hash code for the current object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returns a string that represents the current object. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Converts a string representing a file extension to a [`TextualFormats`](../textualformats) object. |

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

### See Also

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

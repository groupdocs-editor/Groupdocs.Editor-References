---
title: PresentationFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all Presentation formats. Includes the following formats
type: docs
weight: 120
url: /net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Encapsulates all Presentation formats. Includes the following formats:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

Learn more about Presentation formats [here](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Gets the file extension of the document format. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Gets the format family to which the document format belongs. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Gets the unique identifier for the format family. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Gets the MIME type of the document format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Gets the name of the format family. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Gets an enumerable collection of all [`PresentationFormats`](../presentationformats). |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Retrieves an instance of the specified type [`PresentationFormats`](../presentationformats) that has the specified file extension. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instance. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determines whether this instance is equal to the specified [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instance. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determines whether this instance is equal to the specified [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instance. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returns a hash code for the current object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returns a string that represents the current object. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Converts a string representing a file extension to a [`PresentationFormats`](../presentationformats) object. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Learn more about this file format [here](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP). Learn more about this file format [here](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT). Learn more about this file format [here](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Learn more about this file format [here](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Learn more about this file format [here](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS). Learn more about this file format [here](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentation (PPT). Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Presentation (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM). Learn more about this file format [here](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML Macro-Free Document (PPTX). Learn more about this file format [here](https://wiki.fileformat.com/presentation/pptx). |

### See Also

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

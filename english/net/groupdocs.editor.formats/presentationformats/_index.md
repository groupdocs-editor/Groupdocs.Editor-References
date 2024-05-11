---
title: PresentationFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all Presentation formats. Includes the following formats Odp./presentationformats/odp Otp./presentationformats/otp Pot./presentationformats/pot Potm./presentationformats/potm Potx./presentationformats/potx Pps./presentationformats/pps Ppsm./presentationformats/ppsm Ppsx./presentationformats/ppsx Ppt./presentationformats/ppt Ppt95./presentationformats/ppt95 Pptm./presentationformats/pptm Pptx./presentationformats/pptx. Learn more about Presentation formats herehttps//wiki.fileformat.com/presentation.
type: docs
weight: 120
url: /net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Encapsulates all Presentation formats. Includes the following formats: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Ppt95`](./ppt95), [`Pptm`](./pptm), [`Pptx`](./pptx). Learn more about Presentation formats [here](https://wiki.fileformat.com/presentation).

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Returns an extension (without leading dot character) of this Presentation format in lower case |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Returns a MIME code for this format |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Returns a formal full name of this Presentation format |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Returns instance of [`PresentationFormats`](../presentationformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Determines whether this instance is equal to the other specified object, that is presumably of boxed PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Determines whether this instance is equal to the other specified PresentationFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Returns a hash-code, that is immutable for this instance |
| override [ToString](../../groupdocs.editor.formats/presentationformats/tostring)() | Returns the name of this particular format, same as 'Name' property |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Checks two given PresentationFormats instances on equality |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Checks two given PresentationFormats instances on inequality |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP) file represents presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format [here](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP) file represents presentation template files created by applications in OASIS OpenDocument standard format. Learn more about this file format [here](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT) file represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Learn more about this file format [here](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) are files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. Learn more about this file format [here](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX) file represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. Learn more about this file format [here](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS) files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format [here](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) files are created with Microsoft PowerPoint 2007 or higher. Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format [here](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Presentation (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. Learn more about this file format [here](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) is a presentation file created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format [here](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Returns an internal class, that provides enumerable possibilities over all existing Presentation formats |

## Other Members

| Name | Description |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implements IEnumerable generic interface, that enables a 'foreach' possibility for the PresentationFormats type |

### See Also

* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

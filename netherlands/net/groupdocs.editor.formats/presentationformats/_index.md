---
title: "PresentationFormats"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Omvat alle presentatieformaten. Bevat de volgende formaten"
type: docs
weight: 120
url: /nl/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Omvat alle presentatieformaten. Bevat de volgende formaten:

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

Meer informatie over presentatieformaten [hier](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Haalt de bestandsextensie van het documentformaat op. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Haalt de formatfamilie op waartoe het documentformaat behoort. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Haalt de unieke identifier op voor de formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Haalt het MIME-type van het documentformaat op. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Haalt de naam van de formatfamilie op. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Haalt een doorzoekbare collectie op van alle [`PresentationFormats`](../presentationformats). |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Haalt een instantie op van het opgegeven type [`PresentationFormats`](../presentationformats) dat de opgegeven bestandsextensie heeft. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bepaalt of deze instantie gelijk is aan de opgegeven [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de opgegeven [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bepaalt of deze instantie gelijk is aan de opgegeven [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Retourneert een hashcode voor het huidige object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [`PresentationFormats`](../presentationformats)-object. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation-sjabloon (OTP). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentatiesjabloon (POT). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 Diavoorstelling (PPS). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentatie (PPT). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95-presentatie (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML macro-ingeschakeld document (PPTM). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML macro-vrij document (PPTX). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptx). |

### Zie ook

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

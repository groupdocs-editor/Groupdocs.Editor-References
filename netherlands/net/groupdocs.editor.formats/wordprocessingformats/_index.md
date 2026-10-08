---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Omvat alle WordProcessing-formaten. Bevat de volgende bestandstypen"
type: docs
weight: 150
url: /nl/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Omvat alle WordProcessing-formaten. Bevat de volgende bestandstypen:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Meer informatie over Word Processing-formaten [hier](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Haalt de bestandsextensie van het documentformaat op. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Haalt de formatfamilie op waartoe het documentformaat behoort. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Haalt de unieke identifier op voor de formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Haalt het MIME-type van het documentformaat op. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Haalt de naam van de formatfamilie op. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Haalt een doorzoekbare collectie op van alle [`WordProcessingFormats`](../wordprocessingformats). |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Haalt een instantie op van het opgegeven type [`WordProcessingFormats`](../wordprocessingformats) dat de opgegeven bestandsextensie heeft. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bepaalt of deze instantie gelijk is aan de opgegeven [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de opgegeven [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bepaalt of deze instantie gelijk is aan de opgegeven [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Retourneert een hashcode voor het huidige object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [`WordProcessingFormats`](../wordprocessingformats) object. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 binair bestandsformaat (DOC) vertegenwoordigt documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM)-bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) is een bekend formaat voor Microsoft Word-documenten. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template (DOT) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) vertegenwoordigt sjabloonbestanden die zijn gemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Text Document (ODT)-bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument-tekstbestandsformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) vertegenwoordigt sjabloondocumenten die door applicaties worden gegenereerd in overeenstemming met het OpenDocument-standaardformaat van OASIS. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en afbeeldingen te coderen voor gebruik binnen applicaties. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML-formaat — WordProcessingML of WordML (.XML). |

### Zie ook

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

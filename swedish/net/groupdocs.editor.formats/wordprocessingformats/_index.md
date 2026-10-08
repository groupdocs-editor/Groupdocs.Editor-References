---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innesluter alla WordProcessing-format. Inkluderar följande filtyper"
type: docs
weight: 150
url: /sv/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Innesluter alla ordbehandlingsformat. Inkluderar följande filtyper:

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

Läs mer om Word Processing-format [här](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Hämtar en uppräkningsbar samling av alla [`WordProcessingFormats`](../wordprocessingformats). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Hämtar en instans av den angivna typen [`WordProcessingFormats`](../wordprocessingformats) som har den angivna filändelsen. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Konverterar en sträng som representerar en filändelse till ett [`WordProcessingFormats`](../wordprocessingformats)-objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM)-filer är dokument som genererats av Microsoft Word 2007 eller senare med möjlighet att köra makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) är ett välkänt format för Microsoft Word-dokument. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template (DOT) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representerar mallfiler skapade med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML lagras i en platt XML-fil istället för ett ZIP-paket. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Text Document (ODT)-filer är en typ av dokument som skapats med ordbehandlingsprogram baserade på OpenDocument Text File-formatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) representerar mall-dokument som genererats av program i enlighet med OASIS' OpenDocument-standardformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i program. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML eller WordML (.XML). |

### Se även

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

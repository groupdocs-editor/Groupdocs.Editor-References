---
title: WordProcessingFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla WordProcessingformat. Inkluderar följande filtyper Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Läs mer om ordbehandlingsformathärhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /sv/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Kapslar in alla WordProcessing-format. Inkluderar följande filtyper: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Läs mer om ordbehandlingsformat[här](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Returnerar ett tillägg (utan inledande punkttecken) av detta ordbehandlingsformat med gemener |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Returnerar en MIME-kod för detta format |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Returnerar ett formellt fullständigt namn på detta WordProcessing format |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Returnerar instans av[`WordProcessingFormats`](../wordprocessingformats)struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Bestämmer om denna instans är lika med det andra angivna objektet, det vill säga antagligen av WordProcessingFormats |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Avgör om denna instans är lika med den andra angivna WordProcessingFormats-instansen |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Returnerar namnet på detta specifika format, samma som "Namn" egenskap |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Kontrollerar två givna WordProcessingFormats-instanser på equality |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Returnerar ett bytevärde från underliggande fält för specificerad WordProcessingFormats-instans (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Kontrollerar två givna WordProcessingFormats-instanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binärt filformat (DOC) representerar dokument som genereras av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML DOCM-filer (Macro-Enabled Document) är Microsoft Word 2007 eller högre genererade dokument med möjlighet att köra makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanligt binärt till en kombination av XML och binära filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Mall är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representerar mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML lagrad i en platt XML-fil istället för ett ZIP-paket |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Text Document (ODT)-filer är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Öppet dokumentformat Textdokumentmall (OTT) representerar malldokument som genereras av applikationer i överensstämmelse med OASIS OpenDocument-standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML-format — WordProcessingML eller WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga WordProcessing-format |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för WordProcessingFormats type |

### Anmärkningar

MIME-koder hämtas från de givna resurserna: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

---
title: "Formatfamiljer"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar de olika formatfamiljerna som finns tillgängliga i systemet."
type: docs
weight: 110
url: /sv/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Representerar de olika formatfamiljerna som finns tillgängliga i systemet.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | Representerar e‑bokformatfamiljen. Läs mer om Mobi‑formatet [här](https://docs.fileformat.com/ebook/mobi/), om AZW3‑formatet [här](https://docs.fileformat.com/ebook/azw3/), och om ePub‑formatet [här](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Representerar e‑postformatfamiljen. Läs mer om e‑postformat [här](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Representerar formatfamiljen för fast layout. Olika dokumentvisnings‑ eller publiceringsprogram tillåter användare att öppna (Adobe Acrobat, XPS Viewer) och ibland redigera (Adobe InDesign) dokument av specifika format. Dessa program producerar vanligtvis så kallade ”fast‑sid‑”formatdokument. Ett sådant dokumentformat beskriver exakt var dokumentets innehåll placeras på varje sida. Internt innehåller PDF‑ eller XPS‑formatet en beskrivning av varje sida samt ritinstruktioner som specificerar layouten för innehållet på sidan. Detta liknar bildformat, som beskriver var innehållet visas antingen i raster‑ eller vektorform. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Representerar presentationsformatfamiljen. Läs mer om presentationsformat [här](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Representerar kalkylbladsformatfamiljen. Alla binära, XML‑ och textbaserade kalkylbladsformat (exklusive alla textbaserade, avgränsare‑baserade format med separatorer som CSV, TSV, semikolon‑avgränsade osv.) som arbetsboken kan sparas i. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Representerar textformatfamiljen. Inkapslar alla textbaserade (text‑baserade) format, inklusive markup (XML, HTML) och andra. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Representerar ordbehandlingsformatfamiljen. Läs mer om ordbehandlingsformat [här](https://wiki.fileformat.com/word-processing). |

### Se även

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

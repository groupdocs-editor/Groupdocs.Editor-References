---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Gör det möjligt att ange anpassade alternativ för att generera och spara dokumentet i alla stödjade e‑bokformat ePub, MOBI och AZW3."
type: docs
weight: 840
url: /sv/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Tillåter att ange anpassade alternativ för att generera och spara dokumentet i alla stödbara e‑bokformat: ePub, MOBI och AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Denna parameterlösa konstruktor skapar en ny instans av EbookSaveOptions med ePub‑utdataformat (kan sedan ändras via egenskapen [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Skapar en ny instans av [`EbookSaveOptions`](../ebooksaveoptions) med angivet obligatoriskt e‑bokutdataformat, medan alla andra parametrar har standardvärden. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras i den resulterande filen. Standardvärdet är `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Anger formatet för den resulterande e‑bokfilen: IDPF ePub, MOBI eller AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | Anger den maximala rubriknivån vid vilken e‑bokfilen ska delas upp. Standardvärdet är `2`. Att sätta den till `0` inaktiverar uppdelning, så allt innehåll i e‑boken kommer att integreras i ett enda paket i den resulterande filen. |

### Anmärkningar

Stödda e‑bokformat:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Elektronisk publikation)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle-format 8t)

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

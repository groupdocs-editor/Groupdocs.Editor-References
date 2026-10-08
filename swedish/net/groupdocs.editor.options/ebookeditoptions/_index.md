---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange och justera anpassade alternativ för redigering av Ebook‑dokument i alla stödda format ePub, MOBI och AZW3."
type: docs
weight: 830
url: /sv/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Tillåter att ange och justera anpassade alternativ för redigering av e‑bokdokument i alla stödda format: ePub, MOBI och AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Initierar en ny instans av [`EbookEditOptions`](../ebookeditoptions)‑klassen, där alla alternativ är satta till sina standardvärden. |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Initierar en ny instans av [`EbookEditOptions`](../ebookeditoptions)‑klassen med angivet pagineringsläge. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Anger om språkinformation exporteras till HTML‑markup i form av 'lang'-HTML‑attribut. Detta alternativ kan vara användbart för rundresa‑konvertering av flerspråkiga dokument. Som standard är det inaktiverat (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML‑dokumentet. Som standard är det inaktiverat (`false`). |

### Anmärkningar

Stödda e‑bokformat:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Elektronisk publikation)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle-format 8t)

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

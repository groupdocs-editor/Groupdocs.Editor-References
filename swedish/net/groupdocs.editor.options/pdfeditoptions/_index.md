---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att redigera PDF-dokument"
type: docs
weight: 1050
url: /sv/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Tillåter att ange anpassade alternativ för att redigera PDF-dokument

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Skapar och returnerar en ny instans av klassen PdfEditOptions, där alla alternativ är satta till sina standardvärden. |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Skapar och returnerar en ny instans av klassen PdfEditOptions med angiven paginering och standardvärden för alla andra alternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Tillåter att aktivera (true) eller inaktivera (false) paginering i det resulterande HTML-dokumentet. Som standard är den inaktiverad (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Tillåter att ange ett sidintervall att bearbeta. Som standard bearbetas alla sidor i ett fast layout-dokument. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Hämtar eller anger flaggan som indikerar om bilder ska hoppas över vid konvertering av inmatningsdokument med fast layout till resulterande HTML. Standard är false – bilder bevaras. |

### Se även

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

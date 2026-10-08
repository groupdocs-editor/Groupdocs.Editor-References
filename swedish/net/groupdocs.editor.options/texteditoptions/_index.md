---
title: "TextEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för inläsning av enkla text‑TXT‑dokument"
type: docs
weight: 1150
url: /sv/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

Tillåter att ange anpassade alternativ för inläsning av ren text (TXT)-dokument

```csharp
public class TextEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextEditOptions](texteditoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | Tillåter att ange riktningen för textflödet i det inmatade enkla textdokumentet. Standard är Vänster‑till‑höger. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Standard är inaktiverad (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | Teckenkodning för textdokumentet som kommer att tillämpas vid öppning |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | Hämtar eller anger föredraget alternativ för hantering av inledande mellanslag. Standard konverterar inledande mellanslag till vänster indrag. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | Tillåter att ange hur numrerade listobjekt identifieras när dokumentet importeras från enkelt textformat. Standardvärdet är true. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | Hämtar eller anger föredraget alternativ för hantering av avslutande mellanslag. Standard tar bort alla avslutande mellanslag. |

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

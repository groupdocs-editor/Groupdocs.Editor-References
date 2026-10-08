---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara rena text‑TXT-dokument"
type: docs
weight: 1170
url: /sv/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

Tillåter att ange anpassade alternativ för generering och sparande av ren text (TXT)-dokument

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | Anger om bi‑direktionella markeringar ska läggas till före varje BiDi‑sekvens vid export i ren textformat. Standard är 'false' — lägg inte till BiDi‑markeringar. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | Teckenkodning för textdokumentet som kommer att användas vid sparning |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | Anger om programmet ska försöka bevara tabellernas layout vid sparning i ren textformat. Standardvärdet är false. |

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

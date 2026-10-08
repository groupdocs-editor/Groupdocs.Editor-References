---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Spreadsheet Excel‑kompatibla format."
type: docs
weight: 1110
url: /sv/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Spreadsheet (Excel-compatible)-format

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Tillåter att exkludera dolda kalkylblad i inmatnings‑Spreadsheet‑dokumentet, så att de helt ignoreras. Standard är false - dolda kalkylblad är tillgängliga och behandlas som vanliga. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | När den är aktiverad innehåller HTML‑tabellen i det genererade HTML‑dokumentet en tom dold rad längst ner med nollhöjd och tomma celler, där endast bredd anges. Denna rad med tomma celler innehåller exakta breddvärden för varje kolumn och förbättrar bakåtkonvertering från HTML till Spreadsheet. Som standard är den aktiverad (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | När den är aktiverad kommer de tomma intilliggande horisontella cellerna från inmatnings‑Spreadsheet‑dokumentet att representeras i det redigerbara HTML‑dokumentet som sammanslagna till en enda cell med motsvarande `colspan`‑attribut. Som standard är den inaktiverad (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Tillåter att ange det 0‑baserade indexet för kalkylbladet (fliken) i inmatnings‑Spreadsheet‑dokumentet som ska konverteras till HTML (se kommentarer). |

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innehåller alternativ för att läsa in binära Spreadsheet Cells Excel‑kompatibla dokument som XLSX, ODS etc. i Editor‑klassen"
type: docs
weight: 1120
url: /sv/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Innehåller alternativ för inläsning av binära Spreadsheet (Cells, Excel-compatible)-dokument, såsom XLS(X), ODS etc., i Editor-klassen

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Standardkonstruktör utan parametrar – alla parametrar har standardvärden |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, vilket kan försämra prestanda i vissa speciella fall, men å andra sidan minska minnesanvändningen. Användbart vid bearbetning av enorma dokument och när man stöter på OutOfMemoryException. Standard är false (minnesoptimering är inaktiverad för bättre prestanda). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att öppna Spreadsheet-dokumentet, om det är kodat. Sätt till NULL eller en tom sträng för att inte använda lösenordet (standardvärde). |

### Se även

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att dölja dolda arbetsblad i inmatnings‑Spreadsheet‑dokumentet så att de helt ignoreras. Standard är false – dolda arbetsblad är tillgängliga och behandlas som vanliga."
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Tillåter att exkludera dolda kalkylblad i inmatnings‑Spreadsheet‑dokumentet, så att de helt ignoreras. Standard är false - dolda kalkylblad är tillgängliga och behandlas som vanliga.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Anmärkningar

Flera binära Spreadsheet‑format (som XLSX) stödjer konceptet med dolda arbetsblad (flikar). Ett dokument i sådant format, om det har mer än ett arbetsblad, kan innehålla ytterligare dolda arbetsblad. Som standard är sådana dolda arbetsblad tillgängliga för bearbetning, men med detta alternativ kan de ignoreras, som om de dolda arbetsbladen saknas och inte existerar. När detta alternativ är aktiverat kan du inte välja ett dolt arbetsblad med egenskapen '[`WorksheetIndex`](../worksheetindex)'.

### Se även

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

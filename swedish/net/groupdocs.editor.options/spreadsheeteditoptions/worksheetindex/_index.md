---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange det 0‑baserade indexet för arbetsbladsfliken i inmatnings‑Spreadsheet‑dokumentet som ska konverteras till HTML, se kommentarer."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Tillåter att ange det 0‑baserade indexet för kalkylbladet (fliken) i inmatnings‑Spreadsheet‑dokumentet som ska konverteras till HTML (se kommentarer).

```csharp
public int WorksheetIndex { get; set; }
```

### Anmärkningar

De flesta kalkylbladsdokument stödjer ett koncept med flikar, d.v.s. de kan ha flera flikar. Å andra sidan stödjer HTML-formatet inte en sådan struktur. På grund av detta kan GroupDocs.Editor konvertera till HTML endast en specifik flik i inmatningsdokumentet, och detta alternativ gör det möjligt att ange den. Flikindex är 0-baserat, negativa värden är förbjudna. Om det angivna indexet överstiger antalet alla flikar kastas ett undantag. Om inmatningskalkylbladsdokumentet bara innehåller en flik ignoreras detta alternativ. Standardvärdet är 0 (första fliken).

### Se även

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

---
title: "WorksheetNumbersToDelete"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange en array med 1‑baserade nummer på kalkylblad som ska tas bort från kalkylbladet vid sparande när det redigerade kalkylbladet infogas i ett befintligt kalkylblad."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

Tillåter att ange en array med 1‑baserade nummer på kalkylblad som ska tas bort från kalkylarket vid sparande, om det redigerade kalkylbladet infogas i ett befintligt kalkylark.

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### Anmärkningar

När det redigerade kalkylbladet sparas inte som ett nytt kalkylblad med ett enda blad (standardbeteende), utan istället sparas i ett befintligt kalkylblad (med hjälp av egenskapen [`WorksheetNumber`](../worksheetnumber)), är det också möjligt att ta bort vissa specifika kalkylblad från detta kalkylblad genom att ange deras nummer i denna array.

Som standard är denna array `null` — inga kalkylblad kommer att tas bort. Men när arrayen är icke‑null och inte tom, och den innehåller minst ett giltigt kalkylbladsnummer, kommer kalkylbladen med angivna nummer att tas bort från kalkylbladet precis innan dess innehåll skrivs till utströmmen eller filen, efter att utdata‑kalkylbladet har genererats med innehållet från det redigerade kalkylbladet.

Kalkylbladsnummer i denna array är 1‑baserade, inte 0‑baserade; ogiltiga nummer (mindre än 1 eller större än det totala antalet kalkylblad) kommer att ignoreras.

### Se även

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

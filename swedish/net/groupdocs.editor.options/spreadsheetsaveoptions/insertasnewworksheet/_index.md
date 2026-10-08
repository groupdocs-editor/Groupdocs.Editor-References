---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Boolesk flagga som anger om det redigerade arbetsbladet ska ersätta det befintliga arbetsbladet i originalkalkylbladet på den position som anges av WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber property eller om det ska infogas mellan befintligt arbetsblad och föregående utan att ersätta dess innehåll. Som standard är false  befintligt arbetsblad kommer att ersättas. Denna egenskap ignoreras om värdet för WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber property är satt till 0."
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Boolesk flagga som anger om det redigerade arbetsbladet ska ersätta det befintliga arbetsbladet i originalkalkylbladet på den position som anges av [`WorksheetNumber`](../worksheetnumber) egenskap, eller om det ska infogas mellan befintligt arbetsblad och föregående utan att ersätta dess innehåll. Som standard är false — befintligt arbetsblad kommer att ersättas. Denna egenskap ignoreras, om värdet för [`WorksheetNumber`](../worksheetnumber) egenskap är satt till '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Anmärkningar

Som standard ersätts arbetsbladet. Det betyder att om det givna kalkylbladet har 5 arbetsblad och [`WorksheetNumber`](../worksheetnumber)=4, så kommer det fjärde arbetsbladet att ersättas med det nya redigerade arbetsbladet, medan det totala antalet arbetsblad i kalkylbladet (5) förblir oförändrat. Om värdet på den här egenskapen däremot sätts till true, kommer det nya redigerade arbetsbladet att injiceras som det fjärde arbetsbladet, och alla efterföljande arbetsblad kommer att flyttas till slutet: "gamla" fjärde arbetsbladet blir femte, och femte blir sjätte, och det totala antalet arbetsblad i kalkylbladet kommer att ökas med ett och bli 6.

### Se även

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

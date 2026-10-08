---
title: "WorksheetNumber"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att infoga det redigerade kalkylbladet i en kopia av ett befintligt kalkylblad istället för att skapa ett nytt kalkylblad med ett enda blad (standardbeteende). WorksheetNumber är ett 1‑baserat nummer på ett kalkylblad i kalkylbladet som laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas ett nytt kalkylblad med ett enda redigerat blad. Om det är större eller mindre än noll och ett giltigt kalkylblad är laddat i Editor‑klassen, kommer det redigerade kalkylbladet som representeras av den inmatade EditableDocument‑instansen att infogas i detta kalkylblad."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Tillåter att infoga ett redigerat kalkylblad i en kopia av ett befintligt kalkylark istället för att skapa ett nytt kalkylark med ett enda kalkylblad (standardbeteende). WorksheetNumber är ett 1‑baserat nummer på ett kalkylblad i kalkylarket som laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas det nya kalkylarket med ett enda redigerat kalkylblad. Om det är större eller mindre än noll, och det finns ett giltigt kalkylark laddat i Editor‑klassen, kommer det redigerade kalkylbladet, som representeras av den inmatade EditableDocument‑instansen, att infogas i detta kalkylark.

```csharp
public int WorksheetNumber { get; set; }
```

### Anmärkningar

WorksheetNumber heltals‑egenskap, om den inte är i standardläge (reserverat värde '0'), representerar ett arbetsbladnummer, så den börjar på 1, inte på noll, och dess maxvärde är antalet alla befintliga bilder i en presentation. Men om det angivna värdet är större än antalet alla bilder, kommer GroupDocs.Editor att justera det för att markera det sista arbetsbladet. Negativa värden är också tillåtna och räknar arbetsblad från slutet. Till exempel innebär "-1" sista arbetsbladet i ett kalkylblad, "-2" — näst sista, osv. På samma sätt som med positiva värden, när ett negativt arbetsbladnummer överstiger det totala antalet arbetsblad i det givna kalkylbladet, kommer det att justeras till det första arbetsbladet. Den [`InsertAsNewWorksheet`](../insertasnewworksheet) booleska egenskapen är starkt kopplad till denna.

### Exempel

Givet kalkylblad har 5 arbetsblad: WorksheetNumber = 0; — ignorera det givna kalkylbladet, skapa ett nytt kalkylblad och placera det redigerade arbetsbladet i det. WorksheetNumber = 1; — ersätt det första arbetsbladet med det redigerade. WorksheetNumber = 2; — ersätt det andra arbetsbladet med det redigerade. WorksheetNumber = 5; — ersätt det sista (5:e) arbetsbladet med det redigerade. WorksheetNumber = 6; — ersätt det sista (5:e) arbetsbladet med det redigerade, eftersom 6 är större än 5 och därför justeras. WorksheetNumber = -1; — ersätt det sista (5:e) arbetsbladet med det redigerade, eftersom "-1" betyder "sista befintliga". WorksheetNumber = -2; — ersätt det fjärde arbetsbladet med det redigerade. WorksheetNumber = -3; — ersätt det tredje arbetsbladet med det redigerade. WorksheetNumber = -4; — ersätt det andra arbetsbladet med det redigerade. WorksheetNumber = -5; — ersätt det första arbetsbladet med det redigerade. WorksheetNumber = -6; — ersätt det första arbetsbladet med det redigerade, eftersom "-6" är större än 5 och därför justeras.

### Se även

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

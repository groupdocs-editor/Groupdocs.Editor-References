---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Spreadsheet Excelcompliant-dokument"
type: docs
weight: 1130
url: /sv/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Tillåter att ange anpassade alternativ för generering och sparande av Spreadsheet (Excel-compliant)-dokument

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Denna parameterlösa konstruktor skapar en ny instans av SpreadsheetSaveOptions med XLSX‑utdataformat (kan sedan ändras via egenskapen [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Skapar en ny instans av SpreadsheetSaveOptions med angivet obligatoriskt Spreadsheet‑utdataformat, medan alla andra parametrar är standard |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Boolesk flagga som anger om det redigerade kalkylbladet ska ersätta det befintliga kalkylbladet i originalkalkylarket på den position som anges av egenskapen [`WorksheetNumber`](./worksheetnumber), eller om det ska infogas mellan det befintliga kalkylbladet och det föregående utan att ersätta dess innehåll. Standardvärdet är falskt — det befintliga kalkylbladet kommer att ersättas. Denna egenskap ignoreras om värdet för egenskapen [`WorksheetNumber`](./worksheetnumber) är satt till '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Tillåter att ange ett Spreadsheet‑format som ska användas för att spara dokumentet |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Tillåter att ange, ändra, hämta eller ta bort ett lösenord som ska användas för att kryptera det genererade Spreadsheet‑dokumentet, om detta dokumentformat stöder lösenordsskydd. Ange NULL eller en tom sträng för att ta bort (rensa) lösenordet. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Tillåter att infoga ett redigerat kalkylblad i en kopia av ett befintligt kalkylark istället för att skapa ett nytt kalkylark med ett enda kalkylblad (standardbeteende). WorksheetNumber är ett 1‑baserat nummer på ett kalkylblad i kalkylarket som laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas det nya kalkylarket med ett enda redigerat kalkylblad. Om det är större eller mindre än noll, och det finns ett giltigt kalkylark laddat i Editor‑klassen, kommer det redigerade kalkylbladet, som representeras av den inmatade EditableDocument‑instansen, att infogas i detta kalkylark. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Tillåter att ange en array med 1‑baserade nummer på kalkylblad som ska tas bort från kalkylarket vid sparande, om det redigerade kalkylbladet infogas i ett befintligt kalkylark. |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Tillåter att aktivera ett kalkylblads‑skydd för det genererade Spreadsheet‑dokumentet. Standardvärdet är NULL – skyddet tillämpas inte. Alla format stödjer inte kalkylblads‑skydd. |

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Alternativ för inläsning av textbaserade Spreadsheet-dokument, CSV, tabbaserade etc. som använder ett avgränsningstecken."
type: docs
weight: 810
url: /sv/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Alternativ för att läsa in textbaserade kalkylbladsdokument (CSV, tabbaserade etc.) som använder en separator (avgränsare)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Skapar en instans av alternativklassen för avgränsad text med obligatorisk avgränsare (separator). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Hämtar eller anger ett värde som indikerar om strängen i ett textbaserat dokument konverteras till datumdata. Standard är `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Hämtar eller anger ett värde som indikerar om strängen i ett textbaserat dokument konverteras till numerisk data. Standard är `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Aktiverar minnesoptimeringsmekanismer under bearbetning av inmatningsdokument, vilket kan försämra prestanda i vissa speciella fall, men å andra sidan minska minnesanvändningen. Användbart vid bearbetning av enorma dokument och när man stöter på OutOfMemoryException. Standard är `false` (minnesoptimering är inaktiverad för bättre prestanda). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Tillåter att ange en teckenseparator (avgränsare) för textbaserade kalkylbladsdokument |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Definierar om på varandra följande avgränsare ska behandlas som en. Standard är `false`. |

### Anmärkningar

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

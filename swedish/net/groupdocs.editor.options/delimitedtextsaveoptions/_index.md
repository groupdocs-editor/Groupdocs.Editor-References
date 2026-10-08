---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument som CSV, Tab‑baserade etc., som använder ett avgränsartecken."
type: docs
weight: 820
url: /sv/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument (CSV, tabbaserade etc.) som använder en separator (avgränsare)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Denna parameterlösa konstruktor skapar en ny instans av DelimitedTextSaveOptions med ett semikolon (;) som standardavgränsare (kan sedan ändras via egenskapen [`Separator`](./separator)). |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Skapar en instans av alternativklassen för avgränsad text med obligatorisk avgränsare (separator). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Tillåter att ange en kodning för det textbaserade kalkylbladsdokumentet. Standardvärdet (och om inget anges) är UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Indikerar om separatorer ska skrivas ut för tom rad. Standardvärdet är `false` vilket betyder att innehållet för tom rad blir tomt. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Tillåter att ange en teckenseparator (avgränsare) för textbaserade kalkylbladsdokument |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Indikerar om inledande tomma rader och kolumner ska tas bort på samma sätt som MS Excel gör |

### Anmärkningar

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->

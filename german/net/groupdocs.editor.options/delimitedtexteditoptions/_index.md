---
title: DelimitedTextEditOptions
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Optionen zum Laden von textbasierten SpreadsheetDokumenten CSV Tabbasiert etc. die ein Trennzeichen Trennzeichen verwenden
type: docs
weight: 820
url: /de/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Optionen zum Laden von textbasierten Spreadsheet-Dokumenten (CSV, Tab-basiert etc.), die ein Trennzeichen (Trennzeichen) verwenden

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Erstellt eine Instanz der Optionsklasse für begrenzten Text mit obligatorischem Trennzeichen (Trennzeichen) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Zeichenfolge in einem textbasierten Dokument in die Datumsdaten konvertiert wird. Standard ist`FALSCH` . |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Zeichenfolge in einem textbasierten Dokument in numerische Daten konvertiert wird. Standard ist`FALSCH` . |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung von Eingabedokumenten, die in einigen Sonderfällen die Leistung beeinträchtigen können, aber auf der anderen Seite die Speichernutzung verringern. Nützlich, wenn große Dokumente verarbeitet werden und OutOfMemoryException gegenübersteht. Standard ist`FALSCH` (Speicheroptimierung ist zwecks besserer Leistung deaktiviert). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Ermöglicht die Angabe eines Zeichenkettentrennzeichens (Trennzeichen) für textbasierte Tabellenkalkulationsdokumente |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. Standardmäßig ist`FALSCH` . |

### Bemerkungen

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Siehe auch

* interface [IEditOptions](../ieditoptions)
* namensraum [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

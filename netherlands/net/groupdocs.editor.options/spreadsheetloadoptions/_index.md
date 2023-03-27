---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat opties voor het laden van binaire Spreadsheet Cells Excelcompatibele documenten zoals XLSX ODS etc. in Editor class
type: docs
weight: 1110
url: /nl/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Bevat opties voor het laden van binaire Spreadsheet (Cells, Excel-compatibele) documenten zoals XLS(X), ODS etc. in Editor class

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Standaard parameterloze constructor - alle parameters hebben standaardwaarden |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Maakt geheugenoptimalisatiemechanismen mogelijk tijdens de verwerking van invoerdocumenten, wat in sommige speciale gevallen de prestaties kan verminderen, maar aan de andere kant het geheugengebruik vermindert. Handig bij het verwerken van grote documenten en geconfronteerd met OutOfMemoryException. Standaard is false (geheugenoptimalisatie is uitgeschakeld voor betere prestaties). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Hiermee kunt u het wachtwoord specificeren, wijzigen en verkrijgen dat zal worden gebruikt voor het openen van het Spreadsheet-document, als het gecodeerd is. Ingesteld op NULL of lege tekenreeks om het wachtwoord niet te gebruiken (standaardwaarde). |

### Zie ook

* interface [ILoadOptions](../iloadoptions)
* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
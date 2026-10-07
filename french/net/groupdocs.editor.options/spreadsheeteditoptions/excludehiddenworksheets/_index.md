---
title: "ExcludeHiddenWorksheets"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'exclure les feuilles de calcul cachées dans le document Spreadsheet d'entrée afin qu'elles soient totalement ignorées. La valeur par défaut est false ; les feuilles cachées sont disponibles et traitées normalement."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Permet d'exclure les feuilles de calcul masquées dans le document Spreadsheet d'entrée, afin qu'elles soient totalement ignorées. Par défaut, c'est false - les feuilles de calcul masquées sont disponibles et traitées normalement.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Remarques

Plusieurs formats de Spreadsheet binaires (comme XLSX) prennent en charge le concept de feuilles de calcul cachées (onglets). Un document de ce format, s'il possède plus d'une feuille, peut contenir des feuilles cachées supplémentaires. Par défaut, ces feuilles cachées sont disponibles pour le traitement, mais avec cette option il est possible de les ignorer, comme si ces feuilles cachées étaient absentes et n'existaient pas. Lorsque cette option est activée, vous ne pouvez pas sélectionner une feuille cachée avec la propriété '[`WorksheetIndex`](../worksheetindex)'.

### Voir aussi

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: "WorksheetIndex"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier l'index basé à 0 de l'onglet de feuille de calcul du document Spreadsheet d'entrée qui doit être converti en HTML (voir remarques)."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Permet de spécifier l'index basé sur zéro de la feuille de calcul (onglet) du document Spreadsheet d'entrée, qui doit être converti en HTML (voir remarques).

```csharp
public int WorksheetIndex { get; set; }
```

### Remarques

La plupart des documents Spreadsheet prennent en charge le concept d'onglets, c'est‑à‑vous‑dire qu'ils peuvent être multi‑onglets. En revanche, le format HTML ne supporte pas une telle structure. Pour cette raison, le GroupDocs.Editor ne peut convertir en HTML qu'un seul onglet spécifique du document d'entrée, et cette option permet de le spécifier. L'index d'onglet est basé à 0, les valeurs négatives sont interdites. Si l'index spécifié dépasse le nombre total d'onglets, une exception sera levée. Si le document Spreadsheet d'entrée ne contient qu'un seul onglet, cette option sera ignorée. La valeur par défaut est 0 (premier onglet).

### Voir aussi

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

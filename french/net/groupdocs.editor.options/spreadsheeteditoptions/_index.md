---
title: "SpreadsheetEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour l'édition de documents de tous les formats de feuille de calcul compatibles Excel pris en charge"
type: docs
weight: 1110
url: /fr/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Permet de spécifier des options personnalisées pour l’édition de documents de tous les formats de feuille de calcul (Excel-compatible) pris en charge

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Permet d'exclure les feuilles de calcul masquées dans le document Spreadsheet d'entrée, afin qu'elles soient totalement ignorées. Par défaut, c'est false - les feuilles de calcul masquées sont disponibles et traitées normalement. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | Lorsqu'elle est activée, le tableau HTML dans le document HTML généré contient une ligne cachée vide en bas avec une hauteur nulle et des cellules vides, où seule la largeur est spécifiée. Cette ligne avec des cellules vides contient les valeurs exactes de largeur pour chaque colonne et améliore la conversion inverse de HTML vers Spreadsheet. Par défaut, elle est activée (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | Lorsqu'elle est activée, les cellules horizontales vides adjacentes du document Spreadsheet d'entrée seront représentées dans le document HTML éditable comme fusionnées en une seule cellule avec l'attribut `colspan` correspondant. Par défaut, elle est désactivée (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Permet de spécifier l'index basé sur zéro de la feuille de calcul (onglet) du document Spreadsheet d'entrée, qui doit être converti en HTML (voir remarques). |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

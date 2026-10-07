---
title: "MergeEmptyAdjacentCells"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Lorsqu'elle est activée, les cellules horizontales vides adjacentes du document Spreadsheet d'entrée seront représentées dans le document HTML éditable comme fusionnées en une seule cellule avec l'attribut colspan correspondant. Par défaut, elle est désactivée (false)."
type: docs
weight: 40
url: /fr/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

Lorsqu'elle est activée, les cellules horizontales vides adjacentes du document Spreadsheet d'entrée seront représentées dans le document HTML éditable comme fusionnées en une seule cellule avec l'attribut `colspan` correspondant. Par défaut, elle est désactivée (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Remarques

Par défaut, le GroupDocs.Editor convertit un tableau du document Spreadsheet d'entrée en document HTML de sortie en conservant chaque cellule. Cependant, les documents Spreadsheet peuvent être clairsemés — ils peuvent contenir une grande quantité de « zones vides », où de nombreuses cellules sont vides. Cette option, lorsqu'elle est activée, fusionne ces cellules vides en une seule avec l'attribut `colspan` dans l'élément `TD`, ce qui peut réduire considérablement la taille du balisage HTML produit.

### Voir aussi

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

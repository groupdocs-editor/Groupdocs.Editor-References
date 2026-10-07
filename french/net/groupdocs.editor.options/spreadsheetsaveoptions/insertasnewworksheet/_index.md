---
title: "InsertAsNewWorksheet"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Indicateur booléen qui spécifie si la feuille de calcul modifiée doit remplacer la feuille existante dans le classeur original à la position indiquée par la propriété WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber ou si elle doit être injectée entre la feuille existante et la précédente sans remplacer son contenu. Par défaut, la valeur est false ; la feuille existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber est définie sur 0."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Indicateur booléen qui spécifie si la feuille de calcul modifiée doit remplacer la feuille existante dans le classeur original à la position indiquée par la propriété [`WorksheetNumber`](../worksheetnumber), ou si elle doit être injectée entre la feuille existante et la précédente, sans remplacer son contenu. Par défaut, la valeur est false — la feuille existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété [`WorksheetNumber`](../worksheetnumber) est définie sur '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Remarques

Par défaut, la feuille de calcul est remplacée. Cela signifie que si le classeur fourni contient 5 feuilles de calcul et que [`WorksheetNumber`](../worksheetnumber)=4, alors la 4ᵉ feuille sera remplacée par la nouvelle feuille modifiée, tandis que le nombre total de feuilles dans le classeur (5) restera inchangé. Cependant, si la valeur de cette propriété est définie sur true, la nouvelle feuille modifiée sera injectée en tant que 4ᵉ feuille, et toutes les feuilles suivantes seront décalées vers la fin : la feuille "old" 4ᵉ devient la 5ᵉ, et la 5ᵉ devient la 6ᵉ, et le nombre total de feuilles dans le classeur sera incrémenté de un pour atteindre 6.

### Voir aussi

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

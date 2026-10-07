---
title: "WorksheetNumbersToDelete"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier un tableau contenant les numéros de feuilles de calcul (à partir de 1) qui doivent être supprimés du classeur lors de son enregistrement dans le cas où la feuille de calcul modifiée est insérée dans un classeur existant."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

Permet de spécifier un tableau contenant les numéros (basés sur 1) des feuilles qui doivent être supprimées du classeur lors de son enregistrement, dans le cas où la feuille modifiée est insérée dans un classeur existant

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### Remarques

Lorsque la feuille de calcul modifiée n'est pas enregistrée comme un nouveau classeur à feuille unique (comportement par défaut), mais est enregistrée dans un classeur existant (en utilisant la propriété [`WorksheetNumber`](../worksheetnumber)), il est également possible de supprimer certaines feuilles de calcul particulières de ce classeur en spécifiant leurs numéros dans ce tableau.

Par défaut, ce tableau est `null` — aucune feuille de calcul ne sera supprimée. Cependant, lorsque ce tableau n'est pas null et n'est pas vide, et qu'il contient au moins un numéro de feuille de calcul valide, après la génération du document classeur de sortie avec le contenu de la feuille de calcul modifiée, les feuilles de calcul dont les numéros sont spécifiés seront supprimées du classeur juste avant d'écrire son contenu dans le flux de sortie ou le fichier.

Les numéros de feuilles de calcul dans ce tableau sont indexés à partir de 1, pas de 0 ; les numéros invalides (inférieurs à 1 ou supérieurs au nombre total de feuilles de calcul) seront ignorés.

### Voir aussi

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

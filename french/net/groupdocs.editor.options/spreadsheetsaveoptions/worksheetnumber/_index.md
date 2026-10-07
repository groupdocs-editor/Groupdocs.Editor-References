---
title: "WorksheetNumber"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'insérer la feuille de calcul modifiée dans une copie d'un classeur existant au lieu de créer un nouveau classeur à feuille unique (comportement par défaut). WorksheetNumber est un numéro de feuille de calcul à partir de 1 dans le classeur chargé dans la classe Editor. Si la valeur par défaut est 0, le nouveau classeur sera créé avec une seule feuille de calcul modifiée. Si elle est supérieure ou inférieure à zéro et qu'un classeur valide est chargé dans la classe Editor, la feuille de calcul modifiée représentée par l'instance d'EditableDocument d'entrée sera insérée dans ce classeur."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Permet d'insérer la feuille de calcul modifiée dans une copie d'un classeur existant au lieu de créer un nouveau classeur à feuille unique (comportement par défaut). WorksheetNumber est un numéro basé sur 1 d'une feuille dans le classeur chargé dans la classe Editor. S'il vaut 0 (valeur par défaut), le nouveau classeur sera créé avec une seule feuille modifiée. S'il est supérieur ou inférieur à zéro, et qu'un classeur valide est chargé dans la classe Editor, la feuille modifiée, représentée par l'instance d'EditableDocument en entrée, sera insérée dans ce classeur.

```csharp
public int WorksheetNumber { get; set; }
```

### Remarques

Propriété entière WorksheetNumber, si elle n'est pas dans l'état par défaut (valeur réservée '0'), représente un numéro de feuille de calcul, donc elle commence à 1, pas à zéro, et sa valeur maximale correspond au nombre de toutes les diapositives existantes dans une présentation. Cependant, si la valeur spécifiée est supérieure au nombre total de diapositives, GroupDocs.Editor l'ajustera pour désigner la dernière feuille de calcul. Les valeurs négatives sont également autorisées et comptent les feuilles de calcul à partir de la fin. Par exemple, "-1" indique la dernière feuille de calcul d'un classeur, "-2" — l'avant‑dernière, etc. Comme pour les valeurs positives, lorsqu'un numéro de feuille de calcul négatif dépasse le nombre total de feuilles de calcul du classeur donné, il sera ajusté à la première feuille de calcul. La propriété booléenne [`InsertAsNewWorksheet`](../insertasnewworksheet) est étroitement liée à celle‑ci.

### Exemples

Le classeur fourni contient 5 feuilles de calcul : WorksheetNumber = 0 ; — ignorer le classeur fourni, créer un nouveau classeur et y placer la feuille de calcul modifiée. WorksheetNumber = 1 ; — remplacer la première feuille par la feuille modifiée WorksheetNumber = 2 ; — remplacer la deuxième feuille par la feuille modifiée WorksheetNumber = 5 ; — remplacer la dernière (5ᵉ) feuille par la feuille modifiée WorksheetNumber = 6 ; — remplacer la dernière (5ᵉ) feuille par la feuille modifiée, car 6 est supérieur à 5 et est donc ajusté WorksheetNumber = -1 ; — remplacer la dernière (5ᵉ) feuille par la feuille modifiée, car "-1" signifie "last existing" WorksheetNumber = -2 ; — remplacer la 4ᵉ feuille par la feuille modifiée WorksheetNumber = -3 ; — remplacer la 3ᵉ feuille par la feuille modifiée WorksheetNumber = -4 ; — remplacer la 2ᵉ feuille par la feuille modifiée WorksheetNumber = -5 ; — remplacer la première feuille par la feuille modifiée WorksheetNumber = -6 ; — remplacer la première feuille par la feuille modifiée, car "-6" est supérieur à 5 et est donc ajusté

### Voir aussi

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

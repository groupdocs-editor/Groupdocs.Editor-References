---
title: "SpreadsheetSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents Spreadsheet compatibles Excel"
type: docs
weight: 1130
url: /fr/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents de feuille de calcul (Excel-compliant)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Ce constructeur sans paramètres crée une nouvelle instance de SpreadsheetSaveOptions avec le format de sortie XLSX (peut ensuite être modifié via la propriété [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Crée une nouvelle instance de SpreadsheetSaveOptions avec le format de sortie Spreadsheet obligatoire spécifié, tandis que tous les autres paramètres sont par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Indicateur booléen qui spécifie si la feuille de calcul modifiée doit remplacer la feuille existante dans le classeur original à la position indiquée par la propriété [`WorksheetNumber`](./worksheetnumber), ou si elle doit être insérée entre la feuille existante et la précédente, sans remplacer son contenu. False par défaut — la feuille existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété [`WorksheetNumber`](./worksheetnumber) est définie à '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Permet de spécifier un format Spreadsheet qui sera utilisé pour enregistrer le document |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Permet de spécifier, modifier, obtenir ou supprimer un mot de passe qui sera utilisé pour chiffrer le document Spreadsheet généré, si ce format de document prend en charge la protection par mot de passe. Spécifiez NULL ou une chaîne vide pour supprimer (nettoyer) le mot de passe. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Permet d'insérer la feuille de calcul modifiée dans une copie d'un classeur existant au lieu de créer un nouveau classeur à feuille unique (comportement par défaut). WorksheetNumber est un numéro basé sur 1 d'une feuille dans le classeur chargé dans la classe Editor. S'il vaut 0 (valeur par défaut), le nouveau classeur sera créé avec une seule feuille modifiée. S'il est supérieur ou inférieur à zéro, et qu'un classeur valide est chargé dans la classe Editor, la feuille modifiée, représentée par l'instance d'EditableDocument en entrée, sera insérée dans ce classeur. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Permet de spécifier un tableau contenant les numéros (basés sur 1) des feuilles qui doivent être supprimées du classeur lors de son enregistrement, dans le cas où la feuille modifiée est insérée dans un classeur existant |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Permet d'activer la protection d'une feuille pour le document Spreadsheet de sortie. NULL par défaut – la protection n'est pas appliquée. Tous les formats ne prennent pas en charge la protection d'une feuille. |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

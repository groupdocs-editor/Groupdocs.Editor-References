---
title: "SpreadsheetLoadOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Contient des options pour charger des documents binaires Spreadsheet Cells compatibles Excel tels que XLSX, ODS, etc. dans la classe Editor"
type: docs
weight: 1120
url: /fr/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Contient des options pour charger des documents de feuille de calcul binaires (Cells, Excel-compatible) comme XLS(X), ODS etc. dans la classe Editor

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Constructeur sans paramètres par défaut - tous les paramètres ont des valeurs par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors du traitement du document d'entrée, ce qui peut dégrader les performances dans certains cas particuliers, mais réduit en revanche l'utilisation de la mémoire. Utile lors du traitement de documents volumineux et en cas d'OutOfMemoryException. La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'obtenir de meilleures performances). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir le document Spreadsheet, s'il est chiffré. Définissez-le sur NULL ou une chaîne vide afin de ne pas utiliser de mot de passe (valeur par défaut). |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: "WorksheetProtection"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule les options de protection de feuille de calcul qui permettent de protéger une feuille de calcul dans le document Spreadsheet de sortie contre toute modification d'un type spécifié avec un mot de passe spécifié."
type: docs
weight: 1250
url: /fr/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Encapsule les options de protection de la feuille de calcul, qui permettent de protéger une feuille de calcul dans le document Spreadsheet de sortie contre toute modification d'un type spécifié avec un mot de passe donné.

```csharp
public sealed class WorksheetProtection
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Crée une nouvelle instance avec les paramètres par défaut. Si elle n'est pas modifiée et transmise à SpreadsheetSaveOptions, aucune protection de feuille de calcul ne sera appliquée. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Crée une nouvelle instance avec le type de protection de feuille de calcul spécifié et le mot de passe |

## Propriétés

| Nom | Description |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Mot de passe utilisé pour protéger une feuille de calcul. Si NULL ou chaîne vide, la protection ne sera pas appliquée. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Permet de spécifier un type de protection de feuille de calcul. Par défaut, c'est 'None' - la protection n'est pas appliquée. |

### Remarques

La plupart des formats Spreadsheet comme XLSX permettent de protéger une feuille de calcul contre la modification avec un mot de passe. Cette classe permet d'activer cette protection et de spécifier ses options.

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: "DelimitedTextEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Options pour charger des documents Spreadsheet basés sur du texte, tels que CSV, à base de tabulations, etc., qui utilisent un séparateur"
type: docs
weight: 810
url: /fr/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Options pour charger des documents de feuille de calcul basés sur du texte (CSV, Tab-based etc.), qui utilisent un séparateur (delimiter)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Crée une instance de la classe d'options pour le texte délimité avec un séparateur obligatoire (délimiteur) |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Obtient ou définit une valeur indiquant si la chaîne dans le document texte est convertie en données de type date. La valeur par défaut est `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Obtient ou définit une valeur indiquant si la chaîne dans le document texte est convertie en données numériques. La valeur par défaut est `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors du traitement du document d'entrée, ce qui peut dégrader les performances dans certains cas particuliers, mais réduit en revanche l'utilisation de la mémoire. Utile lors du traitement de documents volumineux et en cas d'OutOfMemoryException. La valeur par défaut est `false` (l'optimisation de la mémoire est désactivée afin d'obtenir de meilleures performances). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents de feuille de calcul basés sur du texte |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Définit si les délimiteurs consécutifs doivent être traités comme un seul. Par défaut, la valeur est `false`. |

### Remarques

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

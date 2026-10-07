---
title: "DelimitedTextSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Contient des options pour générer et enregistrer des documents de feuille de calcul basés sur du texte CSV, à base d'onglets, etc., qui utilisent un séparateur délimiteur"
type: docs
weight: 820
url: /fr/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Contient des options pour générer et enregistrer des documents de feuille de calcul basés sur du texte (CSV, Tab-based etc.), qui utilisent un séparateur (delimiter)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Ce constructeur sans paramètres crée une nouvelle instance de DelimitedTextSaveOptions avec un séparateur par défaut point-virgule (;) (peut ensuite être modifié via la propriété [`Separator`](./separator)) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Crée une instance de la classe d'options pour le texte délimité avec un séparateur obligatoire (délimiteur) |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Permet de définir un encodage pour le document de feuille de calcul basé sur du texte. Par défaut (et si non spécifié) il est UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Indique si les séparateurs doivent être générés pour une ligne vide. La valeur par défaut est `false`, ce qui signifie que le contenu de la ligne vide sera vide. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents de feuille de calcul basés sur du texte |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Indique si les lignes et colonnes vides en début doivent être supprimées comme le fait MS Excel |

### Remarques

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

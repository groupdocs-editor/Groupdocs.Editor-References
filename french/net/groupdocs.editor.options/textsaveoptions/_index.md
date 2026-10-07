---
title: "TextSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents texte brut TXT"
type: docs
weight: 1170
url: /fr/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents texte brut (TXT)

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | Spécifie s'il faut ajouter des marques bidirectionnelles avant chaque séquence BiDi lors de l'exportation au format texte brut. La valeur par défaut est 'false' — ne pas ajouter de marques BiDi. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | Encodage des caractères du document texte, qui sera appliqué lors de son enregistrement |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | Spécifie si le programme doit tenter de préserver la mise en page des tableaux lors de l'enregistrement au format texte brut. La valeur par défaut est false. |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

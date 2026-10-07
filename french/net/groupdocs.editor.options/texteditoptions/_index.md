---
title: "TextEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour le chargement de documents texte brut TXT."
type: docs
weight: 1150
url: /fr/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

Permet de spécifier des options personnalisées pour charger des documents texte brut (TXT)

```csharp
public class TextEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextEditOptions](texteditoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | Permet de spécifier la direction du flux de texte dans le document texte brut d'entrée. Par défaut, il est de gauche à droite. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | Permet d'activer ou de désactiver la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | Encodage des caractères du document texte, qui sera appliqué lors de son ouverture. |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | Obtient ou définit l'option préférée de gestion des espaces de début. Par défaut, les espaces de début sont convertis en retrait à gauche. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est importé depuis un format texte brut. La valeur par défaut est vraie. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | Obtient ou définit l'option préférée de gestion des espaces de fin. Par défaut, tous les espaces de fin sont tronqués. |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

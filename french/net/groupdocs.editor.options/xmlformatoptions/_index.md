---
title: "XmlFormatOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Contient des options qui permettent d'ajuster le formatage du document XML lorsqu'il est représenté en HTML"
type: docs
weight: 1280
url: /fr/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Contient des options qui permettent d'ajuster le formatage du document XML lorsqu'il est représenté en HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | Lorsqu'elle est activée, chaque paire attribut-valeur dans chaque élément XML sera placée sur une nouvelle ligne. Par défaut, elle est désactivée (false) — toutes les paires attribut-valeur sont placées sur une seule ligne. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Indique si cette instance d'options de formatage XML possède une valeur par défaut |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | Lorsqu'elle est activée, les nœuds texte feuilles (contenu textuel à l'intérieur des éléments XML, qui n'ont pas d'enfants) seront rendus sur une nouvelle ligne avec une indentation gauche plus grande. Par défaut, elle est désactivée (false) — les nœuds texte feuilles sont placés sur la même ligne que leurs parents, sans nouvelle indentation. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Permet de spécifier un décalage pour l'indentation gauche de chaque nouvelle ligne. Ne peut pas être une valeur non nulle sans unité. Par défaut, il est de 10pt |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

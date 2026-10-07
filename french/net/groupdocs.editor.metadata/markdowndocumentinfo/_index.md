---
title: "MarkdownDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les métadonnées d'un document Markdown"
type: docs
weight: 750
url: /fr/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Représente les métadonnées d'un document Markdown

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Renvoie un format de ce document Markdown — toujours [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Comme les documents Markdown ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Renvoie le nombre de pages. Les documents Markdown n'ont généralement pas de pages fixes et donc de nombre de pages, ainsi ce nombre est calculé à partir de la taille de page standard définie sur A4 en orientation portrait. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Renvoie la taille en octets de ce document Markdown |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Détermine si cette instance est égale à l'autre instance spécifiée de [`MarkdownDocumentInfo`](../markdowndocumentinfo). |

### Voir aussi

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

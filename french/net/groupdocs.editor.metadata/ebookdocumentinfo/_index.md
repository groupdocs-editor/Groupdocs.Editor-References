---
title: "EbookDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les métadonnées d'un document eBook"
type: docs
weight: 710
url: /fr/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Représente les métadonnées d'un document e-Book

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Renvoie le format de cet e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Comme les documents e-Book ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Renvoie le nombre de pages dans le cas d'un MOBI ou d'un AZW3 ou le nombre de chapitres dans le cas d'un ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Renvoie la taille en octets de ce document eBook. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Détermine si cette instance est égale à l'autre instance spécifiée d'EbookDocumentInfo. |

### Voir aussi

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: EbookDocumentInfo
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente les métadonnées dun document eBook
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

| Nom | La description |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Renvoie un format de cet e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Étant donné que les documents e-Book ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Renvoie le nombre de pages en cas de MOBI ou AZW3 ou le nombre de chapitres en cas d'ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Renvoie la taille en octets de ce document eBook |

## Méthodes

| Nom | La description |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Détermine si cette instance est égale à l'autre instance EbookDocumentInfo spécifiée |

### Voir également

* interface [IDocumentInfo](../idocumentinfo)
* espace de noms [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

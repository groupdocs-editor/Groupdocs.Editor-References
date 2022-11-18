---
title: PageCount
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Renvoie le nombre de pages en cas de MOBI ou AZW3 ou le nombre de chapitres en cas dePub.
type: docs
weight: 30
url: /fr/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Renvoie le nombre de pages en cas de MOBI ou AZW3 ou le nombre de chapitres en cas d'ePub.

```csharp
public int PageCount { get; }
```

### Remarques

Les documents e-Book n'ont généralement pas de pages fixes et donc de nombre de pages. Dans le cas d'ePub, il est possible de calculer un certain nombre de chapitres. Cependant, les formats MOBI et AZW3 n'ont pas non plus de chapitres, donc ce nombre est calculé à partir de la taille de page standard définie sur A4 en orientation portrait.

### Voir également

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* espace de noms [GroupDocs.Editor.Metadata](../../ebookdocumentinfo)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
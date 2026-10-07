---
title: "PageCount"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie le nombre de pages dans le cas d'un MOBI ou d'un AZW3 ou le nombre de chapitres dans le cas d'un ePub."
type: docs
weight: 30
url: /fr/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Renvoie le nombre de pages dans le cas d'un MOBI ou d'un AZW3 ou le nombre de chapitres dans le cas d'un ePub.

```csharp
public int PageCount { get; }
```

### Remarques

Les documents e‑Book n'ont généralement pas de pages fixes et donc pas de nombre de pages. Dans le cas d'ePub, il est possible de calculer un nombre de chapitres. Cependant, les formats MOBI et AZW3 n'ont pas non plus de chapitres, ainsi ce nombre est calculé à partir d'une taille de page standard définie à A4 en orientation portrait.

### Voir aussi

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

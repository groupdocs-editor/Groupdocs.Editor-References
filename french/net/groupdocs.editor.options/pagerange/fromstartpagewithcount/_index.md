---
title: "FromStartPageWithCount"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une plage de pages qui commence au numéro de page spécifié et possède le nombre de pages indiqué ou un nombre de pages illimité jusqu'à la fin"
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Crée une plage de pages qui commence au numéro de page spécifié et possède le nombre de pages indiqué, ou un nombre illimité de pages (jusqu'à la fin)

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| startPageNumber | UInt16 | Numéro de page à partir duquel la plage de pages commence, de manière inclusive. Les numéros de page sont indexés à partir de 1, ils doivent donc être strictement supérieurs à zéro |
| pageCount | UInt16 | Nombre de pages, doit être strictement supérieur à zéro. Si zéro - cela signifie toutes les pages jusqu'à la fin d'un document |

### Valeur de retour

Nouvelle instance PageRange

### Voir aussi

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

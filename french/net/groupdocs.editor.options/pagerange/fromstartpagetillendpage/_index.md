---
title: "FromStartPageTillEndPage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une plage de pages qui commence au numéro de page spécifié de manière inclusive et continue jusqu'au numéro de page spécifié de manière exclusive"
type: docs
weight: 40
url: /fr/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Crée une plage de pages qui commence au numéro de page spécifié (inclusivement) et se poursuit jusqu'au numéro de page spécifié (exclusivement)

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| startPageNumber | UInt16 | Numéro de page à partir duquel la plage de pages commence, de manière inclusive. Les numéros de page sont indexés à partir de 1, ils doivent donc être strictement supérieurs à zéro |
| endPageNumber | UInt16 | Numéro de page jusqu'auquel la plage de pages continue, de manière exclusive. Les numéros de page sont indexés à partir de 1, ils doivent donc être strictement supérieurs à zéro, et également strictement supérieurs à *startPageNumber* |

### Voir aussi

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

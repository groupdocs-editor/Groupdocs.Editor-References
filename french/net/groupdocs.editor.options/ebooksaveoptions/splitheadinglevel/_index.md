---
title: "SplitHeadingLevel"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Spécifie le niveau maximal de titres auquel diviser le fichier eBook. La valeur par défaut est 2. Le régler à 0 désactivera la division de sorte que tout le contenu de l'eBook sera incorporé dans un seul paquet à l'intérieur du fichier résultant."
type: docs
weight: 40
url: /fr/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. La valeur par défaut est `2`. Le définir à `0` désactivera la division, de sorte que tout le contenu de l'e-Book sera incorporé dans un seul paquet à l'intérieur du fichier résultant.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Remarques

Lorsque cette propriété est définie sur une valeur de 1 à 9, le document sera divisé aux paragraphes formatés avec les styles **Heading 1**, **Heading 2**, **Heading 3**, etc. jusqu'au niveau de titre spécifié.

Par défaut, seuls les paragraphes **Heading 1** et **Heading 2** provoquent la division du document. Régler cette propriété à zéro (ou à une valeur inférieure) empêchera toute division du document aux paragraphes de titre.

### Voir aussi

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

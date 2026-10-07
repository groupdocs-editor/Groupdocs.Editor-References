---
title: "GeneratePreview"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Génère et renvoie un aperçu de la feuille de calcul sélectionnée sous forme d'image SVG"
type: docs
weight: 60
url: /fr/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Génère et renvoie un aperçu de la feuille de calcul sélectionnée sous forme d'image SVG

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | Int32 | Index basé sur 0 de la feuille de calcul souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de feuilles de calcul dans ce classeur. |

### Valeur de retour

Image SVG en tant qu'instance non nulle de la classe [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | L' *worksheetIndex* spécifié est inférieur à 0 ou supérieur au nombre de feuilles de calcul dans ce classeur |

### Voir aussi

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

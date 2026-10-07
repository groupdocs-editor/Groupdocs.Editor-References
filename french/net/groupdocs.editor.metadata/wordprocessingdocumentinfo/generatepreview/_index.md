---
title: "GeneratePreview"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Génère et renvoie un aperçu de la page sélectionnée sous forme d'image SVG"
type: docs
weight: 60
url: /fr/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Génère et renvoie un aperçu de la page sélectionnée sous forme d'image SVG

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageIndex | Int32 | Index basé sur 0 de la page souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de pages dans ce document WordProcessing. |

### Valeur de retour

Image SVG en tant qu'instance non nulle de la classe [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | L' *pageIndex* spécifié est inférieur à 0 ou supérieur au nombre de pages dans ce document WordProcessing |

### Voir aussi

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: "GeneratePreview"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Génère et renvoie un aperçu de la diapositive sélectionnée sous forme d'image SVG"
type: docs
weight: 50
url: /fr/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Génère et renvoie un aperçu de la diapositive sélectionnée sous forme d'image SVG

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| slideIndex | Int32 | Index basé sur 0 de la diapositive souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de diapositives dans cette présentation. |

### Valeur de retour

Image SVG en tant qu'instance non nulle de la classe [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | L' *slideIndex* spécifié est inférieur à 0 ou supérieur au nombre de diapositives dans cette présentation |

### Voir aussi

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

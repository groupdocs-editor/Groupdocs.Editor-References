---
title: "IImageResource"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une ressource d'image de tout type, raster ou vectoriel"
type: docs
weight: 470
url: /fr/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Représente une ressource d’image de tout type, raster ou vectoriel.

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | Dans le type d'implémentation, il doit renvoyer le rapport d'aspect d'une image particulière quel que soit son type. Les images vectorielles et raster ont un rapport d'aspect intrinsèque entre leur largeur et leur hauteur. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | Dans le type d'implémentation, il doit renvoyer les dimensions linéaires de l'image. Pour les images raster, il s'agit des dimensions intrinsèques en pixels. Les images vectorielles, en revanche, n'ont pas de dimensions fixes, mais leurs métadonnées peuvent contenir certaines dimensions de base dans différentes unités de mesure. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | Dans le type d'implémentation, il doit renvoyer le type d'une image spécifique sous forme d'instance d'ImageType spécifique, qui encapsule toutes les informations propres au type |

### Remarques

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### Voir aussi

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

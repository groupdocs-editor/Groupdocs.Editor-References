---
title: "RasterImageResourceBase"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Classe de base pour toute image raster prise en charge avec nom, dimensions, ratio d’aspect, type, taille et contenu fixes."
type: docs
weight: 540
url: /fr/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Classe de base pour toute image raster prise en charge avec un nom fixe, des dimensions, un rapport d’aspect, un type, une taille et un contenu.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image sous forme de relation largeur/hauteur |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Renvoie le contenu de cette image raster sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image raster, qui se compose du nom et de l'extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est libérée ou non |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Renvoie la taille de ce fichier d'image raster en octets |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image raster (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Renvoie le nom de cette image raster. Habituellement, il ne contient pas l'extension du nom de fichier et peut théoriquement différer du nom de fichier. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Renvoie le contenu de cette image raster sous forme de chaîne encodée en base64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Dans l’implémentation, le type doit renvoyer des informations sur le type de l’image raster |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Disposes this raster image, disposing its content and making most methods and properties non-working |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée en fonction de l'égalité de référence. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Enregistre cette image raster dans le fichier spécifié |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Événement qui se produit lorsque cette image raster est libérée |

### Voir aussi

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

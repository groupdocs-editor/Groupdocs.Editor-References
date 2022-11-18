---
title: RasterImageResourceBase
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Classe de base pour toute image raster prise en charge avec un nom des dimensions des proportions un type une taille et un contenu fixes.
type: docs
weight: 450
url: /fr/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Classe de base pour toute image raster prise en charge avec un nom, des dimensions, des proportions, un type, une taille et un contenu fixes.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Renvoie un rapport d'aspect de cette image en tant que relation largeur-hauteur |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Renvoie le contenu de cette image raster sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image raster, qui se compose du nom et de l'extension. Théoriquement peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est supprimée ou non |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Renvoie la longueur de ce fichier image raster en octets |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image raster (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Renvoie le nom de cette image raster. Ne contient généralement pas d'extension de nom de fichier et peut théoriquement différer de filename. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Renvoie le contenu de cette image raster sous forme de chaîne encodée en base64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Lors de l'implémentation, le type doit renvoyer des informations sur le type de l'image raster |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Dispose cette image raster, supprimant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Vérifie cette instance avec l'égalité de référence spécifiée. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Génère et renvoie une nouvelle instance de 'System.Drawing.Bitmap' à partir de cette image raster. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Crée et renvoie une nouvelle ressource d'image réduite du même type, mais avec une nouvelle hauteur réduite spécifiée et une largeur proportionnellement réduite. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Enregistre cette image raster dans le fichier spécifié |

## Événements

| Nom | La description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Evénement, qui se produit lorsque cette image raster est éliminée |

### Voir également

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* espace de noms [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
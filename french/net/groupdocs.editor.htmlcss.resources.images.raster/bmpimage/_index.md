---
title: "BmpImage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une image au format BMP BitMap Picture avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 490
url: /fr/net/groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
## BmpImage class

Représente une image au format BMP (BitMap Picture) avec ses métadonnées et ses méthodes supplémentaires.

```csharp
public sealed class BmpImage : RasterImageResourceBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BmpImage](bmpimage#constructor)(string, Stream) | Crée une nouvelle instance de BmpImage à partir du contenu, représenté sous forme de flux d’octets, et avec le nom spécifié |
| [BmpImage](bmpimage#constructor_1)(string, string) | Crée une nouvelle instance de BmpImage à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/type) { get; } | Renvoie ImageType.Bmp |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Disposes this raster image, disposing its content and making most methods and properties non-working |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée en fonction de l'égalité de référence. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Enregistre cette image raster dans le fichier spécifié |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid)(Stream) | Vérifie si le flux spécifié est une image BMP valide |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid_1)(string) | Vérifie si la chaîne encodée en base64 spécifiée est une image BMP valide |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Événement qui se produit lorsque cette image raster est libérée |

### Voir aussi

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

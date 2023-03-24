---
title: EmfImage
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente une image vectorielle au format Enhanced Metafile Format EMF avec ses métadonnées et des méthodes supplémentaires
type: docs
weight: 570
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Représente une image vectorielle au format Enhanced Metafile Format (EMF) avec ses métadonnées et des méthodes supplémentaires

```csharp
public sealed class EmfImage : MetaImageBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Crée une nouvelle instance EmfImage à partir du contenu, représenté sous forme de flux d'octets et avec le nom spécifié |
| [EmfImage](emfimage#constructor_1)(string, string) | Crée une nouvelle instance EmfImage à partir du contenu, représentée sous forme de chaîne encodée en base64 et avec le nom spécifié |

## Propriétés

| Nom | La description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image vectorielle |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Renvoie un contenu de cette image EMF sous forme de flux binaire |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image vectorielle, qui se compose du nom et de l'extension. Théoriquement peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est supprimée (`vrai`) ou non (`FAUX` ) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Renvoie le nom de cette image vectorielle. Ne contient généralement pas d'extension de nom de fichier et peut théoriquement différer de filename. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Renvoie un contenu de cette image EMF sous forme de texte brut |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | Renvoie ImageType.Emf |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Supprime cette image EMF en supprimant son contenu et en rendant la plupart de ses méthodes et propriétés non fonctionnelles. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec l'égalité de référence spécifiée. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Enregistre cette image EMF dans le fichier |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Enregistre cette image vectorielle EMF dans une image PNG raster |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Enregistre cette image vectorielle EMF dans une image vectorielle SVG |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Vérifie si le flux spécifié est une image EMF valide |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Vérifie si la chaîne encodée en base64 spécifiée est une image EMF valide |

## Événements

| Nom | La description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Evénement, qui se produit lorsque cette image raster est éliminée |

### Voir également

* class [MetaImageBase](../metaimagebase)
* espace de noms [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
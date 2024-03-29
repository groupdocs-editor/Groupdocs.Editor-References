---
title: SvgImage
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente une image vectorielle au format SVG Scalable Vector Graphics avec ses métadonnées et des méthodes supplémentaires
type: docs
weight: 590
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Représente une image vectorielle au format SVG (Scalable Vector Graphics) avec ses métadonnées et des méthodes supplémentaires

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Crée une nouvelle instance SvgImage à partir du contenu, représenté sous forme de flux d'octets et avec le nom spécifié |
| [SvgImage](svgimage#constructor_1)(string, string) | Crée une nouvelle instance SvgImage à partir du contenu, représenté comme une chaîne habituelle et avec le nom spécifié |

## Propriétés

| Nom | La description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image vectorielle |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Renvoie un contenu de cette image SVG sous forme de flux binaire |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image vectorielle, qui se compose du nom et de l'extension. Théoriquement peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est supprimée (`vrai`) ou non (`FAUX` ) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Renvoie le nom de cette image vectorielle. Ne contient généralement pas d'extension de nom de fichier et peut théoriquement différer de filename. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Renvoie un contenu de cette image SVG sous forme de contenu binaire encodé en base64 (et non sous forme de texte brut au format XML) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Renvoie ImageType.Svg |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Renvoie un contenu de cette image SVG dans sa forme textuelle d'origine compatible XML |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Dispose cette image raster, supprimant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec l'égalité de référence spécifiée. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Enregistre cette image SVG dans le fichier |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Enregistre cette image SVG vectorielle dans une image PNG raster |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Effectue une vérification de surface si le contenu textuel conforme XML représente une image SVG |

## Événements

| Nom | La description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Evénement, qui se produit lorsque cette image raster est éliminée |

### Voir également

* class [VectorImageResourceBase](../vectorimageresourcebase)
* espace de noms [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

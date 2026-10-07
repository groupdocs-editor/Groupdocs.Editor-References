---
title: "SvgImage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Represents one vector image in SVG Scalable Vector Graphics format with its metadata dimensions and additional methods saving to PNG"
type: docs
weight: 580
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Représente une image vectorielle au format SVG (Scalable Vector Graphics) avec ses métadonnées (dimensions) et méthodes supplémentaires (enregistrement en PNG)

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Creates new SvgImage instance from content, represented as byte stream, and with specified name |
| [SvgImage](svgimage#constructor_1)(string, string) | Creates new SvgImage instance from content, represented as usual string, and with specified name |

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image vectorielle |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Returns a content of this SVG image as a binary stream with original position |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image vectorielle, qui comprend le nom et l'extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est libérée (`true`) ou non (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Renvoie le nom de cette image vectorielle. Habituellement, il ne contient pas l'extension du fichier et peut théoriquement différer du nom de fichier. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Returns a content of this SVG image as a base64-encoded binary content (not as a raw text in XML format) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Returns [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Returns a content of this SVG image in its original XML-compliant textual form |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Disposes this raster image, disposing its content and making most methods and properties non-working |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée en fonction de l'égalité de référence. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Saves this SVG image to the file |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Saves this vector SVG image into raster PNG image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Performs a surface check whether specified textual XML-compliant content represents a SVG image |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Événement qui se produit lorsque cette image raster est libérée |

### Voir aussi

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

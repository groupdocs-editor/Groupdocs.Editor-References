---
title: "EmfImage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une image vectorielle au format EMF (Enhanced Metafile) avec ses métadonnées et méthodes supplémentaires"
type: docs
weight: 560
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Représente une image vectorielle au format Enhanced Metafile (EMF) avec ses métadonnées et méthodes supplémentaires

```csharp
public sealed class EmfImage : MetaImageBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Crée une nouvelle instance d'EmfImage à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié |
| [EmfImage](emfimage#constructor_1)(string, string) | Crée une nouvelle instance d'EmfImage à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image vectorielle |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Renvoie le contenu de cette image EMF sous forme de flux binaire |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image vectorielle, qui comprend le nom et l'extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est libérée (`true`) ou non (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Renvoie le nom de cette image vectorielle. Habituellement, il ne contient pas l'extension du fichier et peut théoriquement différer du nom de fichier. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Renvoie le contenu de cette image EMF sous forme de texte brut |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | Renvoie ImageType.Emf |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Libère cette image EMF en libérant son contenu et en rendant la plupart de ses méthodes et propriétés inopérantes. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée en fonction de l'égalité de référence. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Enregistre cette image EMF dans le fichier |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Enregistre cette image EMF vectorielle en image PNG raster |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Saves this vector EMF image into vector SVG image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Checks whether specified stream is a valid EMF image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Checks whether specified base64-encoded string is a valid EMF image |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Événement qui se produit lorsque cette image raster est libérée |

### Voir aussi

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

---
title: "MetaImageBase"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Classe abstraite de base pour les formats d'image WMF et EMF"
type: docs
weight: 570
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

Classe abstraite de base pour les formats d'image WMF et EMF

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Renvoie le rapport d'aspect de cette image vectorielle |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette image vectorielle, qui comprend le nom et l'extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Détermine si cette image raster est libérée (`true`) ou non (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Renvoie les dimensions linéaires de cette image vectorielle (largeur et hauteur) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Renvoie le nom de cette image vectorielle. Habituellement, il ne contient pas l'extension du fichier et peut théoriquement différer du nom de fichier. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | Dans l'implémentation, le type doit renvoyer le contenu de cette image vectorielle sous forme texte : encodage base64 du XML correspondant au type d'image |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | Dans l'implémentation, le type doit renvoyer des informations sur le type de l'image vectorielle |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | Dans l'implémentation, le type doit libérer cette instance |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée en fonction de l'égalité de référence. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | Dans l'implémentation, le type doit enregistrer cette image sur le disque à l'emplacement spécifié |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | Dans l'implémentation, le type doit enregistrer l'image vectorielle actuelle au format PNG raster dans le flux d'octets spécifié |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | Lors de l'implémentation du type WMF ou EMF, il faut enregistrer l'image méta vectorielle actuelle au format SVG vectoriel dans le flux d'octets spécifié |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Événement qui se produit lorsque cette image raster est libérée |

### Remarques

Cette classe abstraite est héritée par [`WmfImage`](../wmfimage) et [`EmfImage`](../emfimage)

### Voir aussi

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

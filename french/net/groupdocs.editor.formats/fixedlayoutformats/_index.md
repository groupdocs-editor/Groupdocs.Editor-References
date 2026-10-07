---
title: "FixedLayoutFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les formats de documents fixedlayout fixedpage tels que PDF, à l'exclusion des formats d'images raster."
type: docs
weight: 100
url: /fr/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

Représente les formats de documents à mise en page fixe (page fixe), tels que PDF, à l'exclusion des formats d'images raster.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Obtient toutes les instances disponibles de [`FixedLayoutFormats`](../fixedlayoutformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Récupère une instance de [`FixedLayoutFormats`](../fixedlayoutformats) correspondant à l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Convertit explicitement une chaîne d'extension de fichier en une instance de [`FixedLayoutFormats`](../fixedlayoutformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Le Portable Document Format (PDF), introduit par Adobe, fournit une représentation normalisée des documents indépendante du logiciel, du matériel et des systèmes d'exploitation. Pour plus de détails, voir : [format de fichier PDF](https://docs.fileformat.com/pdf/). |

### Remarques

Les formats à mise en page fixe spécifient précisément le placement et le rendu du contenu sur chaque page. Ils sont couramment utilisés dans les applications de visualisation, de publication ou d'édition de documents telles qu'Adobe Acrobat et Adobe InDesign. Ces formats définissent en interne les mises en page et le positionnement du contenu à l'aide de graphiques vectoriels et d'instructions textuelles.

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

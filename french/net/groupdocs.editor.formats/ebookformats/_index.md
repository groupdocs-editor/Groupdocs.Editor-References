---
title: "EBookFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule tous les formats eBook. Inclut les types de fichiers suivants Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /fr/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Encapsule tous les formats eBook. Inclut les types de fichiers suivants : [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Obtient une collection énumérable de tous les [`EBookFormats`](../ebookformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Récupère une instance du type spécifié [`EBookFormats`](../ebookformats) qui possède l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en un objet [`EBookFormats`](../ebookformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique AZW développé pour les appareils Amazon Kindle. Ce format constitue une amélioration des anciens fichiers AZW. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Le format Electronic Publication (IDPF ePub) est un format de fichier e‑book qui offre un format de publication numérique standard pour les éditeurs et les consommateurs. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI est le nom attribué au format développé pour le lecteur MobiPocket. Aussi appelé PRC, AZW. Il est actuellement utilisé par Amazon avec un schéma DRM légèrement différent et appelé AZW. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/ebook/mobi/). |

### Remarques

En savoir plus sur le format Mobi [ici](https://docs.fileformat.com/ebook/mobi/), sur le format AZW3 [ici](https://docs.fileformat.com/ebook/azw3/), et sur le format ePub [ici](https://docs.fileformat.com/ebook/epub/).

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

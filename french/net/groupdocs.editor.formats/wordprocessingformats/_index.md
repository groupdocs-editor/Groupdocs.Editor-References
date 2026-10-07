---
title: "WordProcessingFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Regroupe tous les formats WordProcessing. Inclut les types de fichiers suivants"
type: docs
weight: 150
url: /fr/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Regroupe tous les formats de traitement de texte. Inclut les types de fichiers suivants :

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

En savoir plus sur les formats de traitement de texte [ici](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Obtient une collection énumérable de tous les [`WordProcessingFormats`](../wordprocessingformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Récupère une instance du type spécifié [`WordProcessingFormats`](../wordprocessingformats) qui possède l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en un objet [`WordProcessingFormats`](../wordprocessingformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Le format de fichier binaire MS Word 97-2007 (DOC) représente les documents générés par Microsoft Word ou d'autres traitements de texte au format binaire. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Les fichiers Office Open XML WordProcessingML Macro-Enabled Document (DOCM) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d’exécuter des macros. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) est un format bien connu pour les documents Microsoft Word. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Les modèles MS Word 97-2007 (DOT) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) représente des fichiers modèle créés avec Microsoft Word 2007 ou version ultérieure. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOCX. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d’un package ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Les fichiers Open Document Format Text Document (ODT) sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Les modèles Open Document Format Text Document (OTT) représentent des documents modèle générés par des applications conformes au format standard OpenDocument de l’OASIS. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) représente une méthode d’encodage de texte formaté et de graphiques pour une utilisation dans les applications. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML ou WordML (.XML). |

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

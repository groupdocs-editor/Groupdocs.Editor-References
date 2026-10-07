---
title: "FormatFamilies"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les différentes familles de formats disponibles dans le système."
type: docs
weight: 110
url: /fr/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Représente les différentes familles de formats disponibles dans le système.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | Représente la famille de formats eBook. En savoir plus sur le format Mobi [ici](https://docs.fileformat.com/ebook/mobi/), sur le format AZW3 [ici](https://docs.fileformat.com/ebook/azw3/), et sur le format ePub [ici](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Représente la famille de formats Email. En savoir plus sur le format des e‑mails [ici](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Représente la famille de formats à mise en page fixe. Diverses applications de visualisation ou de publication de documents permettent aux utilisateurs d'ouvrir (Adobe Acrobat, XPS Viewer), et parfois de modifier (Adobe InDesign) des documents de formats spécifiques. Ces applications produisent généralement ce que l’on appelle des documents au format « page fixe ». Un tel format de document décrit précisément où le contenu du document est placé sur chaque page. En interne, le format PDF ou XPS contient une description de chaque page, ainsi que des instructions de dessin, spécifiant la disposition du contenu sur la page. Cela ressemble aux formats d'image, décrivant où le contenu est affiché sous forme raster ou vectorielle. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Représente la famille de formats de présentation. En savoir plus sur les formats de présentation [ici](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Représente la famille de formats de feuilles de calcul. Tous les formats de feuilles de calcul binaires, XML et textuels (excluant tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, délimité par point‑virgule, etc.) dans lesquels le classeur peut être enregistré. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Représente la famille de formats textuels. Regroupe tous les formats textuels (basés sur du texte), y compris le balisage (XML, HTML) et d’autres. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Représente la famille de formats de traitement de texte. En savoir plus sur les formats de traitement de texte [ici](https://wiki.fileformat.com/word-processing). |

### Voir aussi

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

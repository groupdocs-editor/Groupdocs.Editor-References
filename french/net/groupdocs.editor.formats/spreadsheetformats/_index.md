---
title: "SpreadsheetFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Regroupe tous les formats de feuilles de calcul binaires, XML et textuels, à l’exclusion de tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, délimité par point‑virgule, etc., dans lesquels le classeur peut être enregistré. Inclut les formats suivants Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. En savoir plus sur les formats de feuilles de calcul icihttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /fr/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Regroupe tous les formats de feuilles de calcul binaires, XML et textuels (excluant tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, délimité par point‑virgule, etc.), dans lesquels le classeur peut être enregistré. Inclut les formats suivants : [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). En savoir plus sur les formats de feuilles de calcul [ici](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Obtient une collection énumérable de tous les [`SpreadsheetFormats`](../spreadsheetformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Récupère une instance du type spécifié [`SpreadsheetFormats`](../spreadsheetformats) qui possède l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en un objet [`SpreadsheetFormats`](../spreadsheetformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Valeurs séparées par des virgules (CSV). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Format d'échange de données (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Feuille de calcul OpenDocument plate (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Feuille de calcul OpenDocument (ODS). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Format XML de Microsoft Office Excel 2002 et Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | Feuille de calcul XML StarOffice ou OpenOffice.org Calc (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Valeurs séparées par des tabulations (TSV). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Module complémentaire Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Format de fichier binaire Excel 97-2003 (XLS). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Classeur binaire Excel (XLSB). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Classeur Office Open XML avec macros (XLSM). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Classeur Office Open XML sans macros (XLSX). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Modèle Excel 97-2003 (XLT). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Modèle Office Open XML avec macros (XLTM). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Modèle Office Open XML sans macros (XLTX). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/spreadsheet/xltx). |

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->

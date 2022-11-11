---
title: SpreadsheetFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats de feuilles de calcul binaires XML et textuels à lexclusion de tous les formats basés sur des délimiteurs textuels avec séparateur comme CSV TSV délimité par des pointsvirgules etc. dans lesquels le classeur peut être enregistré. Inclut les formats suivants  Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . En savoir plus sur les formats de feuille de calculicihttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /fr/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Encapsule tous les formats de feuilles de calcul binaires, XML et textuels (à l'exclusion de tous les formats basés sur des délimiteurs textuels avec séparateur comme CSV, TSV, délimité par des points-virgules, etc.), dans lesquels le classeur peut être enregistré. Inclut les formats suivants : [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . En savoir plus sur les formats de feuille de calcul[ici](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Renvoie une extension (sans point de début) de ce format de feuille de calcul en minuscules |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Renvoie un code MIME pour ce format |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Renvoie un nom complet formel de ce format de feuille de calcul |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Renvoie une instance de[`SpreadsheetFormats`](../spreadsheetformats)structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, qui est vraisemblablement de SpreadsheetFormats en boîte |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Détermine si cette instance est égale à l'autre instance SpreadsheetFormats spécifiée |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Vérifie deux instances SpreadsheetFormats données sur l'égalité |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Vérifie deux instances SpreadsheetFormats données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Les documents CSV (Comma Separated Values) représentent du texte brut contenant des enregistrements de données avec des valeurs séparées par des virgules. Chaque ligne d'un fichier CSV est un nouvel enregistrement de l'ensemble d'enregistrements contenus dans le fichier. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Format d'échange de données (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — stocké sous la forme d'un seul document XML non compressé |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) représente le format de document OpenDocument Spreadsheet modifiable par l'utilisateur. Les données sont stockées dans le fichier ODF en lignes et en colonnes. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Format XML Microsoft Office Excel 2002 et Excel 2003 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | Feuille de calcul XML StarOffice ou OpenOffice.org Calc (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Le format de fichier de valeurs séparées par des tabulations (TSV) représente les données séparées par des tabulations au format texte brut. Le format de fichier, similaire à CSV, est utilisé pour l'organisation des données de manière structurée afin d'importer et d'exporter entre différentes applications. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Complément Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Le format de fichier binaire (XLS) représente des fichiers qui peuvent être créés par Microsoft Excel ainsi que d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB) spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) est un type de fichier de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) représente les documents introduits par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Modèle Excel 97-2003 (XLT) représente les fichiers modèles créés avec Microsoft Excel qui est une application de feuille de calcul qui fait partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) représente les fichiers générés par Microsoft Excel en tant que fichiers modèles prenant en charge les macros. Les fichiers XLTM sont similaires à XLTX dans leur structure, sauf que ce dernier ne prend pas en charge la création de fichiers modèles avec des macros. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Le fichier Office Open XML Template Macro-Free (XLTX) représente le modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier de modèle standard qui peut être utilisé pour générer des fichiers XLSX qui présentent les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Renvoie une classe interne, qui fournit des possibilités énumérables sur tous les formats de feuille de calcul existants |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type SpreadsheetFormats |

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

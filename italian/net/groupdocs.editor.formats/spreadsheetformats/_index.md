---
title: "SpreadsheetFormats"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Incapsula tutti i formati Spreadsheet binari, XML e testuali, escludendo tutti i formati testuali basati su delimitatori con separatori come CSV, TSV, delimitati da punto e virgola, ecc., in cui è possibile salvare la cartella di lavoro. Include i seguenti formati Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Scopri di più sui formati Spreadsheet herehttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /it/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Incapsula tutti i formati Spreadsheet binari, XML e testuali (escludendo tutti i formati testuali basati su delimitatori con separatori come CSV, TSV, delimitati da punto e virgola, ecc.), in cui è possibile salvare la cartella di lavoro. Include i seguenti formati: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Scopri di più sui formati Spreadsheet [qui](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ottiene l'estensione del file del formato di documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ottiene la famiglia di formato a cui appartiene il formato di documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ottiene l'identificatore univoco per la famiglia di formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ottiene il tipo MIME del formato di documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ottiene il nome della famiglia di formato. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Ottiene una collezione enumerabile di tutti i [`SpreadsheetFormats`](../spreadsheetformats). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Recupera un'istanza del tipo specificato [`SpreadsheetFormats`](../spreadsheetformats) che ha l'estensione di file specificata. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina se questa istanza è uguale all'istanza specificata [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina se questa istanza è uguale all'istanza specificata [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina se questa istanza è uguale all'istanza specificata [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Restituisce un codice hash per l'oggetto corrente. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Converte una stringa che rappresenta un'estensione di file in un oggetto [`SpreadsheetFormats`](../spreadsheetformats). |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Valori separati da virgola (CSV). Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Formato di scambio dati (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Foglio di calcolo OpenDocument flat (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Foglio di calcolo OpenDocument (ODS). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Formato XML di Microsoft Office Excel 2002 e Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | Foglio di calcolo XML StarOffice o OpenOffice.org Calc (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Valori separati da tabulazione (TSV). Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Componenti aggiuntivi di Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Formato binario di Excel 97-2003 (XLS). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Cartella di lavoro binaria di Excel (XLSB). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Cartella di lavoro Office Open XML con macro (XLSM). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Cartella di lavoro Office Open XML senza macro (XLSX). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Modello Excel 97-2003 (XLT). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Modello Office Open XML con macro (XLTM). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Modello Office Open XML senza macro (XLTX). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/spreadsheet/xltx). |

### Vedi anche

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

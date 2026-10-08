---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Omvat alle binaire XML‑ en tekstuele spreadsheetformaten, exclusief alle tekstuele, op scheidingstekens gebaseerde formaten met scheidingsteken zoals CSV, TSV, puntkomma‑gescheiden enz., waarin de werkmap kan worden opgeslagen. Bevat de volgende formaten Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Meer informatie over spreadsheetformaten hierhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /nl/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Omvat alle binaire, XML‑ en tekstuele spreadsheetformaten (exclusief alle tekstuele, op scheidingstekens gebaseerde formaten met scheidingsteken zoals CSV, TSV, puntkomma‑gescheiden enz.), waarin de werkmap kan worden opgeslagen. Bevat de volgende formaten: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Meer informatie over spreadsheetformaten [hier](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Haalt de bestandsextensie van het documentformaat op. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Haalt de formatfamilie op waartoe het documentformaat behoort. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Haalt de unieke identifier op voor de formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Haalt het MIME-type van het documentformaat op. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Haalt de naam van de formatfamilie op. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Haalt een doorzoekbare collectie op van alle [`SpreadsheetFormats`](../spreadsheetformats). |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Haalt een instantie op van het opgegeven type [`SpreadsheetFormats`](../spreadsheetformats) dat de opgegeven bestandsextensie heeft. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bepaalt of deze instantie gelijk is aan de opgegeven [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de opgegeven [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bepaalt of deze instantie gelijk is aan de opgegeven [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Retourneert een hashcode voor het huidige object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [`SpreadsheetFormats`](../spreadsheetformats) object. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Komma-gescheiden waarden (CSV). Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Data Interchange Format (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 en Excel 2003 XML-formaat. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice of OpenOffice.org Calc XML-spreadsheet (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-gescheiden waarden (TSV). Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Add-in (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 binair bestandsformaat (XLS). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel binair werkboek (XLSB). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML-werkboek met macro's (XLSM). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML-werkboek zonder macro's (XLSX). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003-sjabloon (XLT). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML-sjabloon met macro's (XLTM). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML-sjabloon zonder macro's (XLTX). Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xltx). |

### Zie ook

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

---
title: SpreadsheetFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all binary XML and textual Spreadsheet formats excluding all textual delimiterbased formats with separator like CSV TSV semicolondelimited etc. in which the workbook can be saved. Includes the following formats Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Learn more about Spreadsheet formats herehttps//wiki.fileformat.com/spreadsheet.
type: docs
weight: 130
url: /net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Encapsulates all binary, XML and textual Spreadsheet formats (excluding all textual delimiter-based formats with separator like CSV, TSV, semicolon-delimited etc.), in which the workbook can be saved. Includes the following formats: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Learn more about Spreadsheet formats [here](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Gets the file extension of the document format. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Gets the format family to which the document format belongs. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Gets the unique identifier for the format family. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Gets the MIME type of the document format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Gets the name of the format family. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Gets an enumerable collection of all [`SpreadsheetFormats`](../spreadsheetformats). |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Retrieves an instance of the specified type [`SpreadsheetFormats`](../spreadsheetformats) that has the specified file extension. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instance. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determines whether this instance is equal to the specified [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instance. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determines whether this instance is equal to the specified [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instance. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returns a hash code for the current object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returns a string that represents the current object. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Converts a string representing a file extension to a [`SpreadsheetFormats`](../spreadsheetformats) object. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Comma Separated Values (CSV). Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Data Interchange Format (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 and Excel 2003 XML Format. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice or OpenOffice.org Calc XML Spreadsheet (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV). Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Add-in (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Template (XLT). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML Template Macro-Free (XLTX). Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltx). |

### See Also

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

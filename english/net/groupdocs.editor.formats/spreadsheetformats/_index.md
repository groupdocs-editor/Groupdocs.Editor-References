---
title: SpreadsheetFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all binary XML and textual Spreadsheet formats excluding all textual delimiterbased formats with separator like CSV TSV semicolondelimited etc. in which the workbook can be saved. Includes the following formats Dif./spreadsheetformats/dif Fods./spreadsheetformats/fods Ods./spreadsheetformats/ods Sxc./spreadsheetformats/sxc Xlam./spreadsheetformats/xlam Xls./spreadsheetformats/xls Xlsb./spreadsheetformats/xlsb Xlsm./spreadsheetformats/xlsm Xlsx./spreadsheetformats/xlsx Xlt./spreadsheetformats/xlt Xltm./spreadsheetformats/xltm Xltx./spreadsheetformats/xltx. Learn more about Spreadsheet formats herehttps//wiki.fileformat.com/spreadsheet.
type: docs
weight: 130
url: /net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Encapsulates all binary, XML and textual Spreadsheet formats (excluding all textual delimiter-based formats with separator like CSV, TSV, semicolon-delimited etc.), in which the workbook can be saved. Includes the following formats: [`Dif`](./dif), [`Fods`](./fods), [`Ods`](./ods), [`Sxc`](./sxc), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Learn more about Spreadsheet formats [here](https://wiki.fileformat.com/spreadsheet).

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Returns an extension (without leading dot character) of this Spreadsheet format in lower case |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Returns a MIME code for this format |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Returns a formal full name of this Spreadsheet format |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Returns instance of [`SpreadsheetFormats`](../spreadsheetformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Determines whether this instance is equal to the other specified object, that is presumably of boxed SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Determines whether this instance is equal to the other specified SpreadsheetFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Returns a hash-code, that is immutable for this instance |
| override [ToString](../../groupdocs.editor.formats/spreadsheetformats/tostring)() | Returns the name of this particular format, same as 'Name' property |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Checks two given SpreadsheetFormats instances on equality |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Checks two given SpreadsheetFormats instances on inequality |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Comma Separated Values (CSV) documents represent plain text that contain records of data with comma separated values. Each line in a CSV file is a new record from the set of records contained in the file. Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Data Interchange Format (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — stored as a single uncompressed XML document |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) stand for OpenDocument Spreadsheet Document format that are editable by user. Data is stored inside ODF file into rows and columns. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 and Excel 2003 XML Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice or OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV) file format represents data separated with tabs in plain text format. The file format, similar to CSV, is used for organization of data in a structured manner in order to import and export between different applications. Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Add-in (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) represents files that can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB)specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) is a type of Spreasheet files that support macros. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) represents documents that was introduced by Microsoft with the release of Microsoft Office 2007. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Template (XLT) represents template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. Microsoft Office 97-2003 supported creating new XLT files as well as opening these. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) represents files that are generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure other than that the later doesn't support creating template files with macros. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML Template Macro-Free (XLTX) file represents Microsoft Excel Template that are based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files that exhibit the same settings as specified in the XLTX file. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltx). |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Returns an internal class, that provides enumerable possibilities over all existing Spreadsheet formats |

## Other Members

| Name | Description |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implements IEnumerable generic interface, that enables a 'foreach' possibility for the SpreadsheetFormats type |

### See Also

* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

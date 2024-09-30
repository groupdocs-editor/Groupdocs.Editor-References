---
title: SpreadsheetFormats
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates all binary XML and textual Spreadsheet formats excluding all textual delimiter-based formats with separator like CSV TSV semicolon-delimited etc. in which the workbook can be saved.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Encapsulates all binary, XML and textual Spreadsheet formats (excluding all textual delimiter-based formats with separator like CSV, TSV, semicolon-delimited etc.), in which the workbook can be saved. Includes the following formats: [Dif](../../com.groupdocs.editor.formats/spreadsheetformats\#Dif), [Fods](../../com.groupdocs.editor.formats/spreadsheetformats\#Fods), [Ods](../../com.groupdocs.editor.formats/spreadsheetformats\#Ods), [Sxc](../../com.groupdocs.editor.formats/spreadsheetformats\#Sxc), [Xlam](../../com.groupdocs.editor.formats/spreadsheetformats\#Xlam), [Xls](../../com.groupdocs.editor.formats/spreadsheetformats\#Xls), [Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats\#Xlsb), [Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats\#Xlsm), [Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats\#Xlsx), [Xlt](../../com.groupdocs.editor.formats/spreadsheetformats\#Xlt), [Xltm](../../com.groupdocs.editor.formats/spreadsheetformats\#Xltm), [Xltx](../../com.groupdocs.editor.formats/spreadsheetformats\#Xltx). Learn more about Spreadsheet formats [here][].


[here]: https://wiki.fileformat.com/spreadsheet
## Fields

| Field | Description |
| --- | --- |
| [Xls](#Xls) | Excel 97-2003 Binary File Format (XLS). |
| [Xlt](#Xlt) | Excel 97-2003 Template (XLT). |
| [Xlsx](#Xlsx) | Office Open XML Workbook Macro-Free (XLSX). |
| [Xlsm](#Xlsm) | Office Open XML Workbook Macro-Enabled (XLSM). |
| [Xlsb](#Xlsb) | Excel Binary Workbook (XLSB). |
| [Xltx](#Xltx) | Office Open XML Template Macro-Free (XLTX). |
| [Xltm](#Xltm) | Office Open XML Template Macro-Enabled (XLTM). |
| [Xlam](#Xlam) | Excel Add-in (XLAM). |
| [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Microsoft Office Excel 2002 and Excel 2003 XML Format. |
| [Ods](#Ods) | OpenDocument Spreadsheet (ODS). |
| [Fods](#Fods) | Flat OpenDocument Spreadsheet (FODS). |
| [Sxc](#Sxc) | StarOffice or OpenOffice.org Calc XML Spreadsheet (SXC). |
| [Dif](#Dif) | Data Interchange Format (DIF). |
| [Csv](#Csv) | Comma Separated Values (CSV). |
| [Tsv](#Tsv) | Tab-Separated Values (TSV). |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets an enumerable collection of all [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Retrieves an instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) that has the specified file extension. |
| [fromString(String extension)](#fromString-java.lang.String-) | Converts a string representing a file extension to a [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object. |
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 Binary File Format (XLS). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xls

### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 Template (XLT). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML Workbook Macro-Free (XLSX). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML Workbook Macro-Enabled (XLSM). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel Binary Workbook (XLSB). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML Template Macro-Free (XLTX). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML Template Macro-Enabled (XLTM). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel Add-in (XLAM).

### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \\u2014 Microsoft Office Excel 2002 and Excel 2003 XML Format.

### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument Spreadsheet (ODS). Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/ods

### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument Spreadsheet (FODS).

### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice or OpenOffice.org Calc XML Spreadsheet (SXC).

### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Data Interchange Format (DIF).

### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Comma Separated Values (CSV). Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/csv/

### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Tab-Separated Values (TSV). Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/tsv/

### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Gets an enumerable collection of all [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).

Value: An  IEnumerable\{SpreadsheetFormats\}  containing all instances of [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).

**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Retrieves an instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) that has the specified file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension of the document format. |

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.
### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Converts a string representing a file extension to a [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension to convert. If the extension contains multiple periods, the part after the last period is used. |

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.

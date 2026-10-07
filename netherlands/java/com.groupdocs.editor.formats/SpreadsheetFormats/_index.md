---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat alle binaire XML‑ en tekstuele Spreadsheet‑formaten, met uitzondering van alle tekstuele, op scheidingstekens gebaseerde formaten met scheidingsteken zoals CSV, TSV, puntkomma‑gescheiden enz., waarin de werkmap kan worden opgeslagen."
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Omvat alle binaire, XML- en tekstuele Spreadsheet‑formaten (exclusief alle tekstgebaseerde scheidingsteken‑formaten zoals CSV, TSV, puntkomma‑gescheiden enz.), waarin de werkmap kan worden opgeslagen.
Bevat de volgende formaten:
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
Meer informatie over Spreadsheet‑formaten [hier](../https://wiki.fileformat.com/spreadsheet).

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 Binair Bestandsformaat (XLS). |
|
|  | [Xlt](#Xlt) | Excel 97-2003 Sjabloon (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML Werkmap Zonder Macro's (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML-werkmap met macro's (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel-binair werkboek (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML-sjabloon zonder macro's (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML-sjabloon met macro's (XLTM). |
|
|  | [Xlam](#Xlam) | Excel-invoegtoepassing (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Microsoft Office Excel 2002 en Excel 2003 XML-indeling. |
|
|  | [Ods](#Ods) | OpenDocument-spreadsheet (ODS). |
|
|  | [Fods](#Fods) | Platte OpenDocument-spreadsheet (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice- of OpenOffice.org Calc XML-spreadsheet (SXC). |
|
|  | [Dif](#Dif) | Data-uitwisselingsformaat (DIF). |
|
|  | [Csv](#Csv) | Komma-gescheiden waarden (CSV). |
|
|  | [Tsv](#Tsv) | Tab-gescheiden waarden (TSV). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt een enumerabele collectie op van alle [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Haalt een instantie op van het opgegeven type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) dat de opgegeven bestandsextensie heeft. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converteert een tekenreeks die een bestandsextensie voorstelt naar een [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-object. |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 Binair Bestandsformaat (XLS).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 Sjabloon (XLT).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML Werkmap Zonder Macro's (XLSX).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML-werkmap met macro's (XLSM).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel-binair werkboek (XLSB).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML-sjabloon zonder macro's (XLTX).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML-sjabloon met macro's (XLTM).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel-invoegtoepassing (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Microsoft Office Excel 2002 en Excel 2003 XML-indeling.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument-spreadsheet (ODS).
Meer informatie over dit bestandsformaat
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Platte OpenDocument-spreadsheet (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice- of OpenOffice.org Calc XML-spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Data-uitwisselingsformaat (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Komma-gescheiden waarden (CSV).
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Tab-gescheiden waarden (TSV).
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Haalt een enumerabele collectie op van alle [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Waarde: Een IEnumerable{SpreadsheetFormats} die alle instanties van [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) bevat.


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Haalt een instantie op van het opgegeven type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) dat de opgegeven bestandsextensie heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie van het documentformaat. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Converteert een tekenreeks die een bestandsextensie voorstelt naar een [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie om te converteren. Als de extensie meerdere punten bevat, wordt het deel na het laatste punt gebruikt. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


---
title: "Kalkylbladsformat"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Inkluderar alla binära XML‑ och textbaserade kalkylbladsformat, exklusive alla textbaserade format med avgränsare som CSV, TSV, semikolon‑avgränsade etc., som arbetsboken kan sparas i."
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Innesluter alla binära, XML‑ och textbaserade kalkylbladsformat (exklusive alla textbaserade format med avgränsare som CSV, TSV, semikolon‑avgränsade etc.), i vilka arbetsboken kan sparas.
Inkluderar följande format:
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
Läs mer om kalkylbladsformat [här](../https://wiki.fileformat.com/spreadsheet).

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 binärt filformat (XLS). |
|
|  | [Xlt](#Xlt) | Excel 97-2003 mall (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML arbetsbok utan makron (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML arbetsbok med makron (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel binär arbetsbok (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML mall utan makron (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML mall med makron (XLTM). |
|
|  | [Xlam](#Xlam) | Excel‑tillägg (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \u2014 Microsoft Office Excel 2002 och Excel 2003 XML‑format. |
|
|  | [Ods](#Ods) | OpenDocument kalkylblad (ODS). |
|
|  | [Fods](#Fods) | Flat OpenDocument kalkylblad (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice eller OpenOffice.org Calc XML-kalkylblad (SXC). |
|
|  | [Dif](#Dif) | Datautbytesformat (DIF). |
|
|  | [Csv](#Csv) | Kommaseparerade värden (CSV). |
|
|  | [Tsv](#Tsv) | Tabbseparerade värden (TSV). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en enumererbar samling av alla [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den angivna typen [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) som har den angivna filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-objekt. |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 binärt filformat (XLS).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 mall (XLT).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML arbetsbok utan makron (XLSX).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML arbetsbok med makron (XLSM).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel binär arbetsbok (XLSB).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML mall utan makron (XLTX).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML mall med makron (XLTM).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel‑tillägg (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \u2014 Microsoft Office Excel 2002 och Excel 2003 XML‑format.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument kalkylblad (ODS).
Läs mer om detta filformat
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument kalkylblad (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice eller OpenOffice.org Calc XML-kalkylblad (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Datautbytesformat (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Kommaseparerade värden (CSV).
Läs mer om detta filformat
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Tabbseparerade värden (TSV).
Läs mer om detta filformat
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Hämtar en enumererbar samling av alla [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Värde: En  IEnumerable{SpreadsheetFormats}  som innehåller alla instanser av [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Hämtar en instans av den angivna typen [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) som har den angivna filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


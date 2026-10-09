---
title: "SpreadsheetFormats"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Raccoglie tutti i formati di foglio di calcolo binari, XML e testuali, escludendo tutti i formati testuali basati su delimitatori con separatori come CSV, TSV, delimitati da punto e virgola, ecc., in cui è possibile salvare la cartella di lavoro."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Incapsula tutti i formati binari, XML e testuali di Foglio di calcolo (escludendo tutti i formati testuali basati su delimitatori con separatori come CSV, TSV, delimitati da punto e virgola, ecc.), in cui è possibile salvare la cartella di lavoro.
Include i seguenti formati:
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
Scopri di più sui formati di foglio di calcolo [qui](../https://wiki.fileformat.com/spreadsheet).

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Xls](#Xls) | Formato file binario Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Modello Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Cartella di lavoro Office Open XML senza macro (XLSX). |
|
|  | [Xlsm](#Xlsm) | Cartella di lavoro Office Open XML con macro (XLSM). |
|
|  | [Xlsb](#Xlsb) | Cartella di lavoro binaria Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Modello Office Open XML senza macro (XLTX). |
|
|  | [Xltm](#Xltm) | Modello Office Open XML con macro (XLTM). |
|
|  | [Xlam](#Xlam) | Add-in Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Formato XML di Microsoft Office Excel 2002 e Excel 2003. |
|
|  | [Ods](#Ods) | Fogli di calcolo OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Fogli di calcolo OpenDocument flat (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice o OpenOffice.org Calc XML Spreadsheet (SXC). |
|
|  | [Dif](#Dif) | Formato di scambio dati (DIF). |
|
|  | [Csv](#Csv) | Valori separati da virgola (CSV). |
|
|  | [Tsv](#Tsv) | Valori separati da tabulazione (TSV). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAll()](#getAll--) | Ottiene una collezione enumerabile di tutti i [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera un'istanza del tipo specificato [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) che ha l'estensione di file specificata. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converte una stringa che rappresenta un'estensione di file in un oggetto [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Formato file binario Excel 97-2003 (XLS).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Modello Excel 97-2003 (XLT).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Cartella di lavoro Office Open XML senza macro (XLSX).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Cartella di lavoro Office Open XML con macro (XLSM).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Cartella di lavoro binaria Excel (XLSB).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Modello Office Open XML senza macro (XLTX).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Modello Office Open XML con macro (XLTM).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Add-in Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Formato XML di Microsoft Office Excel 2002 e Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Fogli di calcolo OpenDocument (ODS).
Scopri di più su questo formato di file
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Fogli di calcolo OpenDocument flat (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice o OpenOffice.org Calc XML Spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Formato di scambio dati (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Valori separati da virgola (CSV).
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Valori separati da tabulazione (TSV).
Scopri di più su questo formato di file
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Ottiene una collezione enumerabile di tutti i [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Valore: Un IEnumerable{SpreadsheetFormats} contenente tutte le istanze di [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Recupera un'istanza del tipo specificato [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) che ha l'estensione di file specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file del formato del documento. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Converte una stringa che rappresenta un'estensione di file in un oggetto [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file da convertire. Se l'estensione contiene più punti, viene utilizzata la parte dopo l'ultimo punto. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


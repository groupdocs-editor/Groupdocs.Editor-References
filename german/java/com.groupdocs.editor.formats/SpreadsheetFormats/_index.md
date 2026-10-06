---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt alle binären XML‑ und textbasierten Tabellenkalkulationsformate, ausgenommen alle textbasierten, durch Trennzeichen definierten Formate mit Separatoren wie CSV, TSV, semikolongetrennt usw., in denen die Arbeitsmappe gespeichert werden kann."
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Kapselt alle binären, XML- und textuellen Tabellenkalkulationsformate (ausgenommen alle textbasierten, durch Trennzeichen getrennten Formate wie CSV, TSV, semikolongetrennt usw.), in denen die Arbeitsmappe gespeichert werden kann.
Enthält die folgenden Formate:
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
Erfahren Sie mehr über Tabellenkalkulationsformate [hier](../https://wiki.fileformat.com/spreadsheet).

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Xls](#Xls) | Excel‑97‑2003‑Binärdateiformat (XLS). |
|
|  | [Xlt](#Xlt) | Excel‑97‑2003‑Vorlage (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML‑Arbeitsmappe ohne Makros (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML‑Arbeitsmappe mit Makros (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel‑Binärarbeitsmappe (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML-Vorlage ohne Makros (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML-Vorlage mit Makros (XLTM). |
|
|  | [Xlam](#Xlam) | Excel-Add-In (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Microsoft Office Excel 2002 und Excel 2003 XML-Format. |
|
|  | [Ods](#Ods) | OpenDocument-Tabellendokument (ODS). |
|
|  | [Fods](#Fods) | Flaches OpenDocument-Tabellendokument (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice- oder OpenOffice.org-Calc-XML-Tabellendokument (SXC). |
|
|  | [Dif](#Dif) | Daten-Austauschformat (DIF). |
|
|  | [Csv](#Csv) | Kommagetrennte Werte (CSV). |
|
|  | [Tsv](#Tsv) | Tabulatorgetrennte Werte (TSV). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Gibt eine aufzählbare Sammlung aller [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) zurück. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) ab, die die angegebene Dateierweiterung hat. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-Objekt. |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel‑97‑2003‑Binärdateiformat (XLS).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel‑97‑2003‑Vorlage (XLT).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML‑Arbeitsmappe ohne Makros (XLSX).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML‑Arbeitsmappe mit Makros (XLSM).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel‑Binärarbeitsmappe (XLSB).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML-Vorlage ohne Makros (XLTX).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML-Vorlage mit Makros (XLTM).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel-Add-In (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Microsoft Office Excel 2002 und Excel 2003 XML-Format.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument-Tabellendokument (ODS).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flaches OpenDocument-Tabellendokument (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice- oder OpenOffice.org-Calc-XML-Tabellendokument (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Daten-Austauschformat (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Kommagetrennte Werte (CSV).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Tabulatorgetrennte Werte (TSV).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Gibt eine aufzählbare Sammlung aller [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) zurück.
Wert: Ein IEnumerable{SpreadsheetFormats}, das alle Instanzen von [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) ab, die die angegebene Dateierweiterung hat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung zum Konvertieren. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


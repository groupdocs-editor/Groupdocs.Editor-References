---
title: "SpreadsheetFormats"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Encapsula todos los formatos de hoja de cálculo binarios, XML y textuales, excluyendo todos los formatos textuales basados en delimitadores con separadores como CSV, TSV, delimitados por punto y coma, etc., en los que se puede guardar el libro de trabajo."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Encapsula todos los formatos binarios, XML y textuales de hojas de cálculo (excluyendo todos los formatos basados en delimitadores textuales con separadores como CSV, TSV, delimitados por punto y coma, etc.), en los que se puede guardar el libro de trabajo.
Incluye los siguientes formatos:
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
Aprende más sobre los formatos de hoja de cálculo [aquí](../https://wiki.fileformat.com/spreadsheet).

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Xls](#Xls) | Formato de archivo binario de Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Plantilla de Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Libro de trabajo Office Open XML sin macros (XLSX). |
|
|  | [Xlsm](#Xlsm) | Libro de trabajo Office Open XML con macros (XLSM). |
|
|  | [Xlsb](#Xlsb) | Libro de trabajo binario de Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Plantilla Office Open XML sin macros (XLTX). |
|
|  | [Xltm](#Xltm) | Plantilla Office Open XML con macros (XLTM). |
|
|  | [Xlam](#Xlam) | Complemento de Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Formato XML de Microsoft Office Excel 2002 y Excel 2003. |
|
|  | [Ods](#Ods) | Hoja de cálculo OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Hoja de cálculo OpenDocument plana (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice o OpenOffice.org Calc XML Spreadsheet (SXC). |
|
|  | [Dif](#Dif) | Formato de Intercambio de Datos (DIF). |
|
|  | [Csv](#Csv) | Valores Separados por Comas (CSV). |
|
|  | [Tsv](#Tsv) | Valores Separados por Tabulaciones (TSV). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Formato de archivo binario de Excel 97-2003 (XLS).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Plantilla de Excel 97-2003 (XLT).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Libro de trabajo Office Open XML sin macros (XLSX).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Libro de trabajo Office Open XML con macros (XLSM).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Libro de trabajo binario de Excel (XLSB).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Plantilla Office Open XML sin macros (XLTX).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Plantilla Office Open XML con macros (XLTM).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Complemento de Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Formato XML de Microsoft Office Excel 2002 y Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Hoja de cálculo OpenDocument (ODS).
Aprende más sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Hoja de cálculo OpenDocument plana (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice o OpenOffice.org Calc XML Spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Formato de Intercambio de Datos (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Valores Separados por Comas (CSV).
Aprende más sobre este formato de archivo
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Valores Separados por Tabulaciones (TSV).
Aprende más sobre este formato de archivo
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Obtiene una colección enumerable de todos los [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Valor: Un IEnumerable{SpreadsheetFormats} que contiene todas las instancias de [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


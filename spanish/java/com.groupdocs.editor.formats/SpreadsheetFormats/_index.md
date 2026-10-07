---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos binarios XML y de hoja de cálculo textuales, excluyendo todos los formatos basados en delimitadores textuales con separadores como CSV, TSV, delimitados por punto y coma, etc., en los que se puede guardar el libro de trabajo."
type: docs
weight: 15
url: /es/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Encapsula todos los formatos binarios, XML y textuales de Hoja de cálculo (excluyendo todos los formatos basados en delimitadores de texto con separadores como CSV, TSV, delimitados por punto y coma, etc.), en los que se puede guardar el libro de trabajo.
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
Obtén más información sobre los formatos de hoja de cálculo [aquí](../https://wiki.fileformat.com/spreadsheet).

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Xls](#Xls) | Formato de archivo binario Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Plantilla Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Libro de trabajo Office Open XML sin macros (XLSX). |
|
|  | [Xlsm](#Xlsm) | Libro de trabajo Office Open XML con macros (XLSM). |
|
|  | [Xlsb](#Xlsb) | Libro de trabajo binario Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Plantilla de Office Open XML sin macros (XLTX). |
|
|  | [Xltm](#Xltm) | Plantilla de Office Open XML con macros (XLTM). |
|
|  | [Xlam](#Xlam) | Complemento de Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Formato XML de Microsoft Office Excel 2002 y Excel 2003. |
|
|  | [Ods](#Ods) | Hoja de cálculo OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Hoja de cálculo OpenDocument plana (FODS). |
|
|  | [Sxc](#Sxc) | Hoja de cálculo XML de StarOffice o OpenOffice.org Calc (SXC). |
|
|  | [Dif](#Dif) | Formato de Intercambio de Datos (DIF). |
|
|  | [Csv](#Csv) | Valores separados por comas (CSV). |
|
|  | [Tsv](#Tsv) | Valores separados por tabulaciones (TSV). |
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


Formato de archivo binario Excel 97-2003 (XLS).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Plantilla Excel 97-2003 (XLT).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Libro de trabajo Office Open XML sin macros (XLSX).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Libro de trabajo Office Open XML con macros (XLSM).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Libro de trabajo binario Excel (XLSB).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Plantilla de Office Open XML sin macros (XLTX).
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Plantilla de Office Open XML con macros (XLTM).
Obtén más información sobre este formato de archivo
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


SpreadsheetML \\u2014 Formato XML de Microsoft Office Excel 2002 y Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Hoja de cálculo OpenDocument (ODS).
Obtén más información sobre este formato de archivo
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


Hoja de cálculo XML de StarOffice o OpenOffice.org Calc (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Formato de Intercambio de Datos (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Valores separados por comas (CSV).
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Valores separados por tabulaciones (TSV).
Obtén más información sobre este formato de archivo
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


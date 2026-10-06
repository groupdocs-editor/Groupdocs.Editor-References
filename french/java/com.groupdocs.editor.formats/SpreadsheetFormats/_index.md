---
title: "SpreadsheetFormats"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Encapsule tous les formats de feuille de calcul XML binaires et textuels, à l'exception de tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, délimité par point‑virgule, etc., dans lesquels le classeur peut être enregistré."
type: docs
weight: 15
url: /fr/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Encapsule tous les formats de feuille de calcul binaires, XML et textuels (excluant tous les formats textuels basés sur des délimiteurs avec séparateur comme CSV, TSV, séparés par des points-virgules, etc.), dans lesquels le classeur peut être enregistré.
Inclut les formats suivants :
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
En savoir plus sur les formats de feuille de calcul [ici](../https://wiki.fileformat.com/spreadsheet).

## Champs

| Champ | Description |
| --- | --- |
|  | [Xls](#Xls) | Format de fichier binaire Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Modèle Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Classeur Office Open XML sans macro (XLSX). |
|
|  | [Xlsm](#Xlsm) | Classeur Office Open XML avec macro (XLSM). |
|
|  | [Xlsb](#Xlsb) | Classeur binaire Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Modèle Office Open XML sans macro (XLTX). |
|
|  | [Xltm](#Xltm) | Modèle Office Open XML avec macro (XLTM). |
|
|  | [Xlam](#Xlam) | Module complémentaire Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Format XML de Microsoft Office Excel 2002 et Excel 2003. |
|
|  | [Ods](#Ods) | Feuille de calcul OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Feuille de calcul OpenDocument plate (FODS). |
|
|  | [Sxc](#Sxc) | Feuille de calcul XML StarOffice ou OpenOffice.org Calc (SXC). |
|
|  | [Dif](#Dif) | Format d'échange de données (DIF). |
|
|  | [Csv](#Csv) | Valeurs séparées par des virgules (CSV). |
|
|  | [Tsv](#Tsv) | Valeurs séparées par des tabulations (TSV). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) qui possède l'extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Format de fichier binaire Excel 97-2003 (XLS).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Modèle Excel 97-2003 (XLT).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Classeur Office Open XML sans macro (XLSX).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Classeur Office Open XML avec macro (XLSM).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Classeur binaire Excel (XLSB).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Modèle Office Open XML sans macro (XLTX).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Modèle Office Open XML avec macro (XLTM).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Module complémentaire Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \\u2014 Format XML de Microsoft Office Excel 2002 et Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Feuille de calcul OpenDocument (ODS).
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Feuille de calcul OpenDocument plate (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


Feuille de calcul XML StarOffice ou OpenOffice.org Calc (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Format d'échange de données (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Valeurs séparées par des virgules (CSV).
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Valeurs séparées par des tabulations (TSV).
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Obtient une collection énumérable de tous les [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Valeur : Un IEnumerable{SpreadsheetFormats} contenant toutes les instances de [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) qui possède l'extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format du document. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


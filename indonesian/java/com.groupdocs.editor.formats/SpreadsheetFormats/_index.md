---
title: "SpreadsheetFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengenkapsulasi semua format Spreadsheet biner XML dan tekstual, kecuali semua format berbasis pemisah tekstual dengan pemisah seperti CSV, TSV, dipisahkan dengan titik koma, dll., yang dapat menyimpan workbook."
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Mengkapsulkan semua format Spreadsheet biner, XML, dan tekstual (mengecualikan semua format berbasis pemisah teks dengan pemisah seperti CSV, TSV, dipisahkan titik koma, dll.), di mana buku kerja dapat disimpan.
Menyertakan format berikut:
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
Pelajari lebih lanjut tentang format Spreadsheet [di sini](../https://wiki.fileformat.com/spreadsheet).

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Xls](#Xls) | Format File Biner Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Templat Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Workbook Office Open XML Tanpa Makro (XLSX). |
|
|  | [Xlsm](#Xlsm) | Buku kerja Office Open XML yang Mendukung Makro (XLSM). |
|
|  | [Xlsb](#Xlsb) | Buku kerja Biner Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Templat Office Open XML Tanpa Makro (XLTX). |
|
|  | [Xltm](#Xltm) | Templat Office Open XML yang Mendukung Makro (XLTM). |
|
|  | [Xlam](#Xlam) | Add-in Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Format XML Microsoft Office Excel 2002 dan Excel 2003. |
|
|  | [Ods](#Ods) | Spreadsheet OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Spreadsheet OpenDocument Datar (FODS). |
|
|  | [Sxc](#Sxc) | Spreadsheet XML StarOffice atau OpenOffice.org Calc (SXC). |
|
|  | [Dif](#Dif) | Format Pertukaran Data (DIF). |
|
|  | [Csv](#Csv) | Nilai yang Dipisahkan Koma (CSV). |
|
|  | [Tsv](#Tsv) | Nilai yang Dipisahkan Tab (TSV). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi enumerable dari semua [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) yang memiliki ekstensi file yang ditentukan. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi file menjadi objek [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Format File Biner Excel 97-2003 (XLS).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Templat Excel 97-2003 (XLT).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Workbook Office Open XML Tanpa Makro (XLSX).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Buku kerja Office Open XML yang Mendukung Makro (XLSM).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Buku kerja Biner Excel (XLSB).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Templat Office Open XML Tanpa Makro (XLTX).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Templat Office Open XML yang Mendukung Makro (XLTM).
Pelajari lebih lanjut tentang format berkas ini
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


SpreadsheetML — Format XML Microsoft Office Excel 2002 dan Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Spreadsheet OpenDocument (ODS).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Spreadsheet OpenDocument Datar (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


Spreadsheet XML StarOffice atau OpenOffice.org Calc (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Format Pertukaran Data (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Nilai yang Dipisahkan Koma (CSV).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Nilai yang Dipisahkan Tab (TSV).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Mendapatkan koleksi enumerable dari semua [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Nilai: Sebuah IEnumerable{SpreadsheetFormats} yang berisi semua instance dari [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Mengambil sebuah instance dari tipe yang ditentukan [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) yang memiliki ekstensi file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi file menjadi objek [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


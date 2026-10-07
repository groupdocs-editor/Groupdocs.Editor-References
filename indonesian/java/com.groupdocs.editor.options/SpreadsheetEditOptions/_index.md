---
title: "SpreadsheetEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan menentukan opsi khusus untuk mengedit dokumen dari semua format Spreadsheet yang kompatibel dengan Excel yang didukung."
type: docs
weight: 35
url: /id/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Memungkinkan menentukan opsi khusus untuk mengedit semua dokumen yang didukung
Format Spreadsheet (kompatibel dengan Excel)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Memungkinkan menentukan indeks berbasis 0 dari lembar kerja (tab) input |
Dokumen Spreadsheet, yang harus dikonversi ke HTML (lihat
catatan).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Memungkinkan menentukan indeks berbasis 0 dari lembar kerja (tab) input |
Dokumen Spreadsheet, yang harus dikonversi ke HTML (lihat
catatan).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga |
mereka akan sepenuhnya diabaikan.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga |
mereka akan sepenuhnya diabaikan.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Ketika diaktifkan, sel horizontal kosong yang berdekatan dari dokumen Spreadsheet input akan |
ditampilkan dalam dokumen HTML yang dapat diedit sebagai digabung menjadi satu sel dengan
atribut colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Ketika diaktifkan, tabel HTML dalam dokumen HTML yang dihasilkan berisi baris tersembunyi kosong di bagian bawah dengan |
tinggi nol dan sel kosong, di mana hanya lebar yang ditentukan.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Memungkinkan menentukan indeks berbasis 0 dari lembar kerja (tab) input
Dokumen Spreadsheet, yang harus dikonversi ke HTML (lihat
catatan).


*** ** * ** ***

Sebagian besar dokumen Spreadsheet mendukung konsep tab, yaitu mereka dapat memiliki banyak tab. Di sisi lain, format HTML tidak mendukung struktur tersebut. Karena itu GroupDocs.Editor dapat mengonversi ke HTML hanya satu tab tertentu dari dokumen input, dan opsi ini memungkinkan untuk menentukan tab tersebut. Indeks tab berbasis 0, nilai negatif dilarang. Jika indeks yang ditentukan melebihi jumlah semua tab, akan dilemparkan pengecualian. Jika dokumen Spreadsheet input hanya berisi satu tab, opsi ini akan diabaikan. Nilai default adalah 0 (tab pertama).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Memungkinkan menentukan indeks berbasis 0 dari lembar kerja (tab) input
Dokumen Spreadsheet, yang harus dikonversi ke HTML (lihat
catatan).


*** ** * ** ***

Sebagian besar dokumen Spreadsheet mendukung konsep tab, yaitu mereka dapat memiliki banyak tab. Di sisi lain, format HTML tidak mendukung struktur tersebut. Karena itu GroupDocs.Editor dapat mengonversi ke HTML hanya satu tab tertentu dari dokumen input, dan opsi ini memungkinkan untuk menentukan tab tersebut. Indeks tab berbasis 0, nilai negatif dilarang. Jika indeks yang ditentukan melebihi jumlah semua tab, akan dilemparkan pengecualian. Jika dokumen Spreadsheet input hanya berisi satu tab, opsi ini akan diabaikan. Nilai default adalah 0 (tab pertama).

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga
mereka akan sepenuhnya diabaikan. Default adalah false - lembar kerja tersembunyi
tersedia dan diproses seperti biasa.


*** ** * ** ***

Beberapa format Spreadsheet biner (seperti XLSX) mendukung konsep lembar kerja tersembunyi (tab). Dokumen dengan format tersebut, jika memiliki lebih dari satu lembar kerja, dapat berisi lembar kerja tersembunyi tambahan. Secara default lembar kerja tersembunyi tersebut tersedia untuk diproses, tetapi dengan opsi ini dapat diabaikan, seolah-olah lembar kerja tersembunyi tersebut tidak ada. Ketika opsi ini diaktifkan, Anda tidak dapat memilih lembar kerja tersembunyi dengan properti 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga
mereka akan sepenuhnya diabaikan. Default adalah false - lembar kerja tersembunyi
tersedia dan diproses seperti biasa.


*** ** * ** ***

Beberapa format Spreadsheet biner (seperti XLSX) mendukung konsep lembar kerja tersembunyi (tab). Dokumen dengan format tersebut, jika memiliki lebih dari satu lembar kerja, dapat berisi lembar kerja tersembunyi tambahan. Secara default lembar kerja tersembunyi tersebut tersedia untuk diproses, tetapi dengan opsi ini dapat diabaikan, seolah-olah lembar kerja tersembunyi tersebut tidak ada. Ketika opsi ini diaktifkan, Anda tidak dapat memilih lembar kerja tersembunyi dengan properti 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Ketika diaktifkan, sel horizontal kosong yang berdekatan dari dokumen Spreadsheet input akan
ditampilkan dalam dokumen HTML yang dapat diedit sebagai digabung menjadi satu sel dengan
atribut colspan. Secara default dinonaktifkan (false).


Secara default GroupDocs.Editor mengonversi tabel dari dokumen Spreadsheet input ke output
dokumen HTML dengan mempertahankan setiap sel. Namun, dokumen Spreadsheet dapat menjadi jarang \\u2014 mereka
dapat berisi sejumlah besar "empty areas", di mana banyak sel kosong. Opsi ini, ketika
diaktifkan, menggabungkan sel kosong tersebut menjadi satu dengan atribut colspan dalam elemen TD,
dan dengan demikian dapat secara signifikan mengurangi ukuran markup HTML yang dihasilkan.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Ketika diaktifkan, tabel HTML dalam dokumen HTML yang dihasilkan berisi baris tersembunyi kosong di bagian bawah dengan
tinggi nol dan sel kosong, di mana hanya lebar yang ditentukan. Baris ini dengan sel kosong berisi
nilai lebar tepat untuk setiap kolom dan meningkatkan konversi balik dari HTML ke Spreadsheet. Oleh
default diaktifkan (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |


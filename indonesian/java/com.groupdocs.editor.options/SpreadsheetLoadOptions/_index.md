---
title: "SpreadsheetLoadOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi untuk memuat dokumen biner Spreadsheet Cells yang kompatibel dengan Excel seperti XLSX, ODS, dll."
type: docs
weight: 36
url: /id/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Berisi opsi untuk memuat Spreadsheet biner (Cells, kompatibel dengan Excel)
dokumen seperti XLS(X), ODS, dll. ke dalam kelas Editor

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Konstruktor default tanpa parameter - semua parameter memiliki nilai default |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen Spreadsheet, jika dokumen tersebut dikodekan.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen Spreadsheet, jika dokumen tersebut dikodekan.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input, |
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input, |
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Konstruktor default tanpa parameter - semua parameter memiliki nilai default


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen Spreadsheet, jika terenkripsi. Set ke NULL atau kosong
string untuk tidak menggunakan kata sandi (nilai default).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen Spreadsheet, jika terenkripsi. Set ke NULL atau kosong
string untuk tidak menggunakan kata sandi (nilai default).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input,
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual. Berguna saat memproses dokumen besar dan
menghadapi OutOfMemoryException. Default adalah false (optimisasi memori
dinonaktifkan demi kinerja yang lebih baik).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input,
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual. Berguna saat memproses dokumen besar dan
menghadapi OutOfMemoryException. Default adalah false (optimisasi memori
dinonaktifkan demi kinerja yang lebih baik).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |


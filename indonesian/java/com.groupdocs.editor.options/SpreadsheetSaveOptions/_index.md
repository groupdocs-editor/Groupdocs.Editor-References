---
title: "SpreadsheetSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Spreadsheet yang sesuai dengan Excel"
type: docs
weight: 37
url: /id/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan Spreadsheet
(dokumen yang sesuai dengan Excel)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Konstruktor tanpa parameter ini membuat instance baru dari SpreadsheetSaveOptions dengan format output XLSX (dapat diubah kemudian melalui |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) properti)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Membuat instance baru dari SpreadsheetSaveOptions dengan wajib yang ditentukan |
Format output Spreadsheet, sementara semua parameter lainnya menggunakan nilai default
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan |
digunakan untuk mengkode dokumen Spreadsheet yang dihasilkan, jika format dokumen ini
mendukung perlindungan kata sandi.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan |
digunakan untuk mengkode dokumen Spreadsheet yang dihasilkan, jika format dokumen ini
mendukung perlindungan kata sandi.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Memungkinkan untuk menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada |
alih-alih membuat spreadsheet lembar kerja tunggal baru (default
perilaku).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Memungkinkan untuk menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada |
alih-alih membuat spreadsheet lembar kerja tunggal baru (default
perilaku).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan |
lembar kerja yang ada di spreadsheet asli pada posisi, yang ditentukan oleh
yang

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti, atau harus disisipkan di antara lembar kerja yang ada dan
yang sebelumnya, tanpa mengganti isinya.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan |
lembar kerja yang ada di spreadsheet asli pada posisi, yang ditentukan oleh
yang

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti, atau harus disisipkan di antara lembar kerja yang ada dan
yang sebelumnya, tanpa mengganti isinya.
|
|  | [getOutputFormat()](#getOutputFormat--) | Memungkinkan untuk menentukan format Spreadsheet, yang akan digunakan untuk menyimpan |
dokumen
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Memungkinkan untuk menentukan format Spreadsheet, yang akan digunakan untuk menyimpan |
dokumen
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Memungkinkan untuk mengaktifkan perlindungan lembar kerja untuk Spreadsheet output |
dokumen.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Memungkinkan untuk mengaktifkan perlindungan lembar kerja untuk Spreadsheet output |
dokumen.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Memungkinkan untuk menentukan array dengan nomor lembar kerja berbasis 1 yang harus dihapus dari spreadsheet saat disimpan, jika lembar kerja yang diedit dimasukkan ke dalam spreadsheet yang sudah ada. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Memungkinkan untuk menentukan array dengan nomor lembar kerja berbasis 1 yang harus dihapus dari spreadsheet saat disimpan, jika lembar kerja yang diedit dimasukkan ke dalam spreadsheet yang sudah ada. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Konstruktor tanpa parameter ini membuat instance baru dari SpreadsheetSaveOptions dengan format output XLSX (dapat diubah kemudian melalui
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) properti)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Membuat instance baru dari SpreadsheetSaveOptions dengan wajib yang ditentukan
Format output Spreadsheet, sementara semua parameter lainnya menggunakan nilai default


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Format output wajib, di mana dokumen Spreadsheet harus disimpan |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan
digunakan untuk mengkode dokumen Spreadsheet yang dihasilkan, jika format dokumen ini
mendukung perlindungan kata sandi. Tentukan NULL atau string kosong untuk menghapus
(membersihkan) kata sandi.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan
digunakan untuk mengkode dokumen Spreadsheet yang dihasilkan, jika format dokumen ini
mendukung perlindungan kata sandi. Tentukan NULL atau string kosong untuk menghapus
(membersihkan) kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Memungkinkan untuk menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada
alih-alih membuat spreadsheet lembar kerja tunggal baru (default
perilaku). WorksheetNumber adalah nomor berbasis 1 dari sebuah lembar kerja dalam
spreadsheet, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default),
spreadsheet baru akan dibuat dengan satu lembar kerja yang diedit. Jika nilainya
lebih besar atau lebih kecil dari nol, dan ada spreadsheet yang valid, dimuat dalam
kelas Editor, lembar kerja yang diedit, yang direpresentasikan oleh input
instance EditableDocument, akan dimasukkan ke dalam spreadsheet ini.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Memungkinkan untuk menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada
alih-alih membuat spreadsheet lembar kerja tunggal baru (default
perilaku). WorksheetNumber adalah nomor berbasis 1 dari sebuah lembar kerja dalam
spreadsheet, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default),
spreadsheet baru akan dibuat dengan satu lembar kerja yang diedit. Jika nilainya
lebih besar atau lebih kecil dari nol, dan ada spreadsheet yang valid, dimuat dalam
kelas Editor, lembar kerja yang diedit, yang direpresentasikan oleh input
instance EditableDocument, akan dimasukkan ke dalam spreadsheet ini.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan
lembar kerja yang ada di spreadsheet asli pada posisi, yang ditentukan oleh
yang

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti, atau harus disisipkan di antara lembar kerja yang ada dan
yang sebelumnya, tanpa mengganti isinya. Secara default adalah false \\u2014
lembar kerja yang ada akan diganti. Properti ini diabaikan, jika nilai
dari

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti diatur ke '0'.


*** ** * ** ***

Secara default lembar kerja diganti. Ini berarti bahwa jika spreadsheet yang diberikan memiliki 5 lembar kerja, dan WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, maka lembar kerja ke-4 akan diganti dengan lembar kerja yang baru diedit, sementara total jumlah lembar kerja dalam spreadsheet (5) tetap tidak berubah. Namun, jika nilai properti ini diatur ke  *true* , lembar kerja yang baru diedit akan disisipkan sebagai lembar kerja ke-4, dan semua lembar kerja berikutnya akan dipindahkan ke akhir: \"old\" lembar kerja ke-4 menjadi ke-5, dan ke-5 menjadi ke-6, dan total jumlah lembar kerja dalam spreadsheet akan bertambah satu menjadi 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan
lembar kerja yang ada di spreadsheet asli pada posisi, yang ditentukan oleh
yang

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti, atau harus disisipkan di antara lembar kerja yang ada dan
yang sebelumnya, tanpa mengganti isinya. Secara default adalah false \\u2014
lembar kerja yang ada akan diganti. Properti ini diabaikan, jika nilai
dari

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
properti diatur ke '0'.


*** ** * ** ***

Secara default lembar kerja diganti. Ini berarti bahwa jika spreadsheet yang diberikan memiliki 5 lembar kerja, dan WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, maka lembar kerja ke-4 akan diganti dengan lembar kerja yang baru diedit, sementara total jumlah lembar kerja dalam spreadsheet (5) tetap tidak berubah. Namun, jika nilai properti ini diatur ke  *true* , lembar kerja yang baru diedit akan disisipkan sebagai lembar kerja ke-4, dan semua lembar kerja berikutnya akan dipindahkan ke akhir: \"old\" lembar kerja ke-4 menjadi ke-5, dan ke-5 menjadi ke-6, dan total jumlah lembar kerja dalam spreadsheet akan bertambah satu menjadi 6.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Memungkinkan untuk menentukan format Spreadsheet, yang akan digunakan untuk menyimpan
dokumen


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Memungkinkan untuk menentukan format Spreadsheet, yang akan digunakan untuk menyimpan
dokumen


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Memungkinkan untuk mengaktifkan perlindungan lembar kerja untuk Spreadsheet output
dokumen. Secara default adalah NULL - perlindungan tidak diterapkan. Tidak semua format
mendukung perlindungan lembar kerja.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Memungkinkan untuk mengaktifkan perlindungan lembar kerja untuk Spreadsheet output
dokumen. Secara default adalah NULL - perlindungan tidak diterapkan. Tidak semua format
mendukung perlindungan lembar kerja.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Memungkinkan untuk menentukan array dengan nomor lembar kerja berbasis 1 yang harus dihapus dari spreadsheet saat disimpan, jika lembar kerja yang diedit dimasukkan ke dalam spreadsheet yang sudah ada. Ketika lembar kerja yang diedit disimpan bukan sebagai spreadsheet lembar kerja tunggal baru (perilaku default), melainkan disimpan ke dalam spreadsheet yang sudah ada (menggunakan #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), juga dimungkinkan untuk menghapus beberapa lembar kerja tertentu dari spreadsheet ini dengan menentukan nomor mereka dalam array ini. Secara default array ini adalah  null  \\u2014 tidak ada lembar kerja yang akan dihapus. Namun, ketika array ini tidak null dan tidak kosong, serta berisi setidaknya satu nomor lembar kerja yang valid, setelah dokumen spreadsheet output dihasilkan dengan konten lembar kerja yang diedit, lembar kerja dengan nomor yang ditentukan akan dihapus dari spreadsheet tepat sebelum menulis isinya ke aliran output atau file. Nomor lembar kerja dalam array ini berbasis 1, bukan berbasis 0. Nomor yang tidak valid (kurang dari 1 atau lebih besar dari total jumlah lembar kerja) akan diabaikan.


**Returns:**
int[] - Array nomor lembar kerja berbasis 1 untuk dihapus, atau  null  jika tidak ada yang harus dihapus.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Memungkinkan untuk menentukan array dengan nomor lembar kerja berbasis 1 yang harus dihapus dari spreadsheet saat disimpan, jika lembar kerja yang diedit dimasukkan ke dalam spreadsheet yang sudah ada. Nomor lembar kerja dalam array ini berbasis 1. Nomor yang tidak valid akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int[] | Array nomor lembar kerja berbasis 1 untuk dihapus (bisa jadi  null  atau kosong). |
|


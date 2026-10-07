---
title: "WorksheetProtection"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan opsi perlindungan lembar kerja yang memungkinkan melindungi sebuah lembar kerja dalam dokumen Spreadsheet output dari modifikasi tipe tertentu dengan kata sandi yang ditentukan."
type: docs
weight: 49
url: /id/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Mengkapsulkan opsi perlindungan lembar kerja, yang memungkinkan melindungi sebuah lembar kerja
dalam dokumen Spreadsheet output dari modifikasi tipe tertentu dengan sebuah
kata sandi yang ditentukan.


*** ** * ** ***

Sebagian besar format Spreadsheet seperti XLSX memungkinkan melindungi sebuah lembar kerja dari penyuntingan dengan kata sandi. Kelas ini memungkinkan mengaktifkan perlindungan tersebut dan menentukan opsinya.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Membuat instance baru dengan parameter default. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Membuat instance baru dengan tipe perlindungan lembar kerja yang ditentukan dan |
kata sandi
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Memungkinkan menentukan tipe perlindungan lembar kerja. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Memungkinkan menentukan tipe perlindungan lembar kerja. |
|
|  | [getPassword()](#getPassword--) | Kata sandi, yang digunakan untuk melindungi sebuah lembar kerja. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Kata sandi, yang digunakan untuk melindungi sebuah lembar kerja. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Membuat instance baru dengan parameter default. Jika tidak diubah dan diteruskan
ke SpreadsheetSaveOptions, tidak ada perlindungan lembar kerja yang akan diterapkan


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Membuat instance baru dengan tipe perlindungan lembar kerja yang ditentukan dan
kata sandi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | protectionType | int | Tipe perlindungan lembar kerja |
|
|  | kata sandi | java.lang.String | Kata sandi, yang mengunci perlindungan |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Memungkinkan menentukan tipe perlindungan lembar kerja. Secara default adalah 'None' -
perlindungan tidak diterapkan.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Memungkinkan menentukan tipe perlindungan lembar kerja. Secara default adalah 'None' -
perlindungan tidak diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi, yang digunakan untuk melindungi sebuah lembar kerja. Jika NULL atau kosong
string, perlindungan tidak akan diterapkan.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Kata sandi, yang digunakan untuk melindungi sebuah lembar kerja. Jika NULL atau kosong
string, perlindungan tidak akan diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |


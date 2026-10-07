---
title: "TtcFont"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu font dalam format TTC TrueType Collection"
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Mewakili satu font dalam format TTC (TrueType Collection).


Lihat lebih lanjut: https://docs.fileformat.com/font/ttc/

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan |
dengan nama yang ditentukan
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Ukuran header TTC (dalam byte), yang diperlukan untuk validasinya |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah font TTC yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string base64-encoded yang ditentukan adalah font TTC yang valid |
|
|  | [getType()](#getType--) | Mengembalikan FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Versi Header TTC, dapat berupa "1" atau "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Jumlah font dalam TTC ini |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Menunjukkan apakah TTC ini memiliki tabel DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font TTC. Tidak boleh null, kosong, atau spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string base64-encoded. Tidak boleh null, kosong, atau spasi. Jika bukan konten TTC, pengecualian akan dilempar. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan
dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font TTC. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Ukuran header TTC (dalam byte), yang diperlukan untuk validasinya


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah font TTC yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi sumber daya TTC |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi font TTC yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string base64-encoded yang ditentukan adalah font TTC yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten dari font TTC yang diperkirakan dalam bentuk string base64-encoded |
|

**Returns:**
boolean - True jika string yang ditentukan berisi font TTC yang valid, false jika tidak

### getType() {#getType--}
```
public FontType getType()
```


Mengembalikan FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Versi Header TTC, dapat berupa "1" atau "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Jumlah font dalam TTC ini


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Menunjukkan apakah TTC ini memiliki tabel DSIG. Tabel DSIG mungkin ada
hanya jika TTC memiliki versi Header 2.0.


**Returns:**
boolean

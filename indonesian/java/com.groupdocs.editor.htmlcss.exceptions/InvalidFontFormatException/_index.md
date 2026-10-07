---
title: "InvalidFontFormatException"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Pengecualian yang dilemparkan ketika mencoba membuka, memuat, menyimpan, atau memproses entah bagaimana konten yang seharusnya merupakan font dengan format yang didukung, tetapi sebenarnya adalah font dengan format yang tidak didukung atau tidak terduga, atau bukan font sama sekali."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Pengecualian yang dilempar ketika mencoba membuka, memuat, menyimpan, atau memproses konten dengan cara lain, yang seharusnya merupakan font dengan format yang didukung (dikenal), tetapi sebenarnya merupakan font dengan format yang tidak didukung atau tidak terduga, atau bukan font sama sekali.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Membuat instance baru dengan pesan kesalahan yang ditentukan |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Membuat instance baru dari @see \"InvalidFontFormatException\" dengan pesan kesalahan yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Membuat instance baru dengan pesan kesalahan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan teks, yang menjelaskan kesalahan, dapat bernilai null atau kosong |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Membuat instance baru dari @see \"InvalidFontFormatException\" dengan pesan kesalahan yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan teks, yang menjelaskan kesalahan, dapat bernilai null atau kosong |
|
|  | innerException | java.lang.RuntimeException | Pengecualian yang menjadi penyebab pengecualian saat ini, atau referensi null jika tidak ada inner exception yang ditentukan. |
|


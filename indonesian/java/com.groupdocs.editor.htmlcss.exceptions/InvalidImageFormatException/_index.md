---
title: "InvalidImageFormatException"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Pengecualian yang dilemparkan ketika mencoba membuka, memuat, menyimpan, atau memproses entah bagaimana konten yang seharusnya merupakan gambar raster atau vektor tetapi sebenarnya adalah gambar dengan tipe yang tidak terduga atau bukan gambar sama sekali."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Pengecualian yang dilemparkan ketika mencoba membuka, memuat, menyimpan, atau memproses
entah bagaimana konten lain, yang seharusnya merupakan gambar (raster atau vektor),
tetapi sebenarnya adalah gambar dengan tipe yang tidak terduga atau bukan gambar sama sekali.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Membuat instance baru dari InvalidImageFormatException dengan pesan kesalahan yang ditentukan |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Membuat instance baru dari InvalidImageFormatException dengan pesan kesalahan yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Membuat instance baru dari InvalidImageFormatException dengan pesan kesalahan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan teks, yang menjelaskan kesalahan, dapat bernilai null atau kosong |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Membuat instance baru dari InvalidImageFormatException dengan pesan kesalahan yang ditentukan dan referensi ke inner exception yang menjadi penyebab pengecualian ini


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan teks, yang menjelaskan kesalahan, dapat bernilai null atau kosong |
|
|  | innerException | java.lang.RuntimeException | Pengecualian yang menjadi penyebab pengecualian saat ini, atau referensi null jika tidak ada inner exception yang ditentukan. |
|


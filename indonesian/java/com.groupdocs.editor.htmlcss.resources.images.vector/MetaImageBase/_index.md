---
title: "MetaImageBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas abstrak dasar untuk format gambar WMF dan EMF"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Kelas abstrak dasar untuk format gambar WMF dan EMF

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Konstruktor umum, yang menyiapkan pembuatan instance WMF atau EMF dari |
string yang di-encode base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Konstruktor umum, yang menyiapkan pembuatan instance WMF atau EMF dari |
aliran byte
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Menentukan apakah aliran byte yang ditentukan berisi gambar WMF yang valid |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Menentukan apakah string yang ditentukan berisi gambar WMF yang valid, yang merupakan |
di-encode dengan base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Menentukan apakah aliran byte yang ditentukan berisi gambar EMF yang valid |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Menentukan apakah string yang ditentukan berisi gambar EMF yang valid, yang merupakan |
di-encode dengan base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Dalam implementasi, tipe harus menyimpan meta-gambar vektor saat ini ke |
format SVG vektor ke aliran byte yang ditentukan
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Konstruktor umum, yang menyiapkan pembuatan instance WMF atau EMF dari
string yang di-encode base64


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama wajib |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string base64. Tidak boleh NULL atau kosong. |
|
|  | isWmf | boolean | true untuk WMF, false untuk EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Konstruktor umum, yang menyiapkan pembuatan instance WMF atau EMF dari
aliran byte


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama wajib |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Harus valid. |
|
|  | isWmf | boolean | true untuk WMF, false untuk EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Menentukan apakah aliran byte yang ditentukan berisi gambar WMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte input. Harus valid. |
|

**Returns:**
boolean - Mengembalikan 'true' jika valid dan 'false' jika tidak valid

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Menentukan apakah string yang ditentukan berisi gambar WMF yang valid, yang merupakan
di-encode dengan base64


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, yang diasumsikan berisi gambar WMF yang dienkode base64 |
|

**Returns:**
boolean - Mengembalikan 'true' jika valid dan 'false' jika tidak valid

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Menentukan apakah aliran byte yang ditentukan berisi gambar EMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte input. Harus valid. |
|

**Returns:**
boolean - Mengembalikan 'true' jika valid dan 'false' jika tidak valid

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Menentukan apakah string yang ditentukan berisi gambar EMF yang valid, yang merupakan
di-encode dengan base64


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, yang diasumsikan berisi gambar EMF yang dienkode base64 |
|

**Returns:**
boolean - Mengembalikan 'true' jika valid dan 'false' jika tidak valid

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Dalam implementasi, tipe harus menyimpan meta-gambar vektor saat ini ke
format SVG vektor ke aliran byte yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Aliran byte, ke dalamnya versi SVG dari meta-gambar vektor ini akan disimpan. Tidak boleh NULL dan harus mendukung penulisan. |
|


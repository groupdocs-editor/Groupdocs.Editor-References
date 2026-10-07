---
title: "FontResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas dasar untuk setiap tipe font yang didukung sebagai sumber daya untuk dokumen HTML dengan semua propertinya"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Kelas dasar untuk setiap tipe font yang didukung sebagai sumber daya untuk dokumen HTML
dengan semua propertinya

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Disposed](#Disposed) | Peristiwa, yang terjadi ketika font ini dibuang |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mengembalikan nama sumber daya font ini. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Mengembalikan nama file yang benar dari sumber daya font ini, yang terdiri dari nama |
dan ekstensi.
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten font ini sebagai aliran byte |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten font ini sebagai string yang di-encode base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan font ini ke file yang ditentukan |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Memeriksa instance ini dengan sumber daya HTML yang ditentukan pada kesetaraan referensi |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Memeriksa instance ini dengan sumber daya font yang ditentukan pada kesetaraan referensi |
|
|  | [dispose()](#dispose--) | Membuang sumber daya font ini, membuang kontennya dan membuat sebagian besar |
metode dan properti tidak berfungsi
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah font ini telah dibuang atau tidak |
|
|  | [getType()](#getType--) | Dalam implementasi, tipe harus mengembalikan informasi tentang tipe spesifik |
sumber daya font sebagai instance dari tipe FontType spesifik, yang
mengenkapsulasi semua info spesifik tipe
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Peristiwa, yang terjadi ketika font ini dibuang


### getName() {#getName--}
```
public final String getName()
```


Mengembalikan nama sumber daya font ini. Biasanya tidak mengandung nama file
ekstensi dan secara teoritis dapat berbeda dari nama file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Mengembalikan nama file yang benar dari sumber daya font ini, yang terdiri dari nama
dan ekstensi. Secara teoritis dapat berbeda dari nama.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Mengembalikan konten font ini sebagai aliran byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Mengembalikan konten font ini sebagai string yang di-encode base64. Nilai ini adalah
disimpan setelah pemanggilan pertama.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Menyimpan font ini ke file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat atau ditulis ulang |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Memeriksa instance ini dengan sumber daya HTML yang ditentukan pada kesetaraan referensi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Pewarisan lain dari antarmuka IHtmlResource |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Memeriksa instance ini dengan sumber daya font yang ditentukan pada kesetaraan referensi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Pewarisan lain dari kelas abstrak FontResourceBase |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang sumber daya font ini, membuang kontennya dan membuat sebagian besar
metode dan properti tidak berfungsi


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Menentukan apakah font ini telah dibuang atau tidak


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Dalam implementasi, tipe harus mengembalikan informasi tentang tipe spesifik
sumber daya font sebagai instance dari tipe FontType spesifik, yang
mengenkapsulasi semua info spesifik tipe


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

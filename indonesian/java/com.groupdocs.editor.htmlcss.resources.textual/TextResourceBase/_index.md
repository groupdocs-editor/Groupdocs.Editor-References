---
title: "TextResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas dasar untuk setiap sumber daya teks yang didukung dengan konten teks dan enkoding."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Kelas dasar untuk setiap sumber daya teks yang didukung dengan konten teks dan enkoding.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Membuat sumber teks baru dari konten tekstual yang ditentukan dengan enkoding |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Membuat sumber teks baru dari aliran byte yang ditentukan dan enkoding |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mengembalikan nama sumber teks ini tanpa ekstensi file |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Mengembalikan nama file yang benar dari sumber teks ini, yang terdiri dari nama |
dan ekstensi
|
|  | [getEncoding()](#getEncoding--) | Mengembalikan enkoding dari sumber tekstual ini. |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten dari sumber teks ini sebagai aliran byte dengan asli |
enkoding
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten dari sumber teks ini sebagai string standar |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan sumber teks ini ke file yang ditentukan |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Memeriksa instance ini dengan yang ditentukan untuk kesetaraan. |
|
|  | [dispose()](#dispose--) | Membuang sumber teks ini, membuang kontennya dan membuat sebagian besar |
metode dan properti tidak berfungsi.
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah sumber teks ini telah dibuang atau tidak |
|
|  | [getType()](#getType--) | Dalam tipe implementasi harus mengembalikan informasi tentang tipe teks |
sumber
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Membuat sumber teks baru dari konten tekstual yang ditentukan dengan enkoding


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama wajib dari sumber, yang berfungsi sebagai pengidentifikasi uniknya. Biasanya adalah nama file. |
|
|  | textualContent | java.lang.String | Konten tekstual dari sumber, tidak boleh NULL atau kosong |
|
|  | originalEncoding | java.nio.charset.Charset | Enkoding asli dari sumber, tidak boleh NULL atau kosong |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Membuat sumber teks baru dari aliran byte yang ditentukan dan enkoding


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama wajib dari sumber, yang berfungsi sebagai pengidentifikasi uniknya. Biasanya adalah nama file. |
|
|  | binaryContent | java.io.InputStream | Konten biner dari sebuah sumber sebagai aliran byte. Tidak boleh NULL, dibuang, harus dapat dibaca dan dapat dipindahkan. |
|
|  | originalEncoding | java.nio.charset.Charset | Enkoding asli dari sumber, tidak boleh NULL atau kosong |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Mengembalikan nama sumber teks ini tanpa ekstensi file


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Mengembalikan nama file yang benar dari sumber teks ini, yang terdiri dari nama
dan ekstensi


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Mengembalikan enkoding dari sumber tekstual ini. Biasanya mengembalikan UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Mengembalikan konten dari sumber teks ini sebagai aliran byte dengan asli
enkoding


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Mengembalikan konten dari sumber teks ini sebagai string standar


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Menyimpan sumber teks ini ke file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat atau ditulis ulang jika sudah ada |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Memeriksa instance ini dengan yang ditentukan untuk kesetaraan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Sumber HTML lain dengan tipe tidak diketahui, yang juga kemungkinan merupakan pewaris TextResourceBase |
|

**Returns:**
boolean - Mengembalikan true jika sama, atau false jika tidak sama

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang sumber teks ini, membuang kontennya dan membuat sebagian besar
metode dan properti tidak berfungsi. Toleran terhadap panggilan berulang.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Menentukan apakah sumber teks ini telah dibuang atau tidak


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Dalam tipe implementasi harus mengembalikan informasi tentang tipe teks
sumber


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)

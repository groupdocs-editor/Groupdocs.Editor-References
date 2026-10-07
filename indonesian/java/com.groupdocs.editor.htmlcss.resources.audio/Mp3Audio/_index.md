---
title: "Mp3Audio"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu sumber daya audio dengan format apa pun."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Mewakili satu sumber daya audio dengan format apa pun.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Membuat kelas Mp3Audio baru dari konten MP3, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Memeriksa apakah aliran yang ditentukan merupakan konten MP3 yang valid |
|
|  | [getName()](#getName--) | Mengembalikan nama konten MP3 ini. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Mengembalikan nama file yang benar untuk konten MP3 ini, yang terdiri dari nama dan ekstensi. |
|
|  | [getType()](#getType--) | Mengembalikan AudioFormat.Mp3 (juga memenuhi IHtmlResource.getFormat() melalui pengembalian kovarian) |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten font ini sebagai aliran byte |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | Mengembalikan konten sumber daya audio MP3 ini sebagai aliran byte dengan posisi asli |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten sumber daya MP3 ini sebagai string yang dienkode base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan sumber daya MP3 ini ke file yang ditentukan |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Memeriksa instance ini dengan sumber daya HTML yang ditentukan pada kesetaraan referensi |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Memeriksa instance ini dengan sumber daya font yang ditentukan pada kesetaraan referensi |
|
|  | [dispose()](#dispose--) | Membuang sumber daya MP3 ini, membuang isinya dan membuat sebagian besar metode serta properti tidak berfungsi |
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah konten MP3 ini telah dibuang atau tidak |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Membuat kelas Mp3Audio baru dari konten MP3, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama konten MP3. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|
|  | leaveOpen | boolean | Menentukan apakah harus membuang aliran yang ditentukan saat instance Mp3Audio dibuang atau tidak |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Memeriksa apakah aliran yang ditentukan merupakan konten MP3 yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | Aliran byte, yang kemungkinan berisi konten MP3 |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi konten MP3 yang valid, false jika tidak

### getName() {#getName--}
```
public String getName()
```


Mengembalikan nama konten MP3 ini. Biasanya tidak menyertakan ekstensi nama file dan secara teoritis dapat berbeda dari nama file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Mengembalikan nama file yang tepat untuk konten MP3 ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Mengembalikan AudioFormat.Mp3 (juga memenuhi IHtmlResource.getFormat() melalui pengembalian kovarian)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Mengembalikan konten font ini sebagai aliran byte


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Mengembalikan konten sumber daya audio MP3 ini sebagai aliran byte dengan posisi asli


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Mengembalikan konten sumber daya MP3 ini sebagai string yang di-encode base64. Nilai ini di-cache setelah pemanggilan pertama.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Menyimpan sumber daya MP3 ini ke file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat atau ditulis ulang |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Memeriksa instance ini dengan sumber daya HTML yang ditentukan pada kesetaraan referensi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Pewarisan lain dari antarmuka IHtmlResource |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Memeriksa instance ini dengan sumber daya font yang ditentukan pada kesetaraan referensi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Instance lain dari kelas Mp3Audio |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### dispose() {#dispose--}
```
public void dispose()
```


Membuang sumber daya MP3 ini, membuang isinya dan membuat sebagian besar metode serta properti tidak berfungsi


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Menentukan apakah konten MP3 ini telah dibuang atau tidak


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |


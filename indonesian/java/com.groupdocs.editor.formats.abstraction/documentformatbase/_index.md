---
title: "DocumentFormatBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili kelas dasar untuk format dokumen yang menyediakan fungsionalitas umum bagi instance format."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Mewakili kelas dasar untuk format dokumen, menyediakan fungsionalitas umum untuk instance format.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMime()](#getMime--) | Mendapatkan tipe MIME dari format dokumen. |
|
|  | [getExtension()](#getExtension--) | Mendapatkan ekstensi file dari format dokumen. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Mendapatkan keluarga format tempat format dokumen termasuk. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan |
T
yang memiliki tipe MIME yang ditentukan.
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk objek saat ini. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Menentukan apakah instance ini sama dengan instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Mengonversi sebuah instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) menjadi string secara implisit. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Mendapatkan tipe MIME dari format dokumen.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Mendapatkan ekstensi file dari format dokumen.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Mendapatkan keluarga format tempat format dokumen termasuk.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Mengambil sebuah instance dari tipe yang ditentukan
T
yang memiliki tipe MIME yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Tipe MIME dari format dokumen. |


T
: Tipe format dokumen.
|

**Returns:**
T - Sebuah instance dari tipe yang ditentukan  T  dengan tipe MIME yang ditentukan.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk objek saat ini.


**Returns:**
int - Kode hash untuk objek saat ini, menggabungkan kode hash dari objek dasar, tipe MIME, ekstensi file, dan keluarga format.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Menentukan apakah instance ini sama dengan instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Instance [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) untuk dibandingkan dengan instance saat ini. |
|

**Returns:**
boolean -  true  jika [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan sama dengan instance saat ini; jika tidak,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) untuk dibandingkan dengan instance saat ini. |
|

**Returns:**
boolean -  true  jika [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan sama dengan instance saat ini; jika tidak,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Mengonversi sebuah instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) menjadi string secara implisit.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) untuk dikonversi. |
|

**Returns:**
java.lang.String - Ekstensi file dari instance [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).


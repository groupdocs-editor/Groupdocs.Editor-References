---
title: "AudioType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu format tipe audio yang didukung"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Mewakili satu tipe audio yang didukung (format).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Nama resmi format audio ini |
|
|  | [getFileExtension()](#getFileExtension--) | Ekstensi nama file (tanpa karakter titik) untuk format audio ini |
|
|  | [getMimeCode()](#getMimeCode--) | Kode MIME untuk format audio ini |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Menentukan apakah instance ini sama dengan instance "AudioType" yang ditentukan |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, yang kemungkinan merupakan instance "AudioType" lain |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Memeriksa apakah dua nilai "AudioType" sama |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Memeriksa apakah dua nilai "AudioType" tidak sama |
|
|  | [hashCode()](#hashCode--) | Mengembalikan hash-code, yang merupakan angka konstan untuk tipe nilai spesifik ini |
|
|  | [getUndefined()](#getUndefined--) | Nilai khusus, yang menandai format audio yang tidak terdefinisi, tidak diketahui, atau tidak didukung |
|
|  | [getMp3()](#getMp3--) | Mewakili format audio MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Mengembalikan nilai AudioType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Nama resmi format audio ini


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Ekstensi nama file (tanpa karakter titik) untuk format audio ini


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Kode MIME untuk format audio ini


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Menentukan apakah instance ini sama dengan instance "AudioType" yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Instance AudioType lain untuk diperiksa dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, yang kemungkinan merupakan instance "AudioType" lain


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance lain yang kemungkinan merupakan struct AudioType, yang dibungkus menjadi System.Object |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Memeriksa apakah dua nilai "AudioType" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType pertama untuk diperiksa |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Memeriksa apakah dua nilai "AudioType" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType pertama untuk diperiksa |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hash-code, yang merupakan angka konstan untuk tipe nilai spesifik ini


**Returns:**
int - integer bertanda 4-byte, 0 untuk nilai Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Nilai khusus, yang menandai format audio yang tidak terdefinisi, tidak diketahui, atau tidak didukung


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Mewakili format audio MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Mengembalikan nilai AudioType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama file | java.lang.String | Nama file arbitrer, dapat berupa jalur relatif atau jalur lengkap |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.


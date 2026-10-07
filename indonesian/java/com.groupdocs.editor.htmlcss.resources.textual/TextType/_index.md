---
title: "TextType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu tipe sumber daya tekstual yang dapat didukung"
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Mewakili satu tipe sumber daya tekstual yang dapat didukung

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextType()](#TextType--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Nilai khusus, yang menandai teks yang tidak terdefinisi, tidak diketahui, atau tidak didukung |
sumber
|
|  | [getCss()](#getCss--) | Tipe CSS dari sumber teks |
|
|  | [getXml()](#getXml--) | Tipe XML dari sumber teks |
|
|  | [getFormalName()](#getFormalName--) | Mengembalikan nama formal dari tipe sumber teks ini |
|
|  | [getFileExtension()](#getFileExtension--) | Ekstensi file (tanpa karakter titik di depan) dari teks tertentu |
sumber
|
|  | [getMimeCode()](#getMimeCode--) | Kode MIME dari tipe sumber teks tertentu |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Menentukan apakah instance ini sama dengan "TextType" yang ditentukan |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, |
yang kemungkinan merupakan instance "TextType" lain
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Mendefinisikan apakah dua instance "TextType" tertentu sama |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Mendefinisikan apakah dua instance "TextType" tertentu tidak sama |
|
|  | [hashCode()](#hashCode--) | Mengembalikan hash-code, yang merupakan angka konstan untuk nilai spesifik ini |
type
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Mengembalikan nilai TextType, yang merupakan ekivalen ekstensi nama file, yang diekstrak dari nama file yang ditentukan dengan ekstensi atau ekstensi murni |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Nilai khusus, yang menandai teks yang tidak terdefinisi, tidak diketahui, atau tidak didukung
sumber


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Tipe CSS dari sumber teks


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Tipe XML dari sumber teks


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Mengembalikan nama formal dari tipe sumber teks ini


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Ekstensi file (tanpa karakter titik di depan) dari teks tertentu
sumber


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Kode MIME dari tipe sumber teks tertentu


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Menentukan apakah instance ini sama dengan "TextType" yang ditentukan
instance


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Instance TextType lain, yang harus dibandingkan dengan ini untuk kesetaraan |
|

**Returns:**
boolean - Mengembalikan true jika sama atau false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik,
yang kemungkinan merupakan instance "TextType" lain


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance TextType lain, yang dibungkus menjadi objek |
|

**Returns:**
boolean - Mengembalikan true jika sama atau false jika tidak sama

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Mendefinisikan apakah dua instance "TextType" tertentu sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Instance TextType pertama |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Instance TextType kedua |
|

**Returns:**
boolean - Mengembalikan true jika sama atau false jika tidak sama

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Mendefinisikan apakah dua instance "TextType" tertentu tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Instance TextType pertama |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Instance TextType kedua |
|

**Returns:**
boolean - Mengembalikan true jika tidak sama atau false jika sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hash-code, yang merupakan angka konstan untuk nilai spesifik ini
type


**Returns:**
int - Bilangan bulat bertanda 4-byte. Mengembalikan 0 jika instance ini memiliki nilai default.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Mengembalikan nilai TextType, yang merupakan ekivalen ekstensi nama file, yang diekstrak dari nama file yang ditentukan dengan ekstensi atau ekstensi murni


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama file | java.lang.String | Nama file dengan ekstensi, dapat berupa jalur relatif atau absolut, atau hanya ekstensi saja |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure


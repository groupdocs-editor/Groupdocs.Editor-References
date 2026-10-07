---
title: "FontType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu tipe font yang dapat didukung."
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Mewakili satu tipe font yang dapat didukung.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontType()](#FontType--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Nilai khusus, yang menandai font tidak terdefinisi, tidak dikenal, atau tidak didukung |
sumber
|
|  | [getWoff()](#getWoff--) | Mewakili tipe font WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Mewakili tipe font WOFF2 (Web Open Font Format versi 2) |
|
|  | [getTtf()](#getTtf--) | Mewakili tipe font TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Mewakili tipe font OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Mewakili font TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Mewakili tipe font EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Mengembalikan nama yang kompatibel dengan CSS untuk tipe font ini, yang digunakan dalam |
|
|  | [getFormalName()](#getFormalName--) | Mengembalikan nama formal untuk tipe font ini |
|
|  | [getFileExtension()](#getFileExtension--) | Ekstensi nama file (tanpa karakter titik) untuk tipe font ini |
|
|  | [getFontFormat()](#getFontFormat--) | Format font untuk format @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Kode MIME untuk tipe font tertentu |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Mengembalikan nilai FontType, yang setara dengan CSS-compatible yang ditentukan |
nama tipe font
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Mengembalikan nilai FontType, yang setara dengan ekstensi nama file, yang |
diambil dari nama file yang ditentukan
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Mengembalikan nilai FontType, yang setara dengan kode MIME yang ditentukan |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Mengembalikan tipe font pertama dari set yang ditentukan, yang bukan \"Undefined\" |
nilai, atau tipe font \"Undefined\" jika tidak (ketika semua item
\"Undefined\")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Menentukan apakah instance ini sama dengan \"FontType\" yang ditentukan |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, |
yang kemungkinan merupakan instance \"FontType\" lain
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Memeriksa apakah dua nilai \"FontType\" sama |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Memeriksa apakah dua nilai \"FontType\" tidak sama |
|
|  | [hashCode()](#hashCode--) | Mengembalikan hash-code, yang merupakan angka konstan untuk nilai spesifik ini |
type
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Nilai khusus, yang menandai font tidak terdefinisi, tidak dikenal, atau tidak didukung
sumber


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Mewakili tipe font WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Mewakili tipe font WOFF2 (Web Open Font Format versi 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Mewakili tipe font TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Mewakili tipe font OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Mewakili font TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Mewakili tipe font EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Mengembalikan nama yang kompatibel dengan CSS untuk tipe font ini, yang digunakan dalam


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Mengembalikan nama formal untuk tipe font ini


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Ekstensi nama file (tanpa karakter titik) untuk tipe font ini


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Format font untuk format @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Kode MIME untuk tipe font tertentu


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Mengembalikan nilai FontType, yang setara dengan CSS-compatible yang ditentukan
nama tipe font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama yang kompatibel dengan CSS dari tipe font |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Mengembalikan nilai FontType, yang setara dengan ekstensi nama file, yang
diambil dari nama file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama file | java.lang.String | Nama file dengan ekstensi, mungkin berupa nama lengkap |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Mengembalikan nilai FontType, yang setara dengan kode MIME yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Kode-MIME |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Mengembalikan tipe font pertama dari set yang ditentukan, yang bukan \"Undefined\"
nilai, atau tipe font \"Undefined\" jika tidak (ketika semua item
\"Undefined\")


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Satu atau lebih nilai FontType, NULL atau koleksi kosong tidak diizinkan |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Menentukan apakah instance ini sama dengan \"FontType\" yang ditentukan
instance


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Instance FontType lain untuk diperiksa dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik,
yang kemungkinan merupakan instance \"FontType\" lain


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance lain yang kemungkinan merupakan struct FontType, yang dibungkus menjadi System.Object |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Memeriksa apakah dua nilai \"FontType\" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | FontType pertama untuk diperiksa |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | FontType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Memeriksa apakah dua nilai \"FontType\" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | FontType pertama untuk diperiksa |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | FontType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hash-code, yang merupakan angka konstan untuk nilai spesifik ini
type


**Returns:**
int - integer bertanda 4-byte, 0 untuk nilai Undefined


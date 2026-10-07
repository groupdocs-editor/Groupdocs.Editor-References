---
title: "WebFont"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili pengaturan font untuk web."
type: docs
weight: 43
url: /id/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Mewakili pengaturan font untuk web.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getColor()](#getColor--) | Warna font dalam format ARGB32 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Warna font dalam format ARGB32 |
|
|  | [getWeight()](#getWeight--) | Mengatur berat (atau ketebalan) font |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Mengatur berat (atau ketebalan) font |
|
|  | [getStyle()](#getStyle--) | Mengatur apakah sebuah font harus diberi gaya normal, miring, atau miring condong dari font-family-nya. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Mengatur apakah sebuah font harus diberi gaya normal, miring, atau miring condong dari font-family-nya. |
|
|  | [getLine()](#getLine--) | Mengatur satu baris atau kombinasi baris, yang diterapkan pada teks |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Mengatur satu baris atau kombinasi baris, yang diterapkan pada teks |
|
|  | [getSize()](#getSize--) | Mengatur ukuran font dalam satuan absolut atau relatif |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Mengatur ukuran font dalam satuan absolut atau relatif |
|
|  | [getName()](#getName--) | Mengatur nama font. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Mengatur nama font. |
|
|  | [deepClone()](#deepClone--) | Membuat dan mengembalikan salinan mendalam penuh dari instance [WebFont](../../com.groupdocs.editor.options/webfont) ini |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Menentukan apakah instance WebFont ini sama dengan yang ditentukan |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance WebFont ini sama dengan objek tidak tercast yang ditentukan |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Warna font dalam format ARGB32


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Warna font dalam format ARGB32


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Mengatur berat (atau ketebalan) font


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Mengatur berat (atau ketebalan) font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Mengatur apakah sebuah font harus diberi gaya normal, miring, atau miring condong dari font-family-nya.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Mengatur apakah sebuah font harus diberi gaya normal, miring, atau miring condong dari font-family-nya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Mengatur satu baris atau kombinasi baris, yang diterapkan pada teks


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Mengatur satu baris atau kombinasi baris, yang diterapkan pada teks


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Mengatur ukuran font dalam satuan absolut atau relatif


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Mengatur ukuran font dalam satuan absolut atau relatif


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Mengatur nama font. Jika tidak ditentukan, font default akan digunakan


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mengatur nama font. Jika tidak ditentukan, font default akan digunakan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Membuat dan mengembalikan salinan mendalam penuh dari instance [WebFont](../../com.groupdocs.editor.options/webfont) ini


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Menentukan apakah instance WebFont ini sama dengan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | WebFont lain untuk memeriksa kesetaraan, dapat berupa NULL |
|

**Returns:**
boolean - true jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance WebFont ini sama dengan objek tidak tercast yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Object, yang diharapkan menjadi instance [WebFont](../../com.groupdocs.editor.options/webfont) |
|

**Returns:**
boolean - true jika sama, false jika tidak sama


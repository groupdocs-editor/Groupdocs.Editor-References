---
title: "ArgbColor"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu nilai warna dalam format ARGB dengan konverter dan serializer."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Mewakili satu nilai warna dalam format ARGB dengan konverter dan serializer.

<br />

*** ** * ** ***

Tipe ini dirancang agar berguna untuk (tetapi tidak terbatas pada) operasi CSS. Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari saluran Merah, Hijau, Biru, dan Alfa yang ditentukan |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari saluran Merah, Hijau, Biru yang ditentukan, sementara saluran Alfa sepenuhnya tidak transparan |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Membuat warna yang sepenuhnya tidak transparan (A=255) dari satu nilai, yang akan diterapkan ke semua saluran |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) yang ditentukan |
|
|  | [getValue()](#getValue--) | Mendapatkan nilai Int32 dari warna. |
|
|  | [getA()](#getA--) | Mendapatkan bagian alfa dari warna. |
|
|  | [getAlpha()](#getAlpha--) | Mendapatkan bagian alfa dari warna dalam persentase (0..1). |
|
|  | [getR()](#getR--) | Mendapatkan bagian merah dari warna. |
|
|  | [getG()](#getG--) | Mendapatkan bagian hijau dari warna. |
|
|  | [getB()](#getB--) | Mendapatkan bagian biru dari warna. |
|
|  | [isEmpty()](#isEmpty--) | Warna yang belum diinisialisasi - semua 4 saluran diatur ke 0. |
|
|  | [isDefault()](#isDefault--) | Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini adalah default (Transparent) - semua 4 saluran diatur ke 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini sepenuhnya transparan - saluran Alfa-nya memiliki nilai minimum (0), sehingga saluran R, G, dan B lainnya tidak memberikan efek yang terlihat. |
|
|  | [isTranslucent()](#isTranslucent--) | Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini tembus pandang (tidak sepenuhnya transparan, tetapi juga tidak sepenuhnya opak) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini sepenuhnya opak, tanpa transparansi (saluran Alfa-nya memiliki nilai maksimum) |
|
|  | [toSystemColor()](#toSystemColor--) | Mengonversi nilai instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke instance [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) dan mengembalikannya |
|
|  | [toRGBA()](#toRGBA--) | Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS yang paling tepat tergantung pada tingkat tembus pandang |
|
|  | [toString()](#toString--) | Sama dengan #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak cocok. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Memeriksa dua warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) untuk kesetaraan |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Memeriksa dua warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) untuk kesetaraan |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Menguji apakah objek lain sama dengan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini. |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash yang mendefinisikan warna saat ini. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari saluran Merah, Hijau, Biru, dan Alfa yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | merah | int | Nilai saluran Merah |
|
|  | hijau | int | Nilai saluran Hijau |
|
|  | biru | int | Nilai saluran Biru |
|
|  | alpha | int | Nilai saluran Alpha |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari saluran Merah, Hijau, Biru yang ditentukan, sementara saluran Alfa sepenuhnya tidak transparan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | merah | int | Nilai saluran Merah |
|
|  | hijau | int | Nilai saluran Hijau |
|
|  | biru | int | Nilai saluran Biru |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Membuat warna yang sepenuhnya tidak transparan (A=255) dari satu nilai, yang akan diterapkan ke semua saluran


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | byte | Nilai byte, sama untuk saluran Merah, Hijau, dan Biru |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Membuat satu nilai [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) dari [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warna | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Mendapatkan nilai Int32 dari warna.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Mendapatkan bagian alfa dari warna.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Mendapatkan bagian alfa dari warna dalam persentase (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Mendapatkan bagian merah dari warna.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Mendapatkan bagian hijau dari warna.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Mendapatkan bagian biru dari warna.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Warna yang belum diinisialisasi - semua 4 saluran diatur ke 0. Sama dengan Default dan Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini adalah default (Transparent) - semua 4 saluran diatur ke 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini sepenuhnya transparan - saluran Alfa-nya memiliki nilai minimum (0), sehingga saluran R, G, dan B lainnya tidak memberikan efek yang terlihat.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini tembus pandang (tidak sepenuhnya transparan, tetapi juga tidak sepenuhnya opak)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Menunjukkan apakah instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini sepenuhnya opak, tanpa transparansi (saluran Alfa-nya memiliki nilai maksimum)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Mengonversi nilai instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke instance [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) dan mengembalikannya


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS 'rgba'


**Returns:**
java.lang.String - String dengan format 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS 'rgb'


**Returns:**
java.lang.String - String dengan format 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Menyerialkan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini ke notasi fungsi CSS yang paling tepat tergantung pada tingkat tembus pandang


**Returns:**
java.lang.String - String dengan format 'rgba(r, g, b, a)' atau 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Sama dengan #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Nilai kembali yang sama seperti di #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Warna pertama yang akan digunakan. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Warna kedua yang akan digunakan. |
|

**Returns:**
boolean - True jika kedua warna sama, jika tidak false.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak cocok.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Warna pertama yang akan digunakan. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Warna kedua yang akan digunakan. |
|

**Returns:**
boolean - True jika kedua warna tidak sama, jika tidak false.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Memeriksa dua warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) untuk kesetaraan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) lainnya |
|

**Returns:**
boolean - True jika kedua warna sama, jika tidak false.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Memeriksa dua warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) untuk kesetaraan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Warna [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) lainnya, di-cast ke ICssDataType |
|

**Returns:**
boolean - True jika kedua warna sama, jika tidak false.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Menguji apakah objek lain sama dengan instance [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | lainnya | java.lang.Object | Objek yang akan diuji. |
|

**Returns:**
boolean - True jika kedua objek sama, jika tidak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash yang mendefinisikan warna saat ini.


**Returns:**
int - Nilai integer dari hashcode.


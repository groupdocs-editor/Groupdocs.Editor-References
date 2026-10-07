---
title: "FormatFamilyBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili kelas dasar untuk keluarga format yang menyediakan fungsionalitas umum bagi instance keluarga format."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Mewakili kelas dasar untuk keluarga format, menyediakan fungsionalitas umum untuk instance keluarga format.

<br />

*** ** * ** ***

Kelas ini bersifat abstrak dan harus diwarisi oleh kelas turunan yang menentukan detail keluarga format yang sebenarnya.

<br />


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getId()](#getId--) | Mendapatkan pengidentifikasi unik untuk keluarga format. |
|
|  | [getName()](#getName--) | Mendapatkan nama keluarga format. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Menentukan apakah instance ini sama dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
|
|  | [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Mengambil semua instance dari tipe yang ditentukan |
T
yang diturunkan dari [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk objek saat ini. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Mengambil sebuah instance dari tipe yang ditentukan |
T
yang memiliki pengidentifikasi yang ditentukan.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan |
T
yang memiliki nama yang ditentukan.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Menentukan apakah dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Menentukan apakah dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Menentukan apakah sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama dengan nama string yang ditentukan. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Menentukan apakah sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama dengan nama string yang ditentukan. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Mengonversi sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) menjadi integer secara implisit. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Mengonversi sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) menjadi string secara implisit. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Mengonversi string yang mewakili nama keluarga format menjadi objek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Mengonversi integer yang mewakili ID keluarga format menjadi objek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Mendapatkan pengidentifikasi unik untuk keluarga format.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama keluarga format.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Menentukan apakah instance ini sama dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan dengan instance saat ini. |
|

**Returns:**
boolean - true jika [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan sama dengan instance saat ini; jika tidak, false.

### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.


**Returns:**
java.lang.String - String yang mewakili objek saat ini, yaitu nilai properti Name.

<br />

*** ** * ** ***

Metode ini menggantikan object.ToString untuk mengembalikan properti Name dari objek.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Mengambil semua instance dari tipe yang ditentukan
T
yang diturunkan dari [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Koleksi yang dapat diiterasi berisi instance dari tipe T yang ditentukan.


T
: Tipe keluarga format.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan dengan instance saat ini. |
|

**Returns:**
boolean - true jika [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan sama dengan instance saat ini; jika tidak, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk objek saat ini.


**Returns:**
int - Kode hash untuk objek saat ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

<br />

*** ** * ** ***

Metode ini menggantikan object.GetHashCode. Kode hash dihitung menggunakan properti Id dan Name objek. Konteks unchecked memungkinkan overflow, yang dapat diterima dalam konteks perhitungan kode hash.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Mengambil sebuah instance dari tipe yang ditentukan
T
yang memiliki pengidentifikasi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | nilai | int | Pengidentifikasi keluarga format. |


T
: Tipe keluarga format.
|

**Returns:**
T - Sebuah instance dari tipe T yang ditentukan dengan pengidentifikasi yang ditentukan.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Mengambil sebuah instance dari tipe yang ditentukan
T
yang memiliki nama yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | nama | java.lang.String | Nama keluarga format. |


T
: Tipe keluarga format.
|

**Returns:**
T - Sebuah instance dari tipe T yang ditentukan dengan nama yang ditentukan.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Menentukan apakah dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance pertama [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance kedua [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|

**Returns:**
boolean - true jika dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama; jika tidak, false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Menentukan apakah dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance pertama [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance kedua [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|

**Returns:**
boolean - true jika dua instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama; jika tidak, false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Menentukan apakah sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama dengan nama string yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|
|  | name | java.lang.String | Nama string untuk dibandingkan dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true jika nama instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sama dengan nama string yang ditentukan; jika tidak, false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Menentukan apakah sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama dengan nama string yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dibandingkan. |
|
|  | name | java.lang.String | Nama string untuk dibandingkan dengan instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true jika nama instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) tidak sama dengan nama string yang ditentukan; jika tidak, false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Mengonversi sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) menjadi integer secara implisit.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dikonversi. |
|

**Returns:**
int - Pengidentifikasi unik dari instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Mengonversi sebuah instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) menjadi string secara implisit.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) untuk dikonversi. |
|

**Returns:**
java.lang.String - Nama dari instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Mengonversi string yang mewakili nama keluarga format menjadi objek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | keluarga | java.lang.String | Nama keluarga format yang akan dikonversi. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Mengonversi integer yang mewakili ID keluarga format menjadi objek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | id | int | ID keluarga format yang akan dikonversi. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.


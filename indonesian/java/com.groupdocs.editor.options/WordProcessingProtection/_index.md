---
title: "WordProcessingProtection"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan opsi perlindungan dokumen untuk dokumen WordProcessing yang dihasilkan dari HTML"
type: docs
weight: 46
url: /id/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Mengkapsulkan opsi perlindungan dokumen untuk dokumen WordProcessing,
yang dihasilkan dari HTML

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Konstruktor tanpa parameter - semua parameter memiliki nilai default |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Memungkinkan mengatur semua parameter selama instansiasi kelas |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Memungkinkan mengatur tipe perlindungan dokumen. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Memungkinkan mengatur tipe perlindungan dokumen. |
|
|  | [getPassword()](#getPassword--) | Kata sandi untuk melindungi dokumen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Kata sandi untuk melindungi dokumen. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Konstruktor tanpa parameter - semua parameter memiliki nilai default


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Memungkinkan mengatur semua parameter selama instansiasi kelas


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | protectionType | int | Atur jenis perlindungan dokumen |
|
|  | kata sandi | java.lang.String | Atur kata sandi perlindungan |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Mengizinkan penetapan jenis perlindungan dokumen. Secara default diatur menjadi tidak
melindungi dokumen sama sekali.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Mengizinkan penetapan jenis perlindungan dokumen. Secara default diatur menjadi tidak
melindungi dokumen sama sekali.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi untuk melindungi dokumen. Jika null atau string kosong -
perlindungan tidak akan diterapkan pada dokumen.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Kata sandi untuk melindungi dokumen. Jika null atau string kosong -
perlindungan tidak akan diterapkan pada dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int

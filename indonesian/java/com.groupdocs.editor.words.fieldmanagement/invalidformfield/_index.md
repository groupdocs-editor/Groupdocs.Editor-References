---
title: "InvalidFormField"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili pembaruan nama bidang formulir yang tidak valid selama operasi FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /id/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Mewakili pembaruan nama bidang formulir yang tidak valid selama
FormFieldManager.FixInvalidFormFieldNames
operasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) dengan nama yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mendapatkan nama asli bidang formulir yang tidak dapat dimodifikasi di luar |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Mendapatkan atau mengatur nama baru untuk bidang formulir setelah perbaikan. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Mendapatkan atau mengatur nama baru untuk bidang formulir setelah perbaikan. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Menginisialisasi sebuah instance baru dari kelas [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) dengan nama yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama asli bidang formulir. |
|

### getName() {#getName--}
```
public final String getName()
```


Mendapatkan nama asli bidang formulir yang tidak dapat dimodifikasi di luar
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Mendapatkan atau mengatur nama baru untuk bidang formulir setelah perbaikan.
Nama ini menghapus pengidentifikasi unik duplikat dengan bidang formulir lain dan menetapkan nama bookmark unik.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Mendapatkan atau mengatur nama baru untuk bidang formulir setelah perbaikan.
Nama ini menghapus pengidentifikasi unik duplikat dengan bidang formulir lain dan menetapkan nama bookmark unik.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |


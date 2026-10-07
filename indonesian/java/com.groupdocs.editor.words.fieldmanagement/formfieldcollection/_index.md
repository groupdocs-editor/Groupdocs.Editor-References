---
title: "FormFieldCollection"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili kumpulan bidang formulir."
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Mewakili kumpulan bidang formulir.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Menginisialisasi instance baru dari kelas [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Menyisipkan bidang formulir ke dalam koleksi. |
|
|  | [get(String name)](#get-java.lang.String-) | Mendapatkan bidang formulir dengan nama yang ditentukan. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Mendapatkan bidang formulir dengan nama dan tipe yang ditentukan. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Menginisialisasi instance baru dari kelas [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Sebuah enumerator yang dapat digunakan untuk mengiterasi koleksi.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Menyisipkan bidang formulir ke dalam koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Bidang formulir yang akan disisipkan. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Mendapatkan bidang formulir dengan nama yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama bidang formulir. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Mendapatkan bidang formulir dengan nama dan tipe yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama bidang formulir. |


T
: Tipe bidang formulir.
|
| type | java.lang.Class<T> |  |

**Returns:**
T - Bidang formulir dengan nama dan tipe yang ditentukan, jika ditemukan; jika tidak, nilai default untuk tipe tersebut.


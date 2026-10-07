---
title: "WordProcessingProtectionType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili semua tipe perlindungan yang tersedia dari dokumen WordProcessing."
type: docs
weight: 47
url: /id/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Mewakili semua tipe perlindungan yang tersedia dari dokumen WordProcessing.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NoProtection](#NoProtection) | Dokumen tidak dilindungi. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Pengguna hanya dapat menambahkan tanda revisi ke dokumen |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Pengguna hanya dapat memodifikasi komentar dalam dokumen |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Pengguna hanya dapat memasukkan data ke dalam bidang formulir di dokumen |
|
|  | [ReadOnly](#ReadOnly) | Tidak ada perubahan yang diizinkan pada dokumen |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


Dokumen tidak dilindungi. Nilai default.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Pengguna hanya dapat menambahkan tanda revisi ke dokumen


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Pengguna hanya dapat memodifikasi komentar dalam dokumen


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Pengguna hanya dapat memasukkan data ke dalam bidang formulir di dokumen


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Tidak ada perubahan yang diizinkan pada dokumen


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>

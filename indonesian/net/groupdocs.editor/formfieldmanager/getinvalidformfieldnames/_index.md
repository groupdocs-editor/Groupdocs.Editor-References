---
title: "GetInvalidFormFieldNames"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil koleksi nama bidang formulir yang tidak valid dari dokumen."
type: docs
weight: 30
url: /id/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Mengambil koleksi nama bidang formulir yang tidak valid dari dokumen.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Nilai Kembalian

Koleksi enumerable berupa string yang mewakili nama-nama bidang formulir tidak valid yang ditemukan dalam dokumen.

### Catatan

Metode `GetInvalidFormFieldNames` memindai konten dokumen untuk mengidentifikasi bidang formulir dengan nama tidak valid. Metode ini mengembalikan koleksi string yang berisi nama-nama bidang formulir tidak valid tersebut. Sebuah bidang formulir dianggap tidak valid jika menggandakan pengidentifikasi unik dengan bidang formulir lain dan tidak memiliki nama bookmark unik yang terkait dengannya. Nama bookmark ini berfungsi sebagai pengidentifikasi untuk setiap bidang formulir. Koleksi yang dikembalikan mempertahankan urutan nama bidang formulir sebagaimana muncul dalam dokumen. Metode ini berguna untuk mendeteksi dan menganalisis masalah penamaan dalam bidang formulir, yang mungkin perlu ditangani menggunakan metode [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### Lihat Juga

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

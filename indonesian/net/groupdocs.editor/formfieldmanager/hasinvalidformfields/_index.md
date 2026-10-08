---
title: "HasInvalidFormFields"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memeriksa apakah dokumen berisi bidang formulir yang tidak valid."
type: docs
weight: 40
url: /id/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Memeriksa apakah dokumen berisi bidang formulir yang tidak valid.

```csharp
public bool HasInvalidFormFields()
```

### Nilai Kembalian

`true` jika dokumen berisi satu atau lebih bidang formulir yang tidak valid; jika tidak, `false`.

### Catatan

Metode `HasInvalidFormFields` memindai konten dokumen untuk menentukan apakah terdapat bidang formulir dengan nama tidak valid. Sebuah bidang formulir dianggap tidak valid jika menggandakan pengidentifikasi unik dengan bidang formulir lain dan tidak memiliki nama bookmark unik yang terkait dengannya. Nama bookmark ini berfungsi sebagai pengidentifikasi untuk setiap bidang formulir. Metode ini berguna untuk dengan cepat memeriksa apakah dokumen memerlukan inspeksi lebih lanjut dan potensi koreksi nama bidang formulir. ; ; ;

### Lihat Juga

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

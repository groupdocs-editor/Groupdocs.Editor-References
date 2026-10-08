---
title: "FormFieldManager"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Kelola Formulir dengan Bidang Formulir Warisan. Bidang formulir warisan adalah jenis bidang yang tersedia di versi Word processing sebelumnya. Grup Legacy Forms yang terlihat setelah Anda mengklik ikon Legacy Tools mencakup tiga jenis bidang formulir yang dapat Anda sisipkan dalam dokumen: teks, kotak centang, dropdown, tanggal, dll. lihat lebih lanjut FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. Setiap bidang formulir ini memungkinkan pengguna formulir untuk memilih atau memasukkan informasi jenis yang Anda anggap sesuai."
type: docs
weight: 40
url: /id/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Kelola Formulir dengan Bidang Formulir Warisan. Bidang formulir warisan adalah jenis bidang yang tersedia di versi Word processing sebelumnya. Grup Legacy Forms (terlihat setelah Anda mengklik ikon Legacy Tools) mencakup tiga jenis bidang formulir yang dapat Anda sisipkan dalam dokumen: teks, kotak centang, dropdown, tanggal, dll., lihat lebih lanjut [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). Setiap bidang formulir ini memungkinkan pengguna formulir untuk memilih atau memasukkan informasi jenis yang Anda anggap sesuai.

```csharp
public sealed class FormFieldManager
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Mendapatkan koleksi bidang formulir dalam dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Memperbaiki nama bidang formulir yang tidak valid dalam dokumen dengan menerapkan pembaruan yang ditentukan atau secara otomatis menghasilkan nama unik. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Mengambil koleksi nama bidang formulir yang tidak valid dari dokumen. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Memeriksa apakah dokumen berisi bidang formulir yang tidak valid. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Menghapus beberapa bidang formulir dari dokumen. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Menghapus bidang formulir tertentu dari dokumen. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Memperbarui bidang formulir dalam dokumen berdasarkan koleksi bidang formulir yang disediakan. |

### Catatan

Kelas [`FormFieldManager`](../formfieldmanager) menyediakan fungsionalitas untuk menangani bidang formulir dalam dokumen. Ini memungkinkan pengguna untuk memperoleh, memperbarui, memperbaiki, memeriksa ketidakvalidan, dan menghapus bidang formulir dari dokumen.

### Lihat Juga

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

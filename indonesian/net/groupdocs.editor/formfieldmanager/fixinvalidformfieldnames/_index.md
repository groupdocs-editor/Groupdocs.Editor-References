---
title: "FixInvalidFormFieldNames"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memperbaiki nama bidang formulir yang tidak valid dalam dokumen dengan menerapkan pembaruan yang ditentukan atau secara otomatis menghasilkan nama unik."
type: docs
weight: 20
url: /id/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Memperbaiki nama bidang formulir yang tidak valid dalam dokumen dengan menerapkan pembaruan yang ditentukan atau secara otomatis menghasilkan nama unik.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | Koleksi pembaruan untuk nama bidang formulir tidak valid. Setiap pembaruan berisi nama asli bidang formulir dan nama baru yang sesuai. Jika dibiarkan kosong, nama bidang formulir tidak valid akan secara otomatis diganti nama untuk memastikan keunikan. |

### Catatan

Metode `FixInvalidFormFieldNames` menyelesaikan konflik atau inkonsistensi penamaan dalam bidang formulir dokumen dengan menerapkan pembaruan yang ditentukan dalam koleksi *updateInvalidFormFieldNames*, atau secara otomatis menghasilkan nama unik jika koleksi kosong. Metode ini berguna ketika beberapa nama bidang formulir tidak valid atau bertentangan dengan elemen lain dalam dokumen, dan perlu diperbaiki untuk memastikan fungsi yang tepat. ; ;

### Lihat Juga

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

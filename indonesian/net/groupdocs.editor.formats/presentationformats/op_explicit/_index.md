---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi string yang mewakili ekstensi file menjadi objek PresentationFormatsgroupdocs.editor.formats/presentationformats."
type: docs
weight: 150
url: /id/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Mengonversi string yang mewakili ekstensi file menjadi objek [`PresentationFormats`](../../presentationformats).

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |

### Nilai Kembalian

Objek [`PresentationFormats`](../../presentationformats) yang sesuai dengan ekstensi file yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Dilemparkan ketika ekstensi file yang ditentukan bernilai null. |

### Lihat Juga

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

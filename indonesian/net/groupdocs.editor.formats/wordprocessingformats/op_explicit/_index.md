---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi string yang mewakili ekstensi file menjadi objek WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats."
type: docs
weight: 140
url: /id/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Mengonversi string yang mewakili ekstensi file menjadi objek [`WordProcessingFormats`](../../wordprocessingformats).

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |

### Nilai Kembalian

Objek [`WordProcessingFormats`](../../wordprocessingformats) yang sesuai dengan ekstensi file yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika ekstensi file yang ditentukan bernilai null. |

### Lihat Juga

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi string yang mewakili ekstensi file menjadi objek EmailFormatsgroupdocs.editor.formats/emailformats."
type: docs
weight: 150
url: /id/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Mengonversi string yang mewakili ekstensi file menjadi objek [`EmailFormats`](../../emailformats).

```csharp
public static explicit operator EmailFormats(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |

### Nilai Kembalian

Sebuah objek [`EmailFormats`](../../emailformats) yang sesuai dengan ekstensi file yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [EmailFormats](../../emailformats) | Dilemparkan ketika ekstensi file yang ditentukan bernilai null. |

### Lihat Juga

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi string yang mewakili ekstensi file menjadi objek EBookFormatsgroupdocs.editor.formats/ebookformats."
type: docs
weight: 60
url: /id/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

Mengonversi string yang mewakili ekstensi file menjadi objek [`EBookFormats`](../../ebookformats).

```csharp
public static explicit operator EBookFormats(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |

### Nilai Kembalian

Sebuah objek [`EBookFormats`](../../ebookformats) yang sesuai dengan ekstensi file yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [EBookFormats](../../ebookformats) | Dilemparkan ketika ekstensi file yang ditentukan bernilai null. |

### Lihat Juga

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

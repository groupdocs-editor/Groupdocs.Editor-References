---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi string yang mewakili ekstensi file menjadi objek TextualFormatsgroupdocs.editor.formats/textualformats."
type: docs
weight: 100
url: /id/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Mengonversi string yang mewakili ekstensi file menjadi objek [`TextualFormats`](../../textualformats).

```csharp
public static explicit operator TextualFormats(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |

### Nilai Kembalian

Objek [`TextualFormats`](../../textualformats) yang sesuai dengan ekstensi file yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [TextualFormats](../../textualformats) | Dilemparkan ketika ekstensi file yang ditentukan bernilai null. |

### Lihat Juga

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

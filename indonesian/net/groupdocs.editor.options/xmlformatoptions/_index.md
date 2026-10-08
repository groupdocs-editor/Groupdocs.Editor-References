---
title: "XmlFormatOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Berisi opsi yang memungkinkan menyesuaikan pemformatan dokumen XML ketika ditampilkan sebagai HTML"
type: docs
weight: 1280
url: /id/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Berisi opsi yang memungkinkan menyesuaikan pemformatan dokumen XML, ketika direpresentasikan sebagai HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | Ketika diaktifkan, setiap pasangan atribut-nilai dalam setiap elemen XML akan ditempatkan pada baris baru. Secara default bernilai false (dinonaktifkan) — semua pasangan atribut-nilai ditempatkan dalam satu baris. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Menunjukkan apakah instance opsi pemformatan XML ini memiliki nilai default |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | Ketika diaktifkan, node teks daun (konten tekstual di dalam elemen XML yang tidak memiliki anak) akan ditampilkan pada baris baru dengan indentasi kiri yang lebih besar. Secara default bernilai false (dinonaktifkan) — node teks daun ditempatkan pada baris yang sama dengan induknya, tanpa indentasi baru. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Memungkinkan menentukan offset untuk indentasi kiri setiap baris baru. Tidak dapat berupa nilai non-nol tanpa satuan. Secara default adalah 10pt |

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

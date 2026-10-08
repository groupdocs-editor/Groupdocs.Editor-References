---
title: "DelimitedTextSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Berisi opsi untuk menghasilkan dan menyimpan dokumen Spreadsheet berbasis teks seperti CSV, berbasis tab, dll. yang menggunakan pemisah delimiter"
type: docs
weight: 820
url: /id/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Berisi opsi untuk menghasilkan dan menyimpan dokumen Spreadsheet berbasis teks (CSV, berbasis Tab, dll.), yang menggunakan pemisah (delimiter)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Konstruktor tanpa parameter ini membuat instance baru dari DelimitedTextSaveOptions dengan pemisah default titik koma (; ) (dapat diubah kemudian melalui properti [`Separator`](./separator)) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Membuat instance kelas opsi untuk teks delimited dengan pemisah (delimiter) wajib |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Mengizinkan penetapan encoding untuk dokumen Spreadsheet berbasis teks. Secara default (dan jika tidak ditentukan) adalah UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Menunjukkan apakah pemisah harus dikeluarkan untuk baris kosong. Nilai default adalah `false` yang berarti konten untuk baris kosong akan kosong. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Mengizinkan penentuan pemisah string (delimiter) untuk dokumen Spreadsheet berbasis teks |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Menunjukkan apakah baris dan kolom kosong di awal harus dipangkas seperti yang dilakukan MS Excel |

### Catatan

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: DelimitedTextSaveOptions
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Berisi pilihan untuk membuat dan menyimpan dokumen Spreadsheet berbasis teks CSV Tabbased dll yang menggunakan pemisah delimiter
type: docs
weight: 830
url: /id/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Berisi pilihan untuk membuat dan menyimpan dokumen Spreadsheet berbasis teks (CSV, Tab-based dll), yang menggunakan pemisah (delimiter)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions)(string) | Membuat instance kelas opsi untuk teks yang dibatasi dengan pemisah wajib (pembatas) |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Memungkinkan untuk mengatur penyandian untuk dokumen Spreadsheet berbasis teks. Secara default (dan jika tidak ditentukan) adalah UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Menunjukkan apakah pemisah harus ditampilkan untuk baris kosong. Nilai default adalah`PALSU` yang artinya isi baris kosong akan kosong. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Memungkinkan untuk menentukan pemisah string (pembatas) untuk dokumen Spreadsheet berbasis teks |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Menunjukkan apakah baris dan kolom kosong di depan harus dipangkas seperti yang dilakukan MS Excel |

### Perkataan

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Lihat juga

* interface [ISaveOptions](../isaveoptions)
* ruang nama [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
---
title: "DelimitedTextEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Opsi untuk memuat dokumen Spreadsheet berbasis teks seperti CSV, berbasis tab, dll. yang menggunakan pemisah delimiter"
type: docs
weight: 810
url: /id/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Opsi untuk memuat dokumen Spreadsheet berbasis teks (CSV, berbasis Tab, dll.), yang menggunakan pemisah (delimiter)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Membuat instance kelas opsi untuk teks delimited dengan pemisah (delimiter) wajib |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam dokumen berbasis teks diubah menjadi data tanggal. Nilai default adalah `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam dokumen berbasis teks diubah menjadi data numerik. Nilai default adalah `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimisasi memori selama pemrosesan dokumen input, yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain mengurangi penggunaan memori. Berguna saat memproses dokumen besar dan menghadapi OutOfMemoryException. Nilai default adalah `false` (optimisasi memori dinonaktifkan demi kinerja yang lebih baik). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Mengizinkan penentuan pemisah string (delimiter) untuk dokumen Spreadsheet berbasis teks |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Mendefinisikan apakah delimiter berurutan harus diperlakukan sebagai satu. Secara default adalah `false`. |

### Catatan

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "SpreadsheetLoadOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Berisi opsi untuk memuat dokumen biner Spreadsheet Cells yang kompatibel dengan Excel seperti XLSX, ODS, dll. ke dalam kelas Editor"
type: docs
weight: 1120
url: /id/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Berisi opsi untuk memuat dokumen Spreadsheet biner (Cells, kompatibel dengan Excel) seperti XLS(X), ODS, dll. ke dalam kelas Editor

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Konstruktor default tanpa parameter - semua parameter memiliki nilai default |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimisasi memori selama pemrosesan dokumen input, yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain mengurangi penggunaan memori. Berguna saat memproses dokumen besar dan menghadapi OutOfMemoryException. Nilai default adalah false (optimisasi memori dinonaktifkan demi kinerja yang lebih baik). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Memungkinkan menentukan, memodifikasi, dan memperoleh kata sandi yang akan digunakan untuk membuka dokumen Spreadsheet, jika dokumen tersebut terenkripsi. Atur ke NULL atau string kosong agar tidak menggunakan kata sandi (nilai default). |

### Lihat Juga

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

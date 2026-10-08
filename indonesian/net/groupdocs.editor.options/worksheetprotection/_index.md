---
title: "WorksheetProtection"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengkapsulasi opsi perlindungan lembar kerja yang memungkinkan melindungi lembar kerja dalam dokumen Spreadsheet output dari modifikasi tipe tertentu dengan kata sandi yang ditentukan."
type: docs
weight: 1250
url: /id/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Mengkapsulkan opsi perlindungan lembar kerja, yang memungkinkan melindungi lembar kerja dalam dokumen Spreadsheet output dari modifikasi tipe tertentu dengan kata sandi yang ditentukan.

```csharp
public sealed class WorksheetProtection
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Membuat instance baru dengan parameter default. Jika tidak diubah dan diteruskan ke SpreadsheetSaveOptions, tidak ada perlindungan lembar kerja yang akan diterapkan. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Membuat instance baru dengan tipe perlindungan lembar kerja dan kata sandi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Kata sandi yang digunakan untuk melindungi lembar kerja. Jika NULL atau string kosong, perlindungan tidak akan diterapkan. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Memungkinkan menentukan tipe perlindungan lembar kerja. Secara default adalah 'None' - perlindungan tidak diterapkan. |

### Catatan

Sebagian besar format Spreadsheet seperti XLSX memungkinkan melindungi lembar kerja dari pengeditan dengan kata sandi. Kelas ini memungkinkan mengaktifkan perlindungan tersebut dan menentukan opsinya.

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

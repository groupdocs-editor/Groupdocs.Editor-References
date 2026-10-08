---
title: "SpreadsheetSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengizinkan menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Spreadsheet yang mematuhi Excelcompliant"
type: docs
weight: 1130
url: /id/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Spreadsheet (mematuhi Excel)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Konstruktor tanpa parameter ini membuat instance baru dari SpreadsheetSaveOptions dengan format output XLSX (dapat diubah kemudian melalui properti [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Membuat instance baru dari SpreadsheetSaveOptions dengan format output Spreadsheet yang wajib ditentukan, sementara semua parameter lain menggunakan nilai default |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan lembar kerja yang ada dalam spreadsheet asli pada posisi yang ditentukan oleh properti [`WorksheetNumber`](./worksheetnumber), atau harus disisipkan di antara lembar kerja yang ada dan sebelumnya, tanpa mengganti isinya. Secara default false — lembar kerja yang ada akan digantikan. Properti ini diabaikan, jika nilai properti [`WorksheetNumber`](./worksheetnumber) disetel ke '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Mengizinkan menentukan format Spreadsheet, yang akan digunakan untuk menyimpan dokumen |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan digunakan untuk mengenkripsi dokumen Spreadsheet yang dihasilkan, jika format dokumen tersebut mendukung perlindungan kata sandi. Tentukan NULL atau string kosong untuk menghapus (membersihkan) kata sandi. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Mengizinkan menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada alih-alih membuat spreadsheet satu-lembar baru (perilaku default). WorksheetNumber adalah nomor berbasis 1 dari sebuah lembar kerja dalam spreadsheet, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default), spreadsheet baru akan dibuat dengan satu lembar kerja yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada spreadsheet yang valid, yang dimuat dalam kelas Editor, lembar kerja yang diedit, yang direpresentasikan oleh instance EditableDocument input, akan disisipkan ke dalam spreadsheet ini. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Mengizinkan menentukan array dengan nomor berbasis 1 dari lembar kerja yang harus dihapus dari spreadsheet selama proses penyimpanan, bila lembar kerja yang diedit disisipkan ke dalam spreadsheet yang ada |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Mengizinkan mengaktifkan perlindungan lembar kerja untuk dokumen Spreadsheet output. Secara default NULL — perlindungan tidak diterapkan. Tidak semua format mendukung perlindungan lembar kerja. |

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

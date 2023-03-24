---
title: SpreadsheetSaveOptions
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Memungkinkan untuk menentukan opsi khusus untuk membuat dan menyimpan dokumen Spreadsheet sesuai dengan Excel
type: docs
weight: 1120
url: /id/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk membuat dan menyimpan dokumen Spreadsheet (sesuai dengan Excel)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions)(SpreadsheetFormats) | Membuat instance baru dari SpreadsheetSaveOptions dengan format keluaran Spreadsheet wajib yang ditentukan, sedangkan semua parameter lainnya adalah default |

## Properti

| Nama | Keterangan |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Boolean flag, yang menentukan apakah lembar kerja yang diedit harus menggantikan lembar kerja yang ada di spreadsheet asli pada posisi yang ditentukan oleh[`WorksheetNumber`](./worksheetnumber) properti, atau harus disuntikkan antara lembar kerja yang ada dan yang sebelumnya, tanpa mengganti isinya. Secara default salah — lembar kerja yang ada akan diganti. Properti ini diabaikan, jika nilai[`WorksheetNumber`](./worksheetnumber) properti disetel ke '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Memungkinkan untuk menentukan format Spreadsheet, yang akan digunakan untuk menyimpan dokumen |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Memungkinkan untuk menentukan, memodifikasi, mendapatkan, atau menghapus kata sandi, yang akan digunakan untuk menyandikan dokumen Spreadsheet yang dihasilkan, jika format dokumen ini mendukung perlindungan kata sandi. Tentukan NULL atau string kosong untuk menghapus (membersihkan) kata sandi. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Memungkinkan untuk menyisipkan lembar kerja yang telah diedit ke dalam salinan spreadsheet yang ada daripada membuat spreadsheet lembar kerja tunggal baru (perilaku default). WorksheetNumber adalah angka berbasis 1 lembar kerja dalam spreadsheet, dimuat di kelas Editor. Jika 0 (nilai default), spreadsheet baru akan dibuat dengan lembar kerja yang diedit tunggal. Jika lebih besar atau lebih kecil dari nol, dan ada spreadsheet yang valid, dimuat di kelas Editor, lembar kerja yang diedit, yang diwakili oleh contoh masukan EditableDocument, akan dimasukkan ke dalam spreadsheet ini. |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Memungkinkan untuk mengaktifkan perlindungan lembar kerja untuk dokumen Spreadsheet keluaran. Secara default adalah NULL - perlindungan tidak diterapkan. Tidak semua format mendukung perlindungan lembar kerja. |

### Lihat juga

* interface [ISaveOptions](../isaveoptions)
* ruang nama [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
---
title: "InsertAsNewWorksheet"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Bendera boolean yang menentukan apakah lembar kerja yang diedit harus menggantikan lembar kerja yang ada di spreadsheet asli pada posisi yang ditentukan oleh properti WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber atau harus disisipkan di antara lembar kerja yang ada dan yang sebelumnya tanpa mengganti isinya. Secara default bernilai false, lembar kerja yang ada akan diganti. Properti ini diabaikan jika nilai properti WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber disetel ke 0."
type: docs
weight: 20
url: /id/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Bendera boolean, yang menentukan apakah lembar kerja yang diedit harus menggantikan lembar kerja yang ada di spreadsheet asli pada posisi yang ditentukan oleh properti [`WorksheetNumber`](../worksheetnumber), atau harus disisipkan di antara lembar kerja yang ada dan yang sebelumnya, tanpa mengganti isinya. Secara default bernilai false — lembar kerja yang ada akan diganti. Properti ini diabaikan, jika nilai properti [`WorksheetNumber`](../worksheetnumber) disetel ke '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Catatan

Secara default lembar kerja diganti. Ini berarti bahwa jika spreadsheet yang diberikan memiliki 5 lembar kerja, dan [`WorksheetNumber`](../worksheetnumber)=4, maka lembar kerja ke-4 akan diganti dengan lembar kerja yang baru diedit, sementara jumlah total lembar kerja dalam spreadsheet (5) tetap tidak berubah. Namun, jika nilai properti ini disetel ke true, lembar kerja yang baru diedit akan disisipkan sebagai lembar kerja ke-4, dan semua lembar kerja berikutnya akan dipindahkan ke akhir: "old" lembar kerja ke-4 menjadi ke-5, dan ke-5 menjadi ke-6, dan jumlah total lembar kerja dalam spreadsheet akan bertambah satu menjadi 6.

### Lihat Juga

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

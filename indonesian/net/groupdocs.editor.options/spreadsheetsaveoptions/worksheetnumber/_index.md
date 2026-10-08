---
title: "WorksheetNumber"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada alih-alih membuat spreadsheet lembar kerja tunggal baru (perilaku default). WorksheetNumber adalah nomor lembar kerja berbasis 1 dalam spreadsheet yang dimuat di kelas Editor. Jika nilainya 0 (nilai default), spreadsheet baru akan dibuat dengan satu lembar kerja yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol dan ada spreadsheet yang valid dimuat di kelas Editor, lembar kerja yang diedit yang direpresentasikan oleh instance EditableDocument input akan disisipkan ke dalam spreadsheet ini."
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Mengizinkan menyisipkan lembar kerja yang diedit ke dalam salinan spreadsheet yang ada alih-alih membuat spreadsheet satu-lembar baru (perilaku default). WorksheetNumber adalah nomor berbasis 1 dari sebuah lembar kerja dalam spreadsheet, yang dimuat dalam kelas Editor. Jika nilainya 0 (nilai default), spreadsheet baru akan dibuat dengan satu lembar kerja yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada spreadsheet yang valid, yang dimuat dalam kelas Editor, lembar kerja yang diedit, yang direpresentasikan oleh instance EditableDocument input, akan disisipkan ke dalam spreadsheet ini.

```csharp
public int WorksheetNumber { get; set; }
```

### Catatan

Properti integer WorksheetNumber, jika tidak berada dalam keadaan default (nilai cadangan '0'), mewakili nomor lembar kerja, sehingga dimulai dari 1, bukan dari nol, dan nilai maksimumnya adalah jumlah semua slide yang ada dalam presentasi. Namun, jika nilai yang ditentukan lebih besar dari jumlah semua slide, GroupDocs.Editor akan menyesuaikannya untuk menandai lembar kerja terakhir. Nilai negatif juga diperbolehkan dan menghitung lembar kerja dari akhir. Misalnya, "-1" berarti lembar kerja terakhir dalam spreadsheet, "-2" — lembar kerja sebelum terakhir, dll. Seperti pada nilai positif, ketika nomor lembar kerja negatif melebihi total jumlah lembar kerja dalam spreadsheet yang diberikan, itu akan disesuaikan ke lembar kerja pertama. Properti boolean [`InsertAsNewWorksheet`](../insertasnewworksheet) sangat terkait dengan properti ini.

### Contoh

Spreadsheet yang diberikan memiliki 5 lembar kerja: WorksheetNumber = 0; — abaikan spreadsheet yang diberikan, buat spreadsheet baru dan letakkan lembar kerja yang diedit ke dalamnya. WorksheetNumber = 1; — ganti lembar kerja pertama dengan yang diedit WorksheetNumber = 2; — ganti lembar kerja kedua dengan yang diedit WorksheetNumber = 5; — ganti lembar kerja terakhir (ke-5) dengan yang diedit WorksheetNumber = 6; — ganti lembar kerja terakhir (ke-5) dengan yang diedit, karena 6 lebih besar dari 5 sehingga disesuaikan WorksheetNumber = -1; — ganti lembar kerja terakhir (ke-5) dengan yang diedit, karena "-1" berarti "yang terakhir ada" WorksheetNumber = -2; — ganti lembar kerja ke-4 dengan yang diedit WorksheetNumber = -3; — ganti lembar kerja ke-3 dengan yang diedit WorksheetNumber = -4; — ganti lembar kerja ke-2 dengan yang diedit WorksheetNumber = -5; — ganti lembar kerja pertama dengan yang diedit WorksheetNumber = -6; — ganti lembar kerja pertama dengan yang diedit, karena "-6" lebih besar dari 5 sehingga disesuaikan

### Lihat Juga

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

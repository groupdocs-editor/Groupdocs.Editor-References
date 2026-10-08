---
title: "WorksheetNumbersToDelete"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan array dengan nomor lembar kerja berbasis 1 yang harus dihapus dari spreadsheet saat disimpan jika lembar kerja yang diedit dimasukkan ke dalam spreadsheet yang ada."
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

Mengizinkan menentukan array dengan nomor berbasis 1 dari lembar kerja yang harus dihapus dari spreadsheet selama proses penyimpanan, bila lembar kerja yang diedit disisipkan ke dalam spreadsheet yang ada

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### Catatan

Ketika lembar kerja yang diedit disimpan bukan sebagai spreadsheet lembar kerja tunggal baru (perilaku default), melainkan disimpan ke dalam spreadsheet yang ada (menggunakan properti [`WorksheetNumber`](../worksheetnumber)), juga dimungkinkan untuk menghapus beberapa lembar kerja tertentu dari spreadsheet ini dengan menentukan nomor mereka dalam array ini.

Secara default array ini adalah `null` — tidak ada lembar kerja yang akan dihapus. Namun, ketika array ini tidak null dan tidak kosong, serta berisi setidaknya satu nomor lembar kerja yang valid, setelah dokumen spreadsheet output dihasilkan dengan konten lembar kerja yang diedit, lembar kerja dengan nomor yang ditentukan akan dihapus dari spreadsheet tepat sebelum menulis kontennya ke aliran output atau file.

Nomor lembar kerja dalam array ini berbasis 1, bukan berbasis 0; nomor yang tidak valid (kurang dari 1 atau lebih besar dari total jumlah lembar kerja) akan diabaikan.

### Lihat Juga

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "WorksheetIndex"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan indeks berbasis 0 dari tab lembar kerja dokumen Spreadsheet input yang harus dikonversi ke HTML, lihat catatan."
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Memungkinkan untuk menentukan indeks berbasis 0 dari lembar kerja (tab) dokumen Spreadsheet input, yang harus dikonversi ke HTML (lihat catatan).

```csharp
public int WorksheetIndex { get; set; }
```

### Catatan

Sebagian besar dokumen Spreadsheet mendukung konsep tab, yaitu mereka dapat memiliki banyak tab. Di sisi lain, format HTML tidak mendukung struktur semacam itu. Karena itu GroupDocs.Editor hanya dapat mengonversi satu tab tertentu dari dokumen input ke HTML, dan opsi ini memungkinkan untuk menentukan tab tersebut. Indeks tab berbasis 0, nilai negatif dilarang. Jika indeks yang ditentukan melebihi jumlah semua tab, akan dilemparkan pengecualian. Jika dokumen Spreadsheet input hanya memiliki satu tab, opsi ini akan diabaikan. Nilai default adalah 0 (tab pertama).

### Lihat Juga

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

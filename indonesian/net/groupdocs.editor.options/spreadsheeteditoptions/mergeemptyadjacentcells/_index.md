---
title: "MergeEmptyAdjacentCells"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Saat diaktifkan, sel horizontal kosong yang berdekatan dari dokumen Spreadsheet input akan direpresentasikan dalam dokumen HTML yang dapat diedit sebagai satu sel yang digabung dengan atribut colspan yang sesuai. Secara default dinonaktifkan (false)."
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

Ketika diaktifkan, sel horizontal kosong yang berdekatan dari dokumen Spreadsheet input akan direpresentasikan dalam dokumen HTML yang dapat diedit sebagai satu sel yang digabungkan dengan atribut `colspan` yang sesuai. Secara default dinonaktifkan (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Catatan

Secara default GroupDocs.Editor mengonversi tabel dari dokumen Spreadsheet input ke dokumen HTML output dengan mempertahankan setiap sel. Namun, dokumen Spreadsheet dapat bersifat jarang — mereka dapat berisi banyak area kosong, di mana banyak sel kosong. Opsi ini, ketika diaktifkan, menggabungkan sel kosong tersebut menjadi satu dengan atribut `colspan` pada elemen `TD`, sehingga dapat secara signifikan mengurangi ukuran markup HTML yang dihasilkan.

### Lihat Juga

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

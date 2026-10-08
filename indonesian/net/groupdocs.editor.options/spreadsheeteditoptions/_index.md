---
title: "SpreadsheetEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan opsi khusus untuk mengedit dokumen dari semua format Spreadsheet yang didukung dan kompatibel dengan Excel"
type: docs
weight: 1110
url: /id/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dari semua format Spreadsheet (kompatibel dengan Excel) yang didukung

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga mereka akan diabaikan sepenuhnya. Default adalah false - lembar kerja tersembunyi tersedia dan diproses seperti biasa. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | Ketika diaktifkan, tabel HTML dalam dokumen HTML yang dihasilkan berisi baris tersembunyi kosong di bagian bawah dengan tinggi nol dan sel kosong, di mana hanya lebar yang ditentukan. Baris dengan sel kosong ini berisi nilai lebar tepat untuk setiap kolom dan meningkatkan konversi balik dari HTML ke Spreadsheet. Secara default diaktifkan (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | Ketika diaktifkan, sel horizontal kosong yang berdekatan dari dokumen Spreadsheet input akan direpresentasikan dalam dokumen HTML yang dapat diedit sebagai satu sel yang digabungkan dengan atribut `colspan` yang sesuai. Secara default dinonaktifkan (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Memungkinkan untuk menentukan indeks berbasis 0 dari lembar kerja (tab) dokumen Spreadsheet input, yang harus dikonversi ke HTML (lihat catatan). |

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

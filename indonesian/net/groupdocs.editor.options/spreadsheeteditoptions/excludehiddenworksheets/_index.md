---
title: "ExcludeHiddenWorksheets"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input sehingga mereka akan diabaikan sepenuhnya. Defaultnya adalah false, lembar kerja tersembunyi tersedia dan diproses seperti biasa."
type: docs
weight: 20
url: /id/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Memungkinkan mengecualikan lembar kerja tersembunyi dalam dokumen Spreadsheet input, sehingga mereka akan diabaikan sepenuhnya. Default adalah false - lembar kerja tersembunyi tersedia dan diproses seperti biasa.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Catatan

Beberapa format Spreadsheet biner (seperti XLSX) mendukung konsep lembar kerja tersembunyi (tab). Dokumen dengan format tersebut, jika memiliki lebih dari satu lembar kerja, dapat berisi lembar kerja tersembunyi tambahan. Secara default lembar kerja tersembunyi tersebut tersedia untuk diproses, tetapi dengan opsi ini dapat diabaikan, seolah-olah lembar kerja tersembunyi tersebut tidak ada. Ketika opsi ini diaktifkan, Anda tidak dapat memilih lembar kerja tersembunyi dengan properti '[`WorksheetIndex`](../worksheetindex)'.

### Lihat Juga

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

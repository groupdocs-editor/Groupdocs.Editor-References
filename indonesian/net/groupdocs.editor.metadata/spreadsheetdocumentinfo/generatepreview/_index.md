---
title: "GeneratePreview"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat dan mengembalikan pratinjau lembar kerja yang dipilih dalam bentuk gambar SVG"
type: docs
weight: 60
url: /id/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Membuat dan mengembalikan pratinjau lembar kerja yang dipilih dalam bentuk gambar SVG

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | Int32 | Indeks berbasis 0 dari lembar kerja yang diinginkan. Tidak boleh kurang dari 0, tidak boleh melebihi jumlah lembar kerja dalam spreadsheet ini. |

### Nilai Kembalian

Gambar SVG sebagai instance non-null dari kelas [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *worksheetIndex* yang ditentukan kurang dari 0 atau lebih besar dari jumlah lembar kerja dalam spreadsheet ini. |

### Lihat Juga

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

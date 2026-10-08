---
title: "GeneratePreview"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat dan mengembalikan pratinjau halaman yang dipilih dalam bentuk gambar SVG"
type: docs
weight: 60
url: /id/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Membuat dan mengembalikan pratinjau halaman yang dipilih dalam bentuk gambar SVG

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageIndex | Int32 | Indeks berbasis 0 dari halaman yang diinginkan. Tidak boleh kurang dari 0, tidak boleh melebihi jumlah halaman dalam dokumen WordProcessing ini. |

### Nilai Kembalian

Gambar SVG sebagai instance non-null dari kelas [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *pageIndex* yang ditentukan kurang dari 0 atau lebih besar dari jumlah halaman dalam dokumen WordProcessing ini. |

### Lihat Juga

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

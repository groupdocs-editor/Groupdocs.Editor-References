---
title: "GeneratePreview"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat dan mengembalikan pratinjau slide yang dipilih dalam bentuk gambar SVG"
type: docs
weight: 50
url: /id/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Membuat dan mengembalikan pratinjau slide yang dipilih dalam bentuk gambar SVG

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slideIndex | Int32 | Indeks berbasis 0 dari slide yang diinginkan. Tidak boleh kurang dari 0, tidak boleh melebihi jumlah slide dalam presentasi ini. |

### Nilai Kembalian

Gambar SVG sebagai instance non-null dari kelas [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *slideIndex* yang ditentukan kurang dari 0 atau lebih besar dari jumlah slide dalam presentasi ini. |

### Lihat Juga

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

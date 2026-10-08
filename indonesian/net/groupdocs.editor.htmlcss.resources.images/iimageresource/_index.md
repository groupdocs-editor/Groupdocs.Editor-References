---
title: "IImageResource"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili sumber daya gambar dari tipe apa pun, raster atau vektor."
type: docs
weight: 470
url: /id/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Mewakili sumber daya gambar dari jenis apa pun, raster atau vektor.

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | Dalam implementasi, tipe harus mengembalikan rasio aspek gambar tertentu terlepas dari tipenya. Baik gambar vektor maupun raster memiliki rasio aspek intrinsik antara lebar dan tinggi. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | Dalam implementasi, tipe harus mengembalikan dimensi linear gambar. Untuk gambar raster, dimensi tersebut adalah dimensi intrinsik dalam piksel. Gambar vektor, sebaliknya, tidak memiliki dimensi tetap, tetapi metadata-nya dapat berisi beberapa dimensi dasar dalam berbagai satuan ukuran. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | Dalam implementasi, tipe harus mengembalikan tipe gambar spesifik sebagai instance dari ImageType tertentu, yang mengenkapsulasi semua informasi spesifik tipe. |

### Catatan

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### Lihat Juga

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

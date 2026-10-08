---
title: "VectorImageResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Kelas dasar untuk gambar vektor apa pun yang didukung"
type: docs
weight: 590
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
## VectorImageResourceBase class

Kelas dasar untuk gambar vektor apa pun yang didukung

```csharp
public abstract class VectorImageResourceBase : IImageResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar vektor ini |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | Dalam implementasinya, tipe harus mengembalikan konten gambar vektor ini sebagai aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk gambar vektor ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini telah dibuang (`true`) atau tidak (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linear gambar vektor ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Mengembalikan nama gambar vektor ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | Dalam implementasinya, tipe harus mengembalikan konten gambar vektor ini dalam bentuk teks: XML yang dienkode base64 terkait tipe gambar |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | Dalam implementasinya, tipe harus mengembalikan informasi tentang tipe gambar vektor |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | Dalam implementasinya, tipe harus membuang instance ini |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals#equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | Dalam implementasinya, tipe harus menyimpan gambar ini ke disk dengan jalur yang ditentukan |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | Dalam implementasinya, tipe harus menyimpan gambar vektor saat ini ke format PNG raster ke dalam aliran byte yang ditentukan |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Lihat Juga

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

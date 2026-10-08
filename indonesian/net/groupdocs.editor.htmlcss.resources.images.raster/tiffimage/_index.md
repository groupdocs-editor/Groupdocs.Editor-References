---
title: "TiffImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu gambar dalam format TIFF Tagged Image File Format dengan metadata dan metode tambahan"
type: docs
weight: 550
url: /id/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Mewakili satu gambar dalam format TIFF (Tagged Image File Format) dengan metadata dan metode tambahan.

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [TiffImage](tiffimage#constructor_1)(string, string) | Membuat instance TiffImage baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar ini sebagai hubungan lebar terhadap tinggi |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Mengembalikan konten gambar raster ini sebagai aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar dari gambar raster ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini telah dibuang atau tidak |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Mengembalikan panjang file gambar raster ini dalam byte |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linier gambar raster ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Mengembalikan nama gambar raster ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Mengembalikan konten gambar raster ini sebagai string yang dienkode base64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Mengembalikan [`Tiff`](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Menyimpan gambar raster ini ke file yang ditentukan |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan merupakan gambar TIFF yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Memeriksa apakah string yang di-encode base64 yang ditentukan merupakan gambar TIFF yang valid |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Catatan

Lihat https://en.wikipedia.org/wiki/TIFF untuk detail. Dalam kasus yang sangat jarang, TIFF hadir di dalam dokumen WordProcessing.

### Lihat Juga

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

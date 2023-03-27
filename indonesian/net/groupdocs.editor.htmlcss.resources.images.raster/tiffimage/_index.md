---
title: TiffImage
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merupakan satu gambar dalam format TIFF Tagged Image File Format dengan metadata dan metode tambahannya
type: docs
weight: 560
url: /id/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Merupakan satu gambar dalam format TIFF (Tagged Image File Format) dengan metadata dan metode tambahannya

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Membuat instance GifImage baru dari konten, direpresentasikan sebagai aliran byte, dan dengan nama tertentu |
| [TiffImage](tiffimage#constructor_1)(string, string) | Membuat instance TiffImage baru dari konten, direpresentasikan sebagai string berenkode base64, dan dengan nama tertentu |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar ini sebagai hubungan lebar-ke-tinggi |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Mengembalikan konten gambar raster ini sebagai byte stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar dari gambar raster ini, yang terdiri dari nama dan ekstensi. Secara teoritis bisa berbeda dengan namanya. |
| [FramesCount](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/framescount) { get; } | Mengembalikan sejumlah bingkai (gambar) di dalam gambar TIFF ini. Tidak boleh kurang dari 1. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini dibuang atau tidak |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Mengembalikan panjang file gambar raster ini dalam byte |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linear dari gambar raster ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Mengembalikan nama gambar raster ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Mengembalikan konten gambar raster ini sebagai string berenkode base64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Mengembalikan ImageType.Tiff |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode dan properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan persamaan referensi yang ditentukan. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Menghasilkan dan mengembalikan instance baru 'System.Drawing.Bitmap' dari gambar raster ini. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Membuat dan mengembalikan sumber gambar baru yang diperkecil dari jenis yang sama, tetapi dengan tinggi baru yang diperkecil dan lebar yang diperkecil secara proporsional. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Menyimpan gambar raster ini ke file yang ditentukan |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan adalah gambar TIFF yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Memeriksa apakah string berenkode base64 yang ditentukan adalah gambar TIFF yang valid |

## Acara

| Nama | Keterangan |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Peristiwa, yang terjadi saat gambar raster ini dibuang |

### Perkataan

Lihat https://en.wikipedia.org/wiki/TIFF untuk detailnya. Dalam kasus yang sangat jarang TIFF hadir di dalam dokumen WordProcessing.

### Lihat juga

* class [RasterImageResourceBase](../rasterimageresourcebase)
* ruang nama [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

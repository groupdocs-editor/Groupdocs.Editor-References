---
title: "BmpImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu gambar dalam format BMP BitMap Picture beserta metadata dan metode tambahan"
type: docs
weight: 490
url: /id/net/groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
## BmpImage class

Mewakili satu gambar dalam format BMP (BitMap Picture) dengan metadata dan metode tambahan.

```csharp
public sealed class BmpImage : RasterImageResourceBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [BmpImage](bmpimage#constructor)(string, Stream) | Membuat instance BmpImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [BmpImage](bmpimage#constructor_1)(string, string) | Membuat instance BmpImage baru dari konten, yang direpresentasikan sebagai string yang dienkode base64, dan dengan nama yang ditentukan |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/type) { get; } | Mengembalikan ImageType.Bmp |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Menyimpan gambar raster ini ke file yang ditentukan |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan adalah gambar BMP yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid_1)(string) | Memeriksa apakah string yang dienkode base64 yang ditentukan adalah gambar BMP yang valid |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Lihat Juga

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

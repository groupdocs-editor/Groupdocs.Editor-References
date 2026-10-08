---
title: "SvgImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu gambar vektor dalam format SVG Scalable Vector Graphics dengan dimensi metadata-nya dan metode tambahan untuk menyimpan ke PNG"
type: docs
weight: 580
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Mewakili satu gambar vektor dalam format SVG (Scalable Vector Graphics) dengan metadata (dimensi) dan metode tambahan (menyimpan ke PNG)

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [SvgImage](svgimage#constructor_1)(string, string) | Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai string biasa, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar vektor ini |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Mengembalikan konten gambar SVG ini sebagai aliran biner dengan posisi asli |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk gambar vektor ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini telah dibuang (`true`) atau tidak (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linear gambar vektor ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Mengembalikan nama gambar vektor ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Mengembalikan konten gambar SVG ini sebagai konten biner yang di-encode base64 (bukan sebagai teks mentah dalam format XML) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Mengembalikan [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Mengembalikan konten gambar SVG ini dalam bentuk teks yang mematuhi XML asli |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Menyimpan gambar SVG ini ke file |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Menyimpan gambar SVG vektor ini menjadi gambar PNG raster |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Melakukan pemeriksaan permukaan apakah konten teks yang mematuhi XML yang ditentukan mewakili gambar SVG |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Lihat Juga

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

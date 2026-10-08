---
title: "WmfImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu gambar vektor dalam format WMF Windows MetaFile beserta metadata dan metode tambahan"
type: docs
weight: 600
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

Mewakili satu gambar vektor dalam format WMF (Windows MetaFile) dengan metadata dan metode tambahan

```csharp
public sealed class WmfImage : MetaImageBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [WmfImage](wmfimage#constructor_1)(string, string) | Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar vektor ini |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | Mengembalikan konten gambar WMF ini sebagai aliran biner |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk gambar vektor ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini telah dibuang (`true`) atau tidak (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linear gambar vektor ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Mengembalikan nama gambar vektor ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | Mengembalikan konten gambar WMF ini sebagai teks biasa |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | Mengembalikan ImageType.Wmf |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | Membuang gambar WMF ini dengan membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | Menyimpan gambar WMF ini ke file |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | Menyimpan gambar WMF vektor ini menjadi gambar raster PNG |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | Menyimpan gambar WMF vektor ini menjadi gambar vektor SVG |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan adalah gambar WMF yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar WMF yang valid |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Lihat Juga

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

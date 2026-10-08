---
title: "EmfImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu gambar vektor dalam format Enhanced Metafile (EMF) beserta metadata dan metode tambahan"
type: docs
weight: 560
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Mewakili satu gambar vektor dalam format Enhanced Metafile (EMF) dengan metadata dan metode tambahan

```csharp
public sealed class EmfImage : MetaImageBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [EmfImage](emfimage#constructor_1)(string, string) | Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Mengembalikan rasio aspek gambar vektor ini |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Mengembalikan konten gambar EMF ini sebagai aliran biner |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk gambar vektor ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Menentukan apakah gambar raster ini telah dibuang (`true`) atau tidak (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Mengembalikan dimensi linear gambar vektor ini (lebar dan tinggi) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Mengembalikan nama gambar vektor ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Mengembalikan konten gambar EMF ini sebagai teks biasa |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | Mengembalikan ImageType.Emf |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Membuang gambar EMF ini dengan membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Menyimpan gambar EMF ini ke file |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Menyimpan gambar EMF vektor ini menjadi gambar raster PNG |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Menyimpan gambar EMF vektor ini menjadi gambar SVG vektor |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan adalah gambar EMF yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar EMF yang valid |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Event, yang terjadi ketika gambar raster ini dibuang |

### Lihat Juga

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "ImageType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu format tipe gambar yang didukung, mendukung kedua format raster dan vektor."
type: docs
weight: 480
url: /id/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Mewakili satu tipe gambar yang didukung (format), mendukung format raster dan vektor.

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | Tipe gambar BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | Tipe gambar vektor EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Tipe gambar GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | Tipe gambar ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Tipe gambar JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | Tipe gambar PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | tipe gambar vektor SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | tipe gambar raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | tipe gambar Tidak Terdefinisi - nilai khusus, yang seharusnya tidak terjadi secara normal |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | tipe gambar vektor WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Ekstensi file (tanpa karakter titik di depan) dari tipe gambar tertentu dalam huruf kecil. Untuk tipe Tidak Terdefinisi mengembalikan string 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Mengembalikan nama formal dari format gambar ini. Tidak pernah mengembalikan NULL. Jika instance tidak rusak, tidak pernah melempar pengecualian. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Menunjukkan apakah format tertentu ini adalah vektor (true) atau raster (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Kode MIME dari tipe gambar tertentu sebagai string. Untuk tipe Tidak Terdefinisi mengembalikan string 'unsefined'. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Mengembalikan nilai ImageType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Mengembalikan nilai ImageType, yang setara dengan kode MIME yang ditentukan |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Menentukan apakah instance ini sama dengan instance "ImageType" yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast, yang kemungkinan adalah instance "ImageType" lain |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Mengembalikan hash-code, yang merupakan angka tak berubah untuk instance spesifik ini |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Mengembalikan properti FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Mendefinisikan apakah dua instance ImageType tertentu sama |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Mendefinisikan apakah dua instance ImageType tertentu tidak sama |

### Lihat Juga

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

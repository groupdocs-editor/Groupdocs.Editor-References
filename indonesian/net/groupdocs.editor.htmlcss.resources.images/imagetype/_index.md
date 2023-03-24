---
title: ImageType
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Mewakili satu jenis format gambar yang dapat didukung mendukung format raster dan vektor
type: docs
weight: 490
url: /id/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Mewakili satu jenis (format) gambar yang dapat didukung, mendukung format raster dan vektor

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | tipe gambar BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | Jenis gambar vektor EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Jenis gambar GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | jenis gambar ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Jenis gambar JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | tipe gambar PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | jenis gambar vektor SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | Tipe gambar raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Jenis gambar tidak terdefinisi - nilai khusus, yang seharusnya tidak terjadi secara normal |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | jenis gambar vektor WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Ekstensi file (tanpa karakter titik awal) dari jenis gambar tertentu dalam huruf kecil. Untuk tipe Undefined mengembalikan string 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Mengembalikan nama resmi dari format gambar ini. Jangan pernah mengembalikan NULL. Jika instance tidak rusak, jangan pernah melempar exception. |
| [Format](../../groupdocs.editor.htmlcss.resources.images/imagetype/format) { get; } | Deskripsi format gambar standar .NET dari format gambar tertentu, jika memiliki representasi khusus .NET. Untuk tipe Undefined mengembalikan nilai null. Untuk semua format, yang tidak terwakili dalam .NET, melempar InvalidOperationException. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Menunjukkan apakah format khusus ini adalah vektor (benar) atau raster (salah) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | kode MIME dari jenis gambar tertentu sebagai string. Untuk tipe Undefined mengembalikan string 'unsefined'. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Mengembalikan nilai ImageType, yang setara dengan ekstensi nama file, yang diekstraksi dari nama file yang ditentukan |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Mengembalikan nilai ImageType, yang setara dengan kode MIME yang ditentukan |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Menentukan apakah instance ini sama dengan instance "ImageType" yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak ditransmisikan, yang mungkin merupakan instance "ImageType" lainnya |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Mengembalikan kode hash, yang merupakan angka tetap untuk instance khusus ini |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Mengembalikan properti FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Menentukan apakah dua instance ImageType spesifik sama |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Menentukan apakah dua instance ImageType tertentu tidak sama |

### Lihat juga

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* ruang nama [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
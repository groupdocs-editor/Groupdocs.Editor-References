---
title: FixedLayoutFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merangkum semua format tata letak tetap juga dikenal sebagai halaman tetap yang mencakup PDF dan XPS ini tidak termasuk gambar raster
type: docs
weight: 80
url: /id/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Merangkum semua format tata letak tetap (juga dikenal sebagai "halaman tetap"), yang mencakup PDF dan XPS (ini tidak termasuk gambar raster)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Mengembalikan ekstensi (tanpa karakter titik awal) dari format tata letak tetap ini dalam huruf kecil |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Mengembalikan kode MIME untuk format ini |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Mengembalikan nama lengkap formal dari format tata letak tetap ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Mengembalikan instance dari[`FixedLayoutFormats`](../fixedlayoutformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Menentukan apakah instance ini sama dengan instance FixedLayoutFormats lain yang ditentukan |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang mungkin berupa FixedLayoutFormats berkotak |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Mengembalikan nama format khusus ini, sama dengan properti 'Nama' |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Memeriksa dua instance FixedLayoutFormats yang diberikan pada kesetaraan |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Mengembalikan nilai byte dari bidang dasar dari instance FixedLayoutFormats yang ditentukan (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Memeriksa dua instance FixedLayoutFormats yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan dari format file ini adalah untuk memperkenalkan standar representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | File XPS mewakili file tata letak halaman yang didasarkan pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. Ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format tata letak tetap yang ada |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk tipe FixedLayoutFormats |

### Perkataan

Berbagai aplikasi penampil atau penerbitan dokumen memungkinkan pengguna untuk membuka (Adobe Acrobat, XPS Viewer), dan terkadang mengedit dokumen (Adobe InDesign) dengan format tertentu. Aplikasi ini biasanya menghasilkan apa yang disebut dokumen format "halaman tetap". Format dokumen seperti itu menjelaskan dengan tepat di mana konten dokumen ditempatkan di setiap halaman. Secara internal, format PDF atau XPS berisi deskripsi setiap halaman, serta petunjuk menggambar, yang menentukan tata letak konten pada halaman tersebut. Ini mirip dengan format gambar, menjelaskan di mana konten ditampilkan baik dalam bentuk raster atau vektor.

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

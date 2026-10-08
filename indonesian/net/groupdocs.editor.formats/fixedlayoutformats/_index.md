---
title: "FixedLayoutFormats"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili format dokumen fixedlayout fixedpage seperti PDF yang tidak termasuk format gambar raster."
type: docs
weight: 100
url: /id/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

Mewakili format dokumen tata letak tetap (halaman tetap), seperti PDF, tidak termasuk format gambar raster.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Mendapatkan semua instance yang tersedia dari [`FixedLayoutFormats`](../fixedlayoutformats). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Mengambil sebuah instance [`FixedLayoutFormats`](../fixedlayoutformats) yang cocok dengan ekstensi file yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Secara eksplisit mengonversi string ekstensi file menjadi sebuah instance [`FixedLayoutFormats`](../fixedlayoutformats). |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF), yang diperkenalkan oleh Adobe, menyediakan representasi standar dokumen yang independen dari perangkat lunak, perangkat keras, dan sistem operasi. Untuk detail tambahan, lihat: [format file PDF](https://docs.fileformat.com/pdf/). |

### Catatan

Format fixed-layout secara tepat menentukan penempatan dan render konten pada setiap halaman. Umumnya digunakan dalam aplikasi penampilan, penerbitan, atau penyuntingan dokumen seperti Adobe Acrobat dan Adobe InDesign. Format ini secara internal mendefinisikan tata letak halaman dan posisi konten menggunakan grafik vektor dan instruksi teks.

### Lihat Juga

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

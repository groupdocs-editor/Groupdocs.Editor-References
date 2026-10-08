---
title: "FormatFamilies"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili berbagai keluarga format yang tersedia dalam sistem."
type: docs
weight: 110
url: /id/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Mewakili berbagai keluarga format yang tersedia dalam sistem.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | Mewakili keluarga format eBook. Pelajari lebih lanjut tentang format Mobi [di sini](https://docs.fileformat.com/ebook/mobi/), tentang format AZW3 [di sini](https://docs.fileformat.com/ebook/azw3/), dan tentang format ePub [di sini](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Mewakili keluarga format Email. Pelajari lebih lanjut tentang format email [di sini](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Mewakili keluarga format Fixed Layout. Berbagai aplikasi penampil atau penerbit dokumen memungkinkan pengguna membuka (Adobe Acrobat, XPS Viewer), dan kadang mengedit (Adobe InDesign) dokumen dengan format tertentu. Aplikasi-aplikasi ini biasanya menghasilkan dokumen format “fixed-page”. Format dokumen semacam itu secara tepat menggambarkan di mana konten dokumen ditempatkan pada setiap halaman. Secara internal, format PDF atau XPS berisi deskripsi setiap halaman, serta instruksi menggambar, yang menentukan tata letak konten pada halaman. Hal ini mirip dengan format gambar, yang menggambarkan di mana konten ditampilkan baik dalam bentuk raster maupun vektor. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Mewakili keluarga format Presentation. Pelajari lebih lanjut tentang format Presentation [di sini](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Mewakili keluarga format Spreadsheet. Semua format Spreadsheet biner, XML, dan teks (mengecualikan semua format berbasis delimiter teks dengan pemisah seperti CSV, TSV, dipisahkan dengan titik koma, dll.) yang dapat menyimpan buku kerja. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Mewakili keluarga format Tekstual. Mengenkapsulasi semua format tekstual (berbasis teks), termasuk markup (XML, HTML) dan lainnya. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Mewakili keluarga format Pengolah Kata. Pelajari lebih lanjut tentang format Pengolah Kata [di sini](https://wiki.fileformat.com/word-processing). |

### Lihat Juga

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

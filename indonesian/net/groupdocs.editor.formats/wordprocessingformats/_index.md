---
title: "WordProcessingFormats"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menyatukan semua format WordProcessing. Mencakup tipe file berikut"
type: docs
weight: 150
url: /id/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Mewakili semua format Pengolahan Kata. Menyertakan tipe file berikut:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Pelajari lebih lanjut tentang format Word Processing [di sini](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Mendapatkan koleksi enumerable dari semua [`WordProcessingFormats`](../wordprocessingformats). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Mengambil sebuah instance dari tipe [`WordProcessingFormats`](../wordprocessingformats) yang memiliki ekstensi file yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Mengonversi string yang mewakili ekstensi file menjadi objek [`WordProcessingFormats`](../wordprocessingformats). |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | File Office Open XML WordProcessingML Macro-Enabled Document (DOCM) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) adalah format yang terkenal untuk dokumen Microsoft Word. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Template MS Word 97-2007 (DOT) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML disimpan dalam file XML datar alih-alih paket ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | File Open Document Format Text Document (ODT) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format OpenDocument Text File. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) mewakili dokumen templat yang dihasilkan oleh aplikasi yang mematuhi format standar OpenDocument milik OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Format XML Microsoft Office Word 2003 — WordProcessingML atau WordML (.XML). |

### Lihat Juga

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

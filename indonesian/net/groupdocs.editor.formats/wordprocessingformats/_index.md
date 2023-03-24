---
title: WordProcessingFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Mengenkapsulasi semua format Pemrosesan Kata. Termasuk jenis file berikut Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Pelajari lebih lanjut tentang format Pemrosesan KataDi Sinihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /id/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Mengenkapsulasi semua format Pemrosesan Kata. Termasuk jenis file berikut: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Pelajari lebih lanjut tentang format Pemrosesan Kata[Di Sini](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Mengembalikan ekstensi (tanpa karakter titik awal) dari format Pemrosesan Kata ini dalam huruf kecil |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Mengembalikan kode MIME untuk format ini |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Mengembalikan nama lengkap formal dari format Pemrosesan Kata ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Mengembalikan instance dari[`WordProcessingFormats`](../wordprocessingformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang mungkin berupa WordProcessingFormats berkotak |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Menentukan apakah instance ini sama dengan instance WordProcessingFormats yang ditentukan lainnya |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Mengembalikan nama format khusus ini, sama dengan properti 'Nama' |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Memeriksa dua instance WordProcessingFormats yang diberikan pada kesetaraan |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Mengembalikan nilai byte dari bidang yang mendasari instance WordProcessingFormats yang ditentukan (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Memeriksa dua instance WordProcessingFormats yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | File Office Open XML WordProcessingML Macro-Enabled Document (DOCM) adalah dokumen yang dibuat Microsoft Word 2007 atau lebih tinggi dengan kemampuan untuk menjalankan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML Word Processing ML Macro-Free Document (DOCX) adalah format terkenal untuk dokumen Microsoft Word. Diperkenalkan dari tahun 2007 dengan dirilisnya Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Template MS Word 97-2007 adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) mewakili file template yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML disimpan dalam file XML datar, bukan paket ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | File Open Document Format Text Document (ODT) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang didasarkan pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) mewakili dokumen template yang dihasilkan oleh aplikasi yang sesuai dengan format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) mewakili metode pengkodean teks dan grafik yang diformat untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Format XML Microsoft Office Word 2003 — WordProcessingML atau WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format Pemrosesan Kata yang ada |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk tipe WordProcessingFormats |

### Perkataan

Kode MIME diambil dari sumber yang diberikan: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

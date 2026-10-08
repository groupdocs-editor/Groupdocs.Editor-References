---
title: "EBookFormats"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menyatukan semua format eBook. Menyertakan tipe file berikut Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /id/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Menyatukan semua format eBook. Menyertakan tipe file berikut: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Mendapatkan koleksi dapat diiterasi dari semua [`EBookFormats`](../ebookformats). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Mengambil sebuah instance dari tipe [`EBookFormats`](../ebookformats) yang memiliki ekstensi file yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Mengonversi string yang mewakili ekstensi file menjadi objek [`EBookFormats`](../ebookformats). |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, juga dikenal sebagai Kindle Format 8 (KF8), adalah versi modifikasi dari format file digital ebook AZW yang dikembangkan untuk perangkat Amazon Kindle. Format ini merupakan peningkatan dibandingkan file AZW lama. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Format Electronic Publication (IDPF ePub) adalah format file e-book yang menyediakan standar publikasi digital bagi penerbit dan konsumen. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI adalah nama yang diberikan pada format yang dikembangkan untuk MobiPocket Reader. Juga disebut PRC, AZW. Saat ini digunakan oleh Amazon dengan skema DRM yang sedikit berbeda dan disebut AZW. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/ebook/mobi/). |

### Catatan

Pelajari lebih lanjut tentang format Mobi [di sini](https://docs.fileformat.com/ebook/mobi/), tentang format AZW3 [di sini](https://docs.fileformat.com/ebook/azw3/), dan tentang format ePub [di sini](https://docs.fileformat.com/ebook/epub/).

### Lihat Juga

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

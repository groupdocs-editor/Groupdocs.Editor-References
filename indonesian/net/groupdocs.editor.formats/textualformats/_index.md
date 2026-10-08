---
title: "TextualFormats"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengkapsulkan semua format teks berbasis teks termasuk markup XML HTML dan lainnya. Menyertakan format berikut Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /id/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Mengkapsulkan semua format teks (berbasis teks), termasuk markup (XML, HTML) dan lainnya. Menyertakan format berikut: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Mendapatkan koleksi enumerable dari semua [`TextualFormats`](../textualformats). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Mengambil sebuah instance dari tipe [`TextualFormats`](../textualformats) yang memiliki ekstensi file yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Mengonversi string yang mewakili ekstensi file menjadi objek [`TextualFormats`](../textualformats). |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help adalah format biner bantuan online milik Microsoft, terdiri dari kumpulan halaman HTML, indeks, dan alat navigasi lainnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Dokumen HyperText Markup Language (HTML) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mentransmisikan data. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown adalah bahasa markup ringan untuk membuat teks terformat menggunakan editor teks biasa. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME encapsulation of aggregate HTML documents adalah format arsip halaman web yang digunakan untuk menggabungkan, dalam satu file komputer, kode HTML dan sumber daya pendampingnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Dokumen Teks Biasa (TXT) mewakili dokumen teks yang berisi teks biasa dalam bentuk baris. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | dokumen eXtensible Markup Language (XML) yang mirip dengan HTML tetapi berbeda dalam menggunakan tag untuk mendefinisikan objek. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/web/xml). |

### Lihat Juga

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

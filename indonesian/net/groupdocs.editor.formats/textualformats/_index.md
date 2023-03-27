---
title: TextualFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merangkum semua format tekstual berbasis teks termasuk markup XML HTML dan lainnya. Termasuk format berikut Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /id/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Merangkum semua format tekstual (berbasis teks), termasuk markup (XML, HTML) dan lainnya. Termasuk format berikut: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Mengembalikan ekstensi (tanpa karakter titik awal) dari format tekstual ini dalam huruf kecil |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Mengembalikan kode MIME untuk format ini |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Mengembalikan nama lengkap formal dari format tekstual ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Mengembalikan instance dari[`TextualFormats`](../textualformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang mungkin berupa TextualFormats kotak |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Menentukan apakah instance ini sama dengan instance TextualFormats yang ditentukan lainnya |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Mengembalikan nama format khusus ini, sama dengan properti 'Nama' |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Memeriksa dua instance TextualFormats yang diberikan pada kesetaraan |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Memeriksa dua instance TextualFormats yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help adalah format biner bantuan online milik Microsoft, yang terdiri dari kumpulan halaman HTML, indeks, dan alat navigasi lainnya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Dokumen HyperText Markup Language (HTML) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di browser. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mengirimkan data. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown adalah bahasa markup ringan untuk membuat teks berformat menggunakan editor teks biasa. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | Enkapsulasi MIME dari kumpulan dokumen HTML adalah format arsip halaman web yang digunakan untuk menggabungkan, dalam satu file komputer, kode HTML dan sumber pendampingnya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) merupakan dokumen teks yang berisi teks biasa dalam bentuk garis. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | dokumen Bahasa Markup eXtensible (XML) yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format Tekstual yang ada. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk TextualFormats type |

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

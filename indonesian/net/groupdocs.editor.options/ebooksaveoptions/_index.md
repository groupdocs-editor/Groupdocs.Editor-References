---
title: "EbookSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengizinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen dalam semua format eBook yang didukung: ePub, MOBI, dan AZW3."
type: docs
weight: 840
url: /id/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen dalam semua format e-Book yang didukung: ePub, MOBI, dan AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Konstruktor tanpa parameter ini membuat instance baru dari EbookSaveOptions dengan format output ePub (dapat diubah kemudian melalui properti [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Membuat instance baru dari [`EbookSaveOptions`](../ebooksaveoptions) dengan format output e-Book wajib yang ditentukan, sementara semua parameter lainnya menggunakan nilai default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Menentukan apakah akan mengekspor properti dokumen bawaan dan kustom dalam file hasil. Nilai default adalah `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Menentukan format file e-Book hasil: IDPF ePub, MOBI, atau AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | Menentukan tingkat maksimum heading yang akan dipisah pada file e-Book. Nilai default adalah `2`. Mengatur menjadi `0` akan menonaktifkan pemisahan, sehingga semua konten e-Book akan dimasukkan ke dalam satu paket di dalam file hasil. |

### Catatan

Format E-book yang didukung:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publikasi Elektronik)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "EbookEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan dan menyesuaikan opsi khusus untuk mengedit dokumen Ebook dalam semua format yang didukung seperti ePub, MOBI, dan AZW3."
type: docs
weight: 830
url: /id/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Memungkinkan untuk menentukan dan menyesuaikan opsi khusus untuk mengedit dokumen E-book dalam semua format yang didukung: ePub, MOBI, dan AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Menginisialisasi instance baru dari kelas [`EbookEditOptions`](../ebookeditoptions), di mana semua opsi diatur ke nilai default mereka |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Menginisialisasi instance baru dari kelas [`EbookEditOptions`](../ebookeditoptions) dengan mode pagination yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'. Opsi ini mungkin berguna untuk konversi bolak-balik dokumen multi-bahasa. Secara default opsi ini dinonaktifkan (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Memungkinkan mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. Secara default dinonaktifkan (`false`). |

### Catatan

Format E-book yang didukung:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publikasi Elektronik)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

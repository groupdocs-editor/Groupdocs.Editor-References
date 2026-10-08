---
title: "PdfEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen PDF"
type: docs
weight: 1050
url: /id/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen PDF

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Membuat dan mengembalikan instance baru dari kelas PdfEditOptions, di mana semua opsi diatur ke nilai default mereka |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Membuat dan mengembalikan instance baru dari kelas PdfEditOptions dengan pagination yang ditentukan dan semua opsi lainnya menggunakan nilai default |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Mengizinkan mengaktifkan (true) atau menonaktifkan (false) paginasi dalam dokumen HTML hasil. Secara default dinonaktifkan (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Mengizinkan penetapan rentang halaman untuk diproses. Secara default semua halaman dokumen fixed-layout diproses. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Mendapatkan atau mengatur flag yang menunjukkan apakah gambar harus dilewati saat mengonversi dokumen fixed-layout input ke HTML hasil. Default adalah false - gambar dipertahankan. |

### Lihat Juga

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

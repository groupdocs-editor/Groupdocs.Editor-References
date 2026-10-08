---
title: "EnablePagination"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML hasil. Secara default dinonaktifkan false."
type: docs
weight: 30
url: /id/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Memungkinkan mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. Secara default dinonaktifkan (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Catatan

Intinya, sebagian besar format e-book secara internal adalah format aliran seperti Office Open XML, di mana konten bersifat kontinu dan dibagi menjadi bab bukan halaman. Namun, ia berisi beberapa informasi spesifik halaman seperti nomor halaman, catatan kaki, header/footer, dan sebagainya. Beberapa pembaca e-book melakukan pemisahan konten e-book menjadi halaman, sementara yang lain (khususnya seluler) — tidak. Opsi ini memungkinkan mengontrol bagaimana konten e-book harus direpresentasikan dalam HTML/CSS saat diedit — dalam tampilan mengalir (`false`) atau berhalaman (`true`).

### Lihat Juga

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

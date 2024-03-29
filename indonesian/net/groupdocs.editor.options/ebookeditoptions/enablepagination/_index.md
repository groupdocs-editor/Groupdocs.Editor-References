---
title: EnablePagination
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Memungkinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. Secara default dinonaktifkan PALSU.
type: docs
weight: 30
url: /id/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Memungkinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. Secara default dinonaktifkan (`PALSU`).

```csharp
public bool EnablePagination { get; set; }
```

### Perkataan

Pada intinya sebagian besar format e-book secara internal adalah format aliran seperti Office Open XML, di mana kontennya padat dan dipecah menjadi beberapa bab tetapi bukan halaman. Namun, ini berisi beberapa info khusus halaman seperti nomor halaman, catatan kaki, herader/footer, dan sebagainya. Beberapa pembaca e-book melakukan pemisahan konten e-book ke halaman, sementara yang lain (terutama ponsel) — tidak. Opsi ini memungkinkan untuk mengontrol bagaimana konten e-book harus direpresentasikan dalam HTML/CSS saat mengedit — di float (`PALSU`) atau halaman (`BENAR`) melihat.

### Lihat juga

* class [EbookEditOptions](../../ebookeditoptions)
* ruang nama [GroupDocs.Editor.Options](../../ebookeditoptions)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

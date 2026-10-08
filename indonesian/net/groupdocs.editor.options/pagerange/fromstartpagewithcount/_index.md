---
title: "FromStartPageWithCount"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan dan memiliki jumlah halaman yang ditentukan atau jumlah halaman tak terbatas hingga akhir"
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan dan memiliki jumlah halaman yang ditentukan, atau jumlah halaman tak terbatas (hingga akhir).

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPageNumber | UInt16 | Nomor halaman, dari mana rentang halaman dimulai, secara inklusif. Nomor halaman dimulai dari 1, sehingga harus lebih besar dari nol |
| pageCount | UInt16 | Jumlah halaman, harus lebih besar dari nol. Jika nol - ini berarti semua halaman hingga akhir dokumen |

### Nilai Kembalian

Instansi PageRange baru

### Lihat Juga

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

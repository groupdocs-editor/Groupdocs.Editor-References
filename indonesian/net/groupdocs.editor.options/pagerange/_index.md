---
title: "PageRange"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengkapsulkan satu rentang halaman yang dapat memiliki batas terbuka atau tertutup. Secara default adalah sepenuhnya terbuka sehingga mencakup semua halaman yang ada. Penomoran halaman dimulai dari 1 bukan dari 0."
type: docs
weight: 1030
url: /id/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Mengkapsulkan satu rentang halaman, yang dapat memiliki batas terbuka atau tertutup. Secara default adalah "sepenuhnya terbuka" - mencakup semua halaman yang ada. Penomoran halaman dimulai dari 1, bukan dari 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Jumlah halaman dalam rentang. Jika 0 - rentang halaman meluas hingga akhir dokumen tanpa mempedulikan berapa banyak halaman yang termasuk. |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Nomor halaman akhir eksklusif, sampai mana rentang halaman ini berlanjut dan berhenti secara eksklusif. Jika 0 - rentang halaman meluas hingga akhir dokumen. |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Menunjukkan apakah instance ini mewakili rentang halaman default "sepenuhnya terbuka", yaitu mewakili semua halaman dokumen (true) atau tidak (false). |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Nomor halaman awal inklusif, dari mana rentang halaman ini dimulai. Jika 1 - rentang halaman dimulai dari halaman pertama dokumen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | Membuat rentang halaman yang dimulai dari halaman pertama dan memiliki jumlah halaman yang ditentukan. |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan dan berlanjut hingga akhir dokumen. |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan (inklusif) dan berlanjut hingga nomor halaman yang ditentukan (eksklusif). |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan dan memiliki jumlah halaman yang ditentukan, atau jumlah halaman tak terbatas (hingga akhir). |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Mendeteksi apakah instance PageRange ini sama dengan yang ditentukan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Mewakili semua halaman yang ada dalam dokumen. Nilai default. |

### Catatan

Struct tak dapat diubah yang mengenkapsulasi rentang halaman, yang tidak terkait dengan dokumen tertentu, dan dapat mewakili rentang halaman untuk dokumen apa pun.

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

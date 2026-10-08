---
title: "FromStartPageTillEndPage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan secara inklusif dan berlanjut hingga nomor halaman yang ditentukan secara eksklusif"
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Membuat rentang halaman yang dimulai dari nomor halaman yang ditentukan (inklusif) dan berlanjut hingga nomor halaman yang ditentukan (eksklusif).

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPageNumber | UInt16 | Nomor halaman, dari mana rentang halaman dimulai, secara inklusif. Nomor halaman dimulai dari 1, sehingga harus lebih besar dari nol |
| endPageNumber | UInt16 | Nomor halaman, hingga mana rentang halaman berlanjut, secara eksklusif. Nomor halaman dimulai dari 1, sehingga harus lebih besar dari nol, dan juga harus lebih besar secara ketat daripada *startPageNumber* |

### Lihat Juga

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

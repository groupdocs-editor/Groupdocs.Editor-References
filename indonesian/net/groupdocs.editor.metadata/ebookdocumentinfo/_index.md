---
title: EbookDocumentInfo
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merupakan metadata dari satu dokumen eBook
type: docs
weight: 710
url: /id/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Merupakan metadata dari satu dokumen e-Book

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Mengembalikan format e-Book ini |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Karena dokumen e-Book tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Mengembalikan jumlah halaman untuk MOBI atau AZW3 atau jumlah bab untuk ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte dari dokumen eBuku ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Menentukan apakah instance ini sama dengan instance EbookDocumentInfo lain yang ditentukan |

### Lihat juga

* interface [IDocumentInfo](../idocumentinfo)
* ruang nama [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

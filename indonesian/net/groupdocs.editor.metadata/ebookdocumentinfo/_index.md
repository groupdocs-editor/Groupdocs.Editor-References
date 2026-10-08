---
title: "EbookDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili metadata dari satu dokumen eBook"
type: docs
weight: 710
url: /id/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Mewakili metadata satu dokumen e-Book

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Mengembalikan format dari e-Book ini |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Karena dokumen e-Book tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Mengembalikan jumlah halaman dalam kasus MOBI atau AZW3 atau jumlah bab dalam kasus ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte dari dokumen eBook ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Menentukan apakah instance ini sama dengan instance EbookDocumentInfo lain yang ditentukan |

### Lihat Juga

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

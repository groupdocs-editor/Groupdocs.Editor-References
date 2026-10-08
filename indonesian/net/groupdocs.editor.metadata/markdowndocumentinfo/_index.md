---
title: "MarkdownDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili metadata satu dokumen Markdown"
type: docs
weight: 750
url: /id/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Mewakili metadata satu dokumen Markdown

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Mengembalikan format dokumen Markdown ini — selalu berupa [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Karena dokumen Markdown tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Mengembalikan jumlah halaman. Dokumen Markdown biasanya tidak memiliki halaman tetap dan oleh karena itu tidak ada jumlah halaman, sehingga angka ini dihitung dari ukuran halaman standar yang ditetapkan ke A4 dalam orientasi potret. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte dari dokumen Markdown ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Menentukan apakah instance ini sama dengan instance [`MarkdownDocumentInfo`](../markdowndocumentinfo) lain yang ditentukan. |

### Lihat Juga

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

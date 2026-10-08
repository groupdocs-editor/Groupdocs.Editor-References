---
title: "PageCount"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan jumlah halaman dalam kasus MOBI atau AZW3 atau jumlah bab dalam kasus ePub."
type: docs
weight: 30
url: /id/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Mengembalikan jumlah halaman dalam kasus MOBI atau AZW3 atau jumlah bab dalam kasus ePub.

```csharp
public int PageCount { get; }
```

### Catatan

Dokumen e-Book biasanya tidak memiliki halaman tetap sehingga tidak ada jumlah halaman. Pada ePub memungkinkan menghitung jumlah bab. Namun, format MOBI dan AZW3 juga tidak memiliki bab, sehingga angka ini dihitung dari ukuran halaman standar yang ditetapkan ke A4 dalam orientasi potret.

### Lihat Juga

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->

---
title: "PageCount"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "MOBI または AZW3 の場合はページ数を、ePub の場合は章数を返します。"
type: docs
weight: 30
url: /ja/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

MOBI または AZW3 の場合はページ数を、ePub の場合は章数を返します。

```csharp
public int PageCount { get; }
```

### 備考

e-Book ドキュメントは通常固定ページがなく、そのためページ数がありません。ePub の場合は章数を計算できますが、MOBI および AZW3 形式は章がないため、標準ページサイズ（縦向きの A4）から計算されます。

### 参照

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

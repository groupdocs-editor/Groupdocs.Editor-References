---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1つの eBook ドキュメントのメタデータを表します"
type: docs
weight: 710
url: /ja/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

1 つの e-Book ドキュメントのメタデータを表します

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | この e-Book の形式を返します |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | e-Book ドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | MOBI または AZW3 の場合はページ数を、ePub の場合は章数を返します。 |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | この eBook ドキュメントのサイズ（バイト）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | このインスタンスが指定された EbookDocumentInfo インスタンスと等しいかどうかを判定します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 つの Markdown ドキュメントのメタデータを表します"
type: docs
weight: 750
url: /ja/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

1 つの Markdown ドキュメントのメタデータを表します

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | この Markdown ドキュメントの形式を返します — 常に [`Md`](../../groupdocs.editor.formats/textualformats/md) です |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Markdown ドキュメントはパスワードで暗号化できないため、このプロパティは常に ``false`` を返します |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | ページ数を返します。Markdown ドキュメントは通常固定ページがなくページ数もないため、この数値は縦向きの A4 標準ページサイズから計算されます |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | この Markdown ドキュメントのサイズ（バイト単位）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | このインスタンスが指定された他の [`MarkdownDocumentInfo`](../markdowndocumentinfo) インスタンスと等しいかどうかを判定します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

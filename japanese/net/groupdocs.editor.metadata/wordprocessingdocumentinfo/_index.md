---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 つのワードプロセッシングドキュメントのメタデータを表します"
type: docs
weight: 790
url: /ja/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

1 つのワードプロセッシングドキュメントのメタデータを表します

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | この WordProcessing ドキュメントの形式を返します |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | この特定の WordProcessing ドキュメントが暗号化されており、開くためにパスワードが必要かどうかを判定します |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | ページ数を返します |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | この WordProcessing ドキュメントのサイズ（バイト単位）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | このインスタンスが指定された他の WordProcessingDocumentInfo インスタンスと等しいかどうかを判定します |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | 選択されたページのプレビューを SVG 画像として生成し、返します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

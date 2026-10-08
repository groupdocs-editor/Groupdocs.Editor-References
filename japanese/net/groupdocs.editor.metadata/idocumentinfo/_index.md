---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのファイルメタデータラッパーの共通インターフェイスです"
type: docs
weight: 740
url: /ja/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

すべてのファイルメタデータラッパーの共通インターフェイスです

```csharp
public interface IDocumentInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | 実装型では、1 つのフォーマットファミリを表し IDocumentFormat インターフェイスを継承する型から単一の値として文書形式を返す必要があります |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | 特定のファイルが暗号化されていて開く際にパスワードが必要かどうかを示します。暗号化できない文書タイプ（すべてのテキストベースなど）については、常に 'false' を返すべきです |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | 実装型では、ページ数やタブ、スライドなど、フォーマットに依存する類似エンティティの数（数値）を返す必要があります。プレーンテキスト文書や XML のように類似するものがないファミリタイプについては、1 を返すべきです |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | 文書のサイズ（バイト） |

### 参照

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

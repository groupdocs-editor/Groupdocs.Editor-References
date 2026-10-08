---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 つのプレゼンテーションドキュメントのメタデータを表します"
type: docs
weight: 760
url: /ja/net/groupdocs.editor.metadata/presentationdocumentinfo/
---
## PresentationDocumentInfo structure

1 つのプレゼンテーションドキュメントのメタデータを表します

```csharp
public struct PresentationDocumentInfo : IDocumentInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/presentationdocumentinfo/format) { get; } | このプレゼンテーション文書の形式を返します |
| [IsEncrypted](../../groupdocs.editor.metadata/presentationdocumentinfo/isencrypted) { get; } | この特定の Presentation ドキュメントが暗号化されており、開くためにパスワードが必要かどうかを示します |
| [PageCount](../../groupdocs.editor.metadata/presentationdocumentinfo/pagecount) { get; } | この Presentation ドキュメントのスライド数を返します |
| [Size](../../groupdocs.editor.metadata/presentationdocumentinfo/size) { get; } | この Presentation ドキュメントのサイズ（バイト単位）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GeneratePreview](../../groupdocs.editor.metadata/presentationdocumentinfo/generatepreview)(int) | 選択されたスライドのプレビューを SVG 画像として生成し、返します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

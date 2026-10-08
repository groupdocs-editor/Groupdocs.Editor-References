---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "XML、HTML、またはプレーンテキスト TXT のようなテキスト文書 1 件のメタデータを表します"
type: docs
weight: 780
url: /ja/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

XML、HTML、またはプレーンテキスト（TXT）のようなテキストドキュメント 1 件のメタデータを表します

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | テキスト文書の検出された推定エンコーディングを返します |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | このテキスト文書の形式を返します。場合によっては 100% 正確でないことがあります。 |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | テキスト文書は暗号化できないため、常に ``false`` を返します |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | 常に 1 を返します |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | このテキスト文書のサイズ（バイト数、文字数ではなく）を返します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

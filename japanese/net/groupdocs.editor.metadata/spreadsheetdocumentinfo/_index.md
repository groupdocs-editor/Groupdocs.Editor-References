---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 つのスプレッドシートドキュメントのメタデータを表します"
type: docs
weight: 770
url: /ja/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
## SpreadsheetDocumentInfo structure

1 つのスプレッドシートドキュメントのメタデータを表します

```csharp
public struct SpreadsheetDocumentInfo : IDocumentInfo, IEquatable<SpreadsheetDocumentInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/format) { get; } | この Spreadsheet ドキュメントの形式を返します |
| [IsEncrypted](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/isencrypted) { get; } | この特定の Spreadsheet ドキュメントが暗号化されており、開くためにパスワードが必要かどうかを示します |
| [PageCount](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/pagecount) { get; } | タブ数を返します |
| [Size](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/size) { get; } | この Spreadsheet ドキュメントのサイズ（バイト単位）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/equals#equals)(SpreadsheetDocumentInfo) | このインスタンスが指定された他の SpreadsheetDocumentInfo インスタンスと等しいかどうかを判定します |
| [GeneratePreview](../../groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview)(int) | 選択されたワークシートのプレビューを SVG 画像として生成し、返します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

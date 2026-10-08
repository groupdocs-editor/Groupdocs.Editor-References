---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Editor クラスに XLSX、ODS などのバイナリ Spreadsheet Cells Excel 互換ドキュメントを読み込むためのオプションを含みます"
type: docs
weight: 1120
url: /ja/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

XLS(X)、ODS などのバイナリスプレッドシート（Cells、Excel 互換）ドキュメントを Editor クラスに読み込むためのオプションを含みます。

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | デフォルトのパラメータなしコンストラクタ - すべてのパラメータはデフォルト値です |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | 入力ドキュメントの処理中にメモリ最適化機構を有効にします。これにより特定のケースでパフォーマンスが低下する可能性がありますが、代わりにメモリ使用量が減少します。巨大なドキュメントを処理し、OutOfMemoryException に直面する場合に有用です。デフォルトは false で、パフォーマンス向上のためメモリ最適化は無効になっています。 |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | エンコードされた Spreadsheet ドキュメントを開く際に使用されるパスワードを指定、変更、取得できます。パスワードを使用しない場合は NULL または空文字列に設定してください（デフォルト値）。 |

### 参照

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

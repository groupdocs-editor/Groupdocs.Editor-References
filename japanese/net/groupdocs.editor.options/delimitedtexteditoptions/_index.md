---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "区切り文字を使用するテキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を読み込むためのオプション"
type: docs
weight: 810
url: /ja/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

区切り文字（デリミタ）を使用するテキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を読み込むためのオプション

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | 必須の区切り文字（デリミタ）を指定して、区切りテキスト用オプションクラスのインスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | テキストベースのドキュメント内の文字列が日付データに変換されるかどうかを示す値を取得または設定します。デフォルトは `false` です。 |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | テキストベースのドキュメント内の文字列が数値データに変換されるかどうかを示す値を取得または設定します。デフォルトは `false` です。 |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | 入力ドキュメントの処理中にメモリ最適化機構を有効にします。これにより特定のケースでパフォーマンスが低下する可能性がありますが、メモリ使用量は減少します。巨大なドキュメントを処理し、OutOfMemoryException に直面する場合に有用です。デフォルトは `false`（パフォーマンス向上のためメモリ最適化は無効になっています）。 |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | テキストベースのスプレッドシートドキュメント用に文字列区切り文字（デリミタ）を指定できます |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | 連続する区切り文字を1つとして扱うかどうかを定義します。デフォルトは `false` です。 |

### 備考

https://en.wikipedia.org/wiki/Delimiter-separated_values

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

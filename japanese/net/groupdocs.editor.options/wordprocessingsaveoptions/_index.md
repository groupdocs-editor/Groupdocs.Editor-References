---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集後の WordProcessing 準拠ドキュメントの生成および保存のためにカスタムオプションを指定できます"
type: docs
weight: 1240
url: /ja/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

編集後の WordProcessing 準拠ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | このパラメータなしコンストラクタは DOCX 出力形式の WordProcessingSaveOptions の新しいインスタンスを作成します（その後 [`OutputFormat`](./outputformat) プロパティで変更可能です） |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | 指定された必須の WordProcessing 出力形式で WordProcessingSaveOptions の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトのままです |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | WordProcessing ドキュメントの保存に使用されるページネーションを有効または無効にできます。元のドキュメントがページネーションモードで開かれ編集されていた場合、このオプションも有効にする必要があります。デフォルトは無効です。 |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | 出力 WordProcessing ドキュメントにフォントリソースを埋め込むことを担当します。デフォルトではフォントは埋め込まれません (NotEmbed)。 |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | WordProcessing ドキュメントのデフォルトロケール (言語) を上書き設定できるようにします。作成時に適用されます。指定されない場合 (デフォルト値)、MS Word (または他のプログラム) は独自の設定やその他の要因に基づいてドキュメントのロケールを検出 (または選択) します。 |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | RTL (右から左) テキスト用の WordProcessing ドキュメントのロケール (言語) を上書き設定できるようにします。作成時に適用されます。指定されない場合 (デフォルト値)、MS Word (または他のプログラム) は独自の設定やその他の要因に基づいてドキュメントの RTL ロケールを検出 (または選択) します。 |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | 東アジアテキスト用の WordProcessing ドキュメントのロケール (言語) を上書きできるようにします。作成時に適用されます。指定されない場合 (デフォルト値)、MS Word (または他のプログラム) は独自の設定やその他の要因に基づいてドキュメントの東アジアロケールを検出 (または選択) します。 |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。このオプションを true に設定すると、大きなドキュメント生成時のメモリ消費を大幅に削減できますが、保存時間が遅くなります。デフォルトは false で、より高いパフォーマンスのためにメモリ最適化は無効になっています。 |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | ドキュメントの保存に使用される WordProcessing フォーマットを指定できるようにします |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | 生成された WordProcessing ドキュメントをエンコードするために使用されるパスワードを指定、変更、取得、または削除できるようにします。パスワードの削除 (クリーニング) には NULL または空文字列を指定してください。 |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | ドキュメント保護をサポートする任意のフォーマットの WordProcessing ドキュメントに対して、保護オプションを制御および適用できるようにします。デフォルトは NULL で、ドキュメント保護は使用されません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | この WordProcessingSaveOptions クラスのインスタンスの完全なコピーを作成して返します |

### 備考

WordProcessingSaveOptions は、編集されたドキュメント内容を含む EditableDocument クラスのインスタンスがあり、その内容を WordProcessing フォーマットの新しいドキュメントに保存する必要がある状況で適用されます。

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

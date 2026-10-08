---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "プレーンテキスト TXT ドキュメントを生成および保存するためのカスタムオプションを指定できるようにします。"
type: docs
weight: 1170
url: /ja/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

プレーンテキスト（TXT）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | プレーンテキスト形式でエクスポートする際に、各 BiDi ランの前に双方向マークを追加するかどうかを指定します。既定は 'false' で、BiDi マークは追加されません。 |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | テキストドキュメントの文字エンコーディングで、保存時に適用されます |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | プログラムがプレーンテキスト形式で保存する際にテーブルのレイアウトを保持しようとするかどうかを指定します。デフォルト値は false です。 |

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

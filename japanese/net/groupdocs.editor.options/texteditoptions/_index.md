---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "プレーンテキスト TXT ドキュメントの読み込みのためのカスタムオプションを指定できます"
type: docs
weight: 1150
url: /ja/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

プレーンテキスト（TXT）ドキュメントを読み込むためのカスタムオプションを指定できます。

```csharp
public class TextEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextEditOptions](texteditoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | 入力プレーンテキストドキュメントのテキストフロー方向を指定できます。デフォルトは左から右です。 |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | 結果の HTML ドキュメントでページネーションを有効または無効にできます。デフォルトは無効（false）です。 |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | テキストドキュメントを開く際に適用される文字エンコーディング |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | 先頭スペースの処理に関する優先オプションを取得または設定します。デフォルトでは先頭スペースを左インデントに変換します。 |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | ドキュメントがプレーンテキスト形式からインポートされる際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。 |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | 末尾の空白処理の優先オプションを取得または設定します。デフォルトではすべての末尾空白を切り捨てます。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

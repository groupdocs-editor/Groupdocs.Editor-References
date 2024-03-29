---
title: TextSaveOptions
second_title: GroupDocs.Editor for .NET API リファレンス
description: プレーン テキスト TXT ドキュメントを生成および保存するためのカスタム オプションを指定できます
type: docs
weight: 1160
url: /ja/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

プレーン テキスト (TXT) ドキュメントを生成および保存するためのカスタム オプションを指定できます

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | プレーン テキスト形式でエクスポートするときに、各 BiDi 実行の前に双方向マークを追加するかどうかを指定します。デフォルトは「false」です — BiDi マークを追加しません. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | 保存に適用されるテキスト ドキュメントの文字エンコード |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | プレーン テキスト形式で保存するときに、プログラムがテーブルのレイアウトを保持しようとするかどうかを指定します。デフォルト値は false. です。 |

### 関連項目

* interface [ISaveOptions](../isaveoptions)
* 名前空間 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

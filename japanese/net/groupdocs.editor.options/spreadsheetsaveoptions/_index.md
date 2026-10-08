---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Spreadsheet Excel 準拠ドキュメントの生成および保存のためのカスタムオプションを指定できるようにします"
type: docs
weight: 1130
url: /ja/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

スプレッドシート（Excel 準拠）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | このパラメータなしコンストラクタは、XLSX 出力フォーマットを使用した SpreadsheetSaveOptions の新しいインスタンスを作成します (その後 [`OutputFormat`](./outputformat) プロパティで変更可能です)。 |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | 指定された必須の Spreadsheet 出力フォーマットで SpreadsheetSaveOptions の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトになります |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | ブールフラグで、編集されたワークシートが [`WorksheetNumber`](./worksheetnumber) プロパティで指定された位置の元のスプレッドシート内の既存ワークシートを置き換えるか、既存ワークシートとその前のワークシートの間に挿入され、内容は置き換えられないかを指定します。デフォルトは false で、既存ワークシートが置き換えられます。[`WorksheetNumber`](./worksheetnumber) プロパティの値が '0' に設定されている場合、このプロパティは無視されます。 |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | ドキュメントの保存に使用される Spreadsheet フォーマットを指定できるようにします |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | パスワードを指定、変更、取得、または削除できるようにします。このパスワードは、生成された Spreadsheet ドキュメントをエンコードする際に使用されます（ドキュメント形式がパスワード保護に対応している場合）。パスワードの削除（クリーニング）には NULL または空文字列を指定してください。 |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | 既存のスプレッドシートのコピーに編集済みワークシートを挿入できるようにします（新しい単一ワークシートのスプレッドシートを作成する代わりのデフォルト動作）。WorksheetNumber は、Editor クラスで読み込まれたスプレッドシート内のワークシートの 1 ベース番号です。0（デフォルト値）の場合、新しいスプレッドシートは単一の編集済みワークシートで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なスプレッドシートが読み込まれていると、入力の EditableDocument インスタンスで表される編集済みワークシートがそのスプレッドシートに挿入されます。 |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | 保存時に、既存のスプレッドシートに編集済みワークシートが挿入される場合に削除すべきワークシートの 1 ベース番号の配列を指定できるようにします。 |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | 出力 Spreadsheet ドキュメントに対してワークシート保護を有効にできるようにします。デフォルトは NULL で、保護は適用されません。すべての形式がワークシート保護に対応しているわけではありません。 |

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

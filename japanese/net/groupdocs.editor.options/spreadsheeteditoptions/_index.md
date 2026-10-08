---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのサポート可能な Spreadsheet Excelcompatible フォーマットのドキュメントを編集するためのカスタムオプションを指定できます。"
type: docs
weight: 1110
url: /ja/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

すべてのサポート可能なスプレッドシート（Excel 互換）フォーマットのドキュメントを編集するためのカスタムオプションを指定できます。

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | 入力の Spreadsheet ドキュメントで非表示のワークシートを除外できるようにします。これにより完全に無視されます。デフォルトは false で、非表示のワークシートは利用可能で通常どおり処理されます。 |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | 有効にすると、生成された HTML ドキュメントの HTML テーブルに高さ 0 の空の下部非表示行が含まれ、セルは空ですが幅のみが指定されます。この空のセルを持つ行は各列の正確な幅値を保持し、HTML から Spreadsheet への逆変換を改善します。デフォルトでは有効 (`true`) です。 |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | 有効にすると、入力の Spreadsheet ドキュメントからの空の隣接水平セルが、対応する `colspan` 属性を持つ単一のセルに結合された状態で編集可能な HTML ドキュメントに表現されます。デフォルトでは無効 (`false`) です。 |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | 入力の Spreadsheet ドキュメントのワークシート（タブ）の 0 ベースインデックスを指定でき、HTML に変換される対象を決定します（備考参照）。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

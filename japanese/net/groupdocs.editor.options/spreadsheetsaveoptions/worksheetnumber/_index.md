---
title: "WorksheetNumber"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集されたワークシートを新しい単一ワークシートスプレッドシートを作成するデフォルトの動作ではなく、既存スプレッドシートのコピーに挿入できます。WorksheetNumber は Editor クラスで読み込まれたスプレッドシート内のワークシートの 1 ベース番号です。0 の場合はデフォルト値となり、単一の編集ワークシートを持つ新しいスプレッドシートが作成されます。0 以外の正または負の値で、かつ Editor クラスに有効なスプレッドシートが読み込まれている場合、入力の EditableDocument インスタンスで表される編集ワークシートがそのスプレッドシートに挿入されます。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

既存のスプレッドシートのコピーに編集済みワークシートを挿入できるようにします（新しい単一ワークシートのスプレッドシートを作成する代わりのデフォルト動作）。WorksheetNumber は、Editor クラスで読み込まれたスプレッドシート内のワークシートの 1 ベース番号です。0（デフォルト値）の場合、新しいスプレッドシートは単一の編集済みワークシートで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なスプレッドシートが読み込まれていると、入力の EditableDocument インスタンスで表される編集済みワークシートがそのスプレッドシートに挿入されます。

```csharp
public int WorksheetNumber { get; set; }
```

### 備考

WorksheetNumber 整数プロパティは、デフォルト状態（予約値 '0'）でない場合、ワークシート番号を表し、0 ではなく 1 から始まり、最大値はプレゼンテーション内のすべての既存スライド数です。ただし、指定された値がスライド総数を超える場合、GroupDocs.Editor は最後のワークシートになるよう調整します。負の値も使用でき、末尾からワークシートを数えます。たとえば "-1" はスプレッドシートの最後のワークシート、"-2" は最後から2番目、というようにです。正の値と同様に、負のワークシート番号がスプレッドシートの総ワークシート数を超える場合は、最初のワークシートに調整されます。[`InsertAsNewWorksheet`](../insertasnewworksheet) ブールプロパティはこれと密接に連動しています。

### 例

スプレッドシートに 5 つのワークシートがあるとします: WorksheetNumber = 0; — 指定されたスプレッドシートを無視し、新しいスプレッドシートを作成して編集ワークシートを配置します。 WorksheetNumber = 1; — 最初のワークシートを編集したものに置き換えます。 WorksheetNumber = 2; — 2 番目のワークシートを編集したものに置き換えます。 WorksheetNumber = 5; — 最後（5 番目）のワークシートを編集したものに置き換えます。 WorksheetNumber = 6; — 6 は 5 を超えるため調整され、最後（5 番目）のワークシートを編集したものに置き換えます。 WorksheetNumber = -1; — "-1" は「最後の既存」ワークシートを意味し、最後（5 番目）のワークシートを編集したものに置き換えます。 WorksheetNumber = -2; — 4 番目のワークシートを編集したものに置き換えます。 WorksheetNumber = -3; — 3 番目のワークシートを編集したものに置き換えます。 WorksheetNumber = -4; — 2 番目のワークシートを編集したものに置き換えます。 WorksheetNumber = -5; — 最初のワークシートを編集したものに置き換えます。 WorksheetNumber = -6; — "-6" は 5 を超えるため調整され、最初のワークシートを編集したものに置き換えます。

### 参照

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

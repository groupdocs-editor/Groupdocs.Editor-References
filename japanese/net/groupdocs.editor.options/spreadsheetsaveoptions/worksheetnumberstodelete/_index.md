---
title: "WorksheetNumbersToDelete"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集されたワークシートが既存のスプレッドシートに挿入される場合に、保存時に削除すべきワークシートの 1 ベース番号の配列を指定できます。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

保存時に、既存のスプレッドシートに編集済みワークシートが挿入される場合に削除すべきワークシートの 1 ベース番号の配列を指定できるようにします。

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### 備考

編集されたワークシートが新しい単一ワークシートのスプレッドシートとして保存されるのではなく（デフォルトの動作）、既存のスプレッドシートに保存される場合（[`WorksheetNumber`](../worksheetnumber) プロパティを使用）、この配列で番号を指定することで特定のワークシートを削除することも可能です。

デフォルトではこの配列は `null` で、ワークシートは削除されません。ただし、配列が null でなく空でもない場合、かつ有効なワークシート番号が少なくとも1つ含まれている場合、編集されたワークシートの内容で出力スプレッドシートドキュメントが生成された後、指定された番号のワークシートは出力ストリームまたはファイルに書き込む直前にスプレッドシートから削除されます。

この配列のワークシート番号は 1 ベースで、0 ベースではありません。無効な番号（1 未満またはワークシート総数を超える）は無視されます。

### 参照

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

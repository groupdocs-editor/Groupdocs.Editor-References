---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ブールフラグで、編集されたワークシートが元のスプレッドシート内の既存ワークシートを、WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber プロパティで指定された位置に置き換えるか、既存ワークシートとその前のワークシートの間に挿入して内容を置き換えないかを指定します。デフォルトは false で、既存のワークシートが置き換えられます。このプロパティは WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber プロパティの値が 0 に設定されている場合は無視されます。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

ブールフラグで、編集されたワークシートが元のスプレッドシート内の既存ワークシートを、[`WorksheetNumber`](../worksheetnumber) プロパティで指定された位置に置き換えるか、既存ワークシートとその前のワークシートの間に挿入して内容を置き換えないかを指定します。デフォルトは false — 既存のワークシートが置き換えられます。このプロパティは、[`WorksheetNumber`](../worksheetnumber) プロパティの値が '0' に設定されている場合は無視されます。

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### 備考

デフォルトではワークシートは置き換えられます。つまり、対象のスプレッドシートに5つのワークシートがあり、[`WorksheetNumber`](../worksheetnumber)=4 の場合、4番目のワークシートは新しい編集済みワークシートに置き換えられ、スプレッドシート内のワークシート総数（5）は変わりません。ただし、このプロパティの値が true に設定されている場合、新しい編集済みワークシートは4番目として挿入され、以降のワークシートはすべて末尾へシフトします。つまり、"old"4番目のワークシートは5番目になり、5番目は6番目となり、スプレッドシートのワークシート総数は1増えて6になります。

### 参照

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

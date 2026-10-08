---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "入力 Spreadsheet ドキュメントのワークシートタブの 0 ベースインデックスを指定でき、HTML に変換されます。備考をご参照ください。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

入力の Spreadsheet ドキュメントのワークシート（タブ）の 0 ベースインデックスを指定でき、HTML に変換される対象を決定します（備考参照）。

```csharp
public int WorksheetIndex { get; set; }
```

### 備考

ほとんどの Spreadsheet ドキュメントはタブの概念をサポートしており、複数タブを持つことができます。一方、HTML 形式はそのような構造をサポートしていません。そのため GroupDocs.Editor は入力ドキュメントの特定のタブのみを HTML に変換でき、このオプションでそのタブを指定できます。タブインデックスは 0 ベースで、負の値は許可されません。指定したインデックスがタブ数を超える場合は例外がスローされます。入力 Spreadsheet ドキュメントが 1 つのタブしか持たない場合、このオプションは無視されます。デフォルト値は 0（最初のタブ）です。

### 参照

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

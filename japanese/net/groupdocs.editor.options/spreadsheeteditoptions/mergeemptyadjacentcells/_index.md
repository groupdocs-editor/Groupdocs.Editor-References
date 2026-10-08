---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "有効にすると、入力 Spreadsheet ドキュメントの空の隣接する水平セルが、対応する colspan 属性を持つ単一のセルに結合された状態で編集可能な HTML ドキュメントに表現されます。デフォルトは無効（false）です。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

有効にすると、入力の Spreadsheet ドキュメントからの空の隣接水平セルが、対応する `colspan` 属性を持つ単一のセルに結合された状態で編集可能な HTML ドキュメントに表現されます。デフォルトでは無効 (`false`) です。

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### 備考

デフォルトでは GroupDocs.Editor は入力 Spreadsheet ドキュメントのテーブルを各セルを保持したまま出力 HTML ドキュメントに変換します。ただし、Spreadsheet ドキュメントはスパースになることがあり、たくさんの「空白領域」を含み、多くのセルが空です。このオプションを有効にすると、空のセルを `colspan` 属性を持つ `TD` 要素の1つに結合し、生成される HTML マークアップのサイズを大幅に削減できます。

### 参照

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

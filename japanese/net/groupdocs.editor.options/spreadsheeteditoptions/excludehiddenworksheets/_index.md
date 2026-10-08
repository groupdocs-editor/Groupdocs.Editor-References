---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "入力の Spreadsheet ドキュメントで非表示のワークシートを除外できるようにし、完全に無視されます。デフォルトは false で、非表示のワークシートは利用可能で通常通り処理されます。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

入力の Spreadsheet ドキュメントで非表示のワークシートを除外できるようにします。これにより完全に無視されます。デフォルトは false で、非表示のワークシートは利用可能で通常どおり処理されます。

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### 備考

いくつかのバイナリ Spreadsheet フォーマット（XLSX など）は非表示ワークシート（タブ）の概念をサポートしています。このようなフォーマットのドキュメントは、複数のワークシートがある場合、追加の非表示ワークシートを含むことがあります。デフォルトではこれらの非表示ワークシートは処理対象となりますが、このオプションを使用すると、これらを無視でき、非表示ワークシートが存在しないかのように扱われます。このオプションが有効な場合、'[`WorksheetIndex`](../worksheetindex)' プロパティで非表示ワークシートを選択することはできません。

### 参照

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->

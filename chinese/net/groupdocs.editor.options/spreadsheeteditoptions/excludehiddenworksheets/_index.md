---
title: ExcludeHiddenWorksheets
second_title: GroupDocs.Editor for .NET API 参考
description: 允许排除输入电子表格文档中的隐藏工作表因此它们将被完全忽略 默认值为 false  隐藏的工作表可用并正常处理
type: docs
weight: 20
url: /zh/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

允许排除输入电子表格文档中的隐藏工作表，因此它们将被完全忽略。 默认值为 false - 隐藏的工作表可用并正常处理。

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### 评论

几种二进制电子表格格式（如 XLSX）支持隐藏工作表（选项卡）概念。 这种格式的文档，如果它有一个以上的工作表，可能包含额外的隐藏工作表。 默认情况下，此类隐藏工作表可用于处理，但使用此选项可以忽略它们， 就像这些隐藏工作表不存在且不存在一样。启用此选项后，您无法选择带有 ' 的隐藏工作表[`WorksheetIndex`](../worksheetindex)财产.

### 也可以看看

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* 命名空间 [GroupDocs.Editor.Options](../../spreadsheeteditoptions)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

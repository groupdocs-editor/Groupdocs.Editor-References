---
title: InsertAsNewWorksheet
second_title: GroupDocs.Editor for .NET API 参考
description: 布尔标志指定编辑后的工作表是否应替换原始电子表格中由WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberproperty 或应在现有工作表和前一个工作表之间注入而不替换其内容 默认为 false  现有工作表将被替换如果值为WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber属性设置为0.
type: docs
weight: 20
url: /zh/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

布尔标志，指定编辑后的工作表是否应替换原始电子表格中由[`WorksheetNumber`](../worksheetnumber)property, 或应在现有工作表和前一个工作表之间注入，而不替换其内容。 默认为 false — 现有工作表将被替换。如果值为[`WorksheetNumber`](../worksheetnumber)属性设置为“0”.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### 评论

默认情况下，工作表被替换。这意味着如果给定的电子表格有 5 个工作表，并且[`WorksheetNumber`](../worksheetnumber)=4，则第 4 个工作表将被新编辑的工作表替换， 而电子表格 (5) 中的工作表总数将保持不变。 但是，如果此属性的值设置为真的，新编辑的工作表将作为第 4 个工作表注入，所有后续工作表将移到最后：“旧”第 4 个工作表变为第 5 个， 和第 5 个变为第 6 个，电子表格中的工作表总数将递增 1并等于 6。

### 也可以看看

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* 命名空间 [GroupDocs.Editor.Options](../../spreadsheetsaveoptions)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

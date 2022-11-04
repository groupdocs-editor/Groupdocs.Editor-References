---
title: SpreadsheetEditOptions
second_title: GroupDocs.Editor for .NET API 参考
description: 允许为编辑所有支持的电子表格Excel 兼容格式的文档指定自定义选项
type: docs
weight: 890
url: /zh/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

允许为编辑所有支持的电子表格（Excel 兼容）格式的文档指定自定义选项

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | 允许在输入电子表格文档中排除隐藏的工作表，因此它们将被完全忽略。 默认为 false - 隐藏的工作表可用并正常处理。 |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | 允许指定输入电子表格文档的工作表（选项卡）的从 0 开始的索引，应将其转换为 HTML（见备注）。 |

### 也可以看看

* interface [IEditOptions](../ieditoptions)
* 命名空间 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
---
title: SpreadsheetFormats
second_title: GroupDocs.Editor for .NET API 参考
description: 封装所有二进制XML 和文本电子表格格式不包括所有基于文本分隔符的格式如 CSVTSV分号分隔等可以在其中保存工作簿 包括以下格式 Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . 了解有关电子表格格式的更多信息这里https//wiki.fileformat.com/spreadsheet.
type: docs
weight: 130
url: /zh/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

封装所有二进制、XML 和文本电子表格格式（不包括所有基于文本分隔符的格式，如 CSV、TSV、分号分隔等），可以在其中保存工作簿。 包括以下格式： [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . 了解有关电子表格格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet).

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | 以小写形式返回此电子表格格式的扩展名（不带前导点字符） |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | 返回此格式的 MIME 代码 |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | 返回此电子表格格式的正式全名 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | 返回实例[`SpreadsheetFormats`](../spreadsheetformats)结构，关联到指定的文件扩展名，或者如果扩展名无法正确解析，则抛出异常 |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | 确定此实例是否等于其他指定的 IDocumentFormat 实例 |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | 确定此实例是否等于另一个指定对象，可能是装箱的 SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | 确定此实例是否等于其他指定的 SpreadsheetFormats 实例 |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | 返回一个哈希码，对于这个实例是不可变的 |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | 检查两个给定的 SpreadsheetFormats 实例是否相等 |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | 在不等式 上检查两个给定的 SpreadsheetFormats 实例 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | 逗号分隔值 (CSV) 文档表示纯文本，其中包含具有逗号分隔值的数据记录。 CSV 文件中的每一行都是文件中包含的记录集中的一条新记录。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | 数据交换格式 (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | 平面 OpenDocument 电子表格 (FODS) — 存储为单个未压缩的 XML 文档 |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument 电子表格 (ODS) 代表用户可编辑的 OpenDocument 电子表格文档格式。数据在 ODF 文件中存储为行和列。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 和 Excel 2003 XML 格式 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice 或 OpenOffice.org Calc XML 电子表格 (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | 制表符分隔值 (TSV) 文件格式表示用纯文本格式的制表符分隔的数据。该文件格式类似于 CSV，用于以结构化方式组织数据，以便在不同应用程序之间导入和导出。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel 插件 (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 二进制文件格式 (XLS) 表示可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建的文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel 二进制工作簿 (XLSB) 指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) 是一种支持宏的电子表格文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) 表示 Microsoft 在 Microsoft Office 2007 发行版中引入的文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 模板 (XLT) 表示使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是作为 Microsoft Office 套件的一部分提供的电子表格应用程序。 Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML 模板已启用宏 (XLTM) 表示由 Microsoft Excel 生成的文件作为启用宏的模板文件。 XLTM 文件在结构上与 XLTX 相似，只是后者不支持使用宏创建模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML 模板无宏 (XLTX) 文件表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建一个标准模板文件，该文件可用于生成 XLSX 文件，这些文件具有与 XLTX 文件中指定的相同的设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltx) |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | 返回一个内部类，它为所有现有的电子表格格式提供了可枚举的可能性 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | 实现 IEnumerable 通用接口，为 SpreadsheetFormats 类型启用“foreach”可能性 |

### 也可以看看

* interface [IDocumentFormat](../idocumentformat)
* 命名空间 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

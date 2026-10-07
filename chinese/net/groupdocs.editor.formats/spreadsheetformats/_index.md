---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for .NET API 参考"
description: "封装所有二进制 XML 和文本电子表格格式，排除所有使用分隔符如 CSV、TSV、分号分隔等的文本分隔符格式，可用于保存工作簿。包括以下格式 Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. 了解更多关于电子表格格式的信息，请访问herehttps//wiki.fileformat.com/spreadsheet。"
type: docs
weight: 130
url: /zh/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

封装所有二进制、XML 和文本电子表格格式（排除所有使用分隔符如 CSV、TSV、分号分隔等的文本分隔符格式），可用于保存工作簿。包括以下格式：[`Xls`](./xls)、[`Xlt`](./xlt)、[`Xlsx`](./xlsx)、[`Xlsm`](./xlsm)、[`Xlsb`](./xlsb)、[`Xltx`](./xltx)、[`Xltm`](./xltm)、[`Xlam`](./xlam)、[`SpreadsheetML`](./spreadsheetml)、[`Ods`](./ods)、[`Fods`](./fods)、[`Sxc`](./sxc)、[`Dif`](./dif)、[`Csv`](./csv)、[`Tsv`](./tsv)。了解更多关于电子表格格式的信息，请访问[here](https://wiki.fileformat.com/spreadsheet)。

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 获取文档格式的文件扩展名。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 获取文档格式所属的格式族。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 获取格式族的唯一标识符。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 获取文档格式的 MIME 类型。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 获取格式族的名称。 |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | 获取所有 [`SpreadsheetFormats`](../spreadsheetformats) 的可枚举集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | 检索具有指定文件扩展名的指定类型 [`SpreadsheetFormats`](../spreadsheetformats) 实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 确定此实例是否等于指定的 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 确定此实例是否等于指定的 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 实例。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 确定此实例是否等于指定的 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 返回当前对象的哈希码。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 返回表示当前对象的字符串。 |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | 将表示文件扩展名的字符串转换为 [`SpreadsheetFormats`](../spreadsheetformats) 对象。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | 逗号分隔值（CSV）。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/spreadsheet/csv/)。 |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | 数据交换格式（DIF）。 |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | 平面 OpenDocument 电子表格（FODS）。 |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument 电子表格（ODS）。了解更多关于此文件格式的信息，请访问[here](https://wiki.fileformat.com/spreadsheet/ods)。 |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 和 Excel 2003 XML 格式。 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice 或 OpenOffice.org Calc XML 电子表格（SXC）。 |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | 制表符分隔值（TSV）。了解更多关于此文件格式的信息，请访问[here](https://docs.fileformat.com/spreadsheet/tsv/)。 |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel 加载项（XLAM）。 |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 二进制文件格式 (XLS)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xls)。 |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel 二进制工作簿 (XLSB)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsb)。 |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML 工作簿（启用宏） (XLSM)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsm)。 |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML 工作簿（无宏） (XLSX)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsx)。 |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 模板 (XLT)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlt)。 |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML 模板（启用宏） (XLTM)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltm)。 |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML 模板（无宏） (XLTX)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltx)。 |

### 另请参见

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

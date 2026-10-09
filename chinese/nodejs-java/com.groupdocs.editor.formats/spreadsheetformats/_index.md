---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装所有二进制、XML 和文本电子表格格式，排除所有使用逗号、制表符、分号等分隔符的文本分隔格式（如 CSV、TSV、分号分隔等），可用于保存工作簿。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

封装所有二进制、XML 和文本电子表格格式（排除所有使用分隔符的文本分隔格式，如 CSV、TSV、分号分隔等），可用于保存工作簿。
包括以下格式：
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
了解更多关于电子表格格式 [此处](../https://wiki.fileformat.com/spreadsheet)。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 二进制文件格式 (XLS)。 |
|
|  | [Xlt](#Xlt) | Excel 97-2003 模板 (XLT)。 |
|
|  | [Xlsx](#Xlsx) | Office Open XML 工作簿（无宏） (XLSX)。 |
|
|  | [Xlsm](#Xlsm) | Office Open XML 工作簿（启用宏） (XLSM)。 |
|
|  | [Xlsb](#Xlsb) | Excel 二进制工作簿 (XLSB)。 |
|
|  | [Xltx](#Xltx) | Office Open XML 模板（无宏） (XLTX)。 |
|
|  | [Xltm](#Xltm) | Office Open XML 模板（启用宏） (XLTM)。 |
|
|  | [Xlam](#Xlam) | Excel 加载项 (XLAM)。 |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Microsoft Office Excel 2002 和 Excel 2003 XML 格式。 |
|
|  | [Ods](#Ods) | OpenDocument 电子表格 (ODS)。 |
|
|  | [Fods](#Fods) | Flat OpenDocument 电子表格 (FODS)。 |
|
|  | [Sxc](#Sxc) | StarOffice 或 OpenOffice.org Calc XML 电子表格 (SXC)。 |
|
|  | [Dif](#Dif) | 数据交换格式 (DIF)。 |
|
|  | [Csv](#Csv) | 逗号分隔值 (CSV)。 |
|
|  | [Tsv](#Tsv) | 制表符分隔值 (TSV)。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 对象。 |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 二进制文件格式 (XLS)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 模板 (XLT)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML 工作簿（无宏） (XLSX)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML 工作簿（启用宏） (XLSM)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel 二进制工作簿 (XLSB)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML 模板（无宏） (XLTX)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML 模板（启用宏） (XLTM)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel 加载项 (XLAM)。


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \\u2014 Microsoft Office Excel 2002 和 Excel 2003 XML 格式。


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument 电子表格 (ODS)。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument 电子表格 (FODS)。


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice 或 OpenOffice.org Calc XML 电子表格 (SXC)。


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


数据交换格式 (DIF)。


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


逗号分隔值 (CSV)。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


制表符分隔值 (TSV)。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


获取所有 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 的可枚举集合。
值：包含所有 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 实例的 IEnumerable{SpreadsheetFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点后的部分。 |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


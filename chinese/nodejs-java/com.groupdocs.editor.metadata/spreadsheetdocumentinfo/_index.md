---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一个电子表格文档的元数据"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

表示一个电子表格文档的元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此 Spreadsheet 文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 返回标签页数量 |
|
|  | [getSize()](#getSize--) | 返回此 Spreadsheet 文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 指示此特定的 Spreadsheet 文档是否已加密并 |
需要密码才能打开
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | 生成并返回所选工作表的 SVG 图像预览 |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | 确定此实例是否等于指定的另一个实例 |
SpreadsheetDocumentInfo 实例
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


返回此 Spreadsheet 文档的格式


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


返回标签页数量


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此 Spreadsheet 文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


指示此特定的 Spreadsheet 文档是否已加密并
需要密码才能打开


**Returns:**
布尔
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


生成并返回所选工作表的 SVG 图像预览


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | worksheetIndex | int | 所需工作表的 0 基索引。不能小于 0，且不能超过此电子表格中的工作表数量。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


确定此实例是否等于指定的另一个实例
SpreadsheetDocumentInfo 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | 其他 SpreadsheetDocumentInfo 实例，应与此进行相等性检查 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false


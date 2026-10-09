---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示具有固定布局格式（如 PDF 或 XPS）的文档的元数据"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

表示具有固定布局格式（如 PDF 或 XPS）的文档的元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此固定布局格式文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 返回页数 |
|
|  | [getSize()](#getSize--) | 返回此固定布局格式文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 确定此特定固定布局格式文档是否已加密并需要密码打开 |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | 确定此实例是否等于指定的其他 FixedLayoutDocumentInfo 实例 |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


返回此固定布局格式文档的格式


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


返回页数


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此固定布局格式文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


确定此特定固定布局格式文档是否已加密并需要密码打开


**Returns:**
布尔
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


确定此实例是否等于指定的其他 FixedLayoutDocumentInfo 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | 其他 FixedLayoutDocumentInfo 实例，应与此进行相等性检查 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false


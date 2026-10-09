---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一本电子书文档的元数据"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

表示一本电子书文档的元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 在 MOBI 或 AZW3 情况下返回页数，在 ePub 情况下返回章节数。 |
|
|  | [getSize()](#getSize--) | 返回此电子书文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 由于电子书文档无法使用密码加密，此属性始终返回 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | 确定此实例是否等于另一个指定的 EbookDocumentInfo 实例 |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


返回此文档的格式


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


在 MOBI 或 AZW3 情况下返回页数，在 ePub 情况下返回章节数。

<br />

*** ** * ** ***

电子书文档通常没有固定的页面，因此也没有页数。对于 ePub 可以计算章节数量。然而，MOBI 和 AZW3 格式同样没有章节，因此该数字是根据设置为纵向 A4 的标准页面大小计算的。

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此电子书文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


由于电子书文档无法使用密码加密，此属性始终返回 'false'


**Returns:**
布尔
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


确定此实例是否等于另一个指定的 EbookDocumentInfo 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | 另一个应与此进行相等性检查的 EbookDocumentInfo 实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false


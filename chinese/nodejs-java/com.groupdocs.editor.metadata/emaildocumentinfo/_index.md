---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示任意受支持电子邮件格式的电子邮件文档的元数据"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

表示任意受支持电子邮件格式的电子邮件文档的元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此电子邮件文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 始终返回 1，因为电子邮件文档没有分页视图 |
|
|  | [getSize()](#getSize--) | 返回此电子邮件文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 由于电子邮件文档无法使用密码加密，此属性始终返回 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | 确定此实例是否等于指定的其他 EmailDocumentInfo 实例 |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


返回此电子邮件文档的格式


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


始终返回 1，因为电子邮件文档没有分页视图


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此电子邮件文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


由于电子邮件文档无法使用密码加密，此属性始终返回 'false'


**Returns:**
布尔
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


确定此实例是否等于指定的其他 EmailDocumentInfo 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | 其他 EmailDocumentInfo 实例，应与此进行相等性检查 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false


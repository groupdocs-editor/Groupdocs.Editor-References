---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一个 Markdown 文档的元数据"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

表示一个 Markdown 文档的元数据

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此 Markdown 文档的格式 \\u2014 始终是 |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | 返回页数。 |
|
|  | [getSize()](#getSize--) | 返回此 Markdown 文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 由于 Markdown 文档无法使用密码加密，此 |
属性始终返回 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | 确定此实例是否等于指定的另一个实例 |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


返回此 Markdown 文档的格式 \\u2014 始终是
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


返回页数。Markdown 文档通常没有固定页数
因此页数是根据标准页面尺寸计算的
设置为纵向 A4 纸张。


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此 Markdown 文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


由于 Markdown 文档无法使用密码加密，此
属性始终返回 'false'


**Returns:**
布尔
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


确定此实例是否等于指定的另一个实例
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | 另一个 [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) 实例，应与此进行相等性检查 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false


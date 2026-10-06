---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示 Markdown 文档的元数据"
type: docs
weight: 13
url: /zh/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

表示 Markdown 文档的元数据

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此 Markdown 文档的格式 \u2014 总是如此 |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | 返回页数。 |
|
|  | [getSize()](#getSize--) | 返回此 Markdown 文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 由于 Markdown 文档无法使用密码加密，这 |
属性始终返回 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | 确定此实例是否等于指定的另一个实例 |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


返回此 Markdown 文档的格式 \u2014 总是如此
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


返回页数。Markdown 文档通常没有固定的页面
因此页数是基于标准页面尺寸计算的
设置为纵向 A4。


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


由于 Markdown 文档无法使用密码加密，这
属性始终返回 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


确定此实例是否等于指定的另一个实例
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | 其他 [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) 实例，应与此进行相等性检查 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false


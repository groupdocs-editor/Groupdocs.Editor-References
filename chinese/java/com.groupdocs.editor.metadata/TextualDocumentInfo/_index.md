---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示一个文本文档的元数据，例如 XML、HTML 或纯文本 TXT"
type: docs
weight: 16
url: /zh/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

表示一个文本文档的元数据，例如 XML、HTML 或纯文本
(TXT)

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此文本文档的格式。 |
|
|  | [getPageCount()](#getPageCount--) | 始终返回 1 |
|
|  | [getSize()](#getSize--) | 返回此文本的字节大小（而非字符数） |
文档
|
|  | [isEncrypted()](#isEncrypted--) | 始终返回 'false'，因为文本文档无法加密。 |
|
|  | [getEncoding()](#getEncoding--) | 返回检测到的文本文件的可能编码 |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


返回此文本文档的格式。可能在以下情况下并非 100% 正确
某些情况下。


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


始终返回 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此文本的字节大小（而非字符数）
文档


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


始终返回 'false'，因为文本文档无法加密。


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


返回检测到的文本文件的可能编码


**Returns:**
java.nio.charset.Charset

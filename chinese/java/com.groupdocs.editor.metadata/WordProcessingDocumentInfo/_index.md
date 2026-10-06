---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示文字处理文档的元数据"
type: docs
weight: 17
url: /zh/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

表示文字处理文档的元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此 WordProcessing 文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 返回页数 |
|
|  | [getSize()](#getSize--) | 返回此 WordProcessing 文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 确定此特定 WordProcessing 文档是否已加密且 |
需要密码才能打开
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | 生成并返回所选页面的 SVG 图像预览 |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | 确定此实例是否等于指定的另一个实例 |
WordProcessingDocumentInfo 实例
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


返回此 WordProcessing 文档的格式


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
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


返回此 WordProcessing 文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


确定此特定 WordProcessing 文档是否已加密且
需要密码才能打开


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


生成并返回所选页面的 SVG 图像预览


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageIndex | int | 所需页面的 0 基索引。不能小于 0，且不能超过此 WordProcessing 文档中的页数。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


确定此实例是否等于指定的另一个实例
WordProcessingDocumentInfo 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | 其他 WordProcessingDocumentInfo 实例，应与此实例进行相等性检查 |
|

**Returns:**
boolean - 如果相等则为 True，若不相等则为 false


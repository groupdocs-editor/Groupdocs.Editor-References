---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一个演示文稿文档的元数据"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

表示一个演示文稿文档的元数据

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 返回此 Presentation 文档的格式 |
|
|  | [getPageCount()](#getPageCount--) | 返回此 Presentation 文档中的幻灯片数量 |
|
|  | [getSize()](#getSize--) | 返回此 Presentation 文档的字节大小 |
|
|  | [isEncrypted()](#isEncrypted--) | 指示此特定的 Presentation 文档是否已加密并需要密码才能打开 |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | 生成并返回所选幻灯片的 SVG 图像预览 |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


返回此 Presentation 文档的格式


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


返回此 Presentation 文档中的幻灯片数量


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


返回此 Presentation 文档的字节大小


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


指示此特定的 Presentation 文档是否已加密并需要密码才能打开


**Returns:**
布尔
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


生成并返回所选幻灯片的 SVG 图像预览


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | slideIndex | int | 所需幻灯片的 0 基索引。不能小于 0，且不能超过此演示文稿中的幻灯片数量。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class


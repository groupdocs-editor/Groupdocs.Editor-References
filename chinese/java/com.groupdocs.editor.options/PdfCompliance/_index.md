---
title: "PdfCompliance"
second_title: "GroupDocs.Editor for Java API 参考"
description: "指定 PDF 标准合规级别。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

指定 PDF 标准合规级别。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7（ISO 32000-1）标准 |
|
|  | [Pdf20](#Pdf20) | PDF 2.0（ISO 32000-2）标准 |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a 标准。 |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b（ISO 19005-1）。 |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a（ISO 19005-2）标准。 |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u（ISO 19005-2）标准。 |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1（ISO 14289-1）标准。 |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7（ISO 32000-1）标准


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0（ISO 32000-2）标准


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a 标准。此级别包括 PDF/A-1b 的所有要求，并额外要求包含文档结构
（也称为 "tagged"），其目的是确保文档内容可被搜索和重新利用。

<br />

*** ** * ** ***

请注意，导出文档结构会显著增加内存消耗，尤其是对于大型文档。

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b（ISO 19005-1）。PDF/A-1b 的目标是确保文档视觉外观的可靠再现。


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a（ISO 19005-2）标准。此级别包括 PDF/A-2u 的所有要求，并额外要求包含文档结构（也称为“标记”），其目标是确保文档内容可被搜索和重新利用。

<br />

*** ** * ** ***

请注意，导出文档结构会显著增加内存消耗，尤其是对于大型文档。

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u（ISO 19005-2）标准。PDF/A-2u 的目标是随时间保持文档静态视觉外观，独立于用于创建、存储或渲染文件的工具和系统。此外，文档中包含的任何文本都可以可靠地提取为一系列 Unicode 码点。


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1（ISO 14289-1）标准。PDF/UA 的主要目的是定义如何以可访问的方式在 PDF 格式中表示电子文档。



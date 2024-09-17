---
title: PdfCompliance
second_title: GroupDocs.Editor for Java API Reference
description: Specifies the PDF standards compliance level
type: docs
weight: 28
url: /java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

Specifies the PDF standards compliance level
## Fields

| Field | Description |
| --- | --- |
| [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) standard |
| [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) standard |
| [PdfA1a](#PdfA1a) | PDF/A-1a standard. |
| [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
| [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) standard. |
| [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) standard. |
| [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) standard. |
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) standard

### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) standard

### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a standard. This level includes all the requirements of PDF/A-1b and additionally requires that document structure be included (also known as being "tagged"), with the objective of ensuring that document content can be searched and repurposed.

--------------------

Note that exporting the document structure significantly increases the memory consumption, especially for the large documents.

### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b has the objective of ensuring reliable reproduction of the visual appearance of the document.

### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) standard. This level includes all the requirements of PDF/A-2u and additionally requires that document structure be included (also known as being "tagged"), with the objective of ensuring that document content can be searched and repurposed.

--------------------

Note that exporting the document structure significantly increases the memory consumption, especially for the large documents.

### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) standard. PDF/A-2u has the objective of preserving document static visual appearance over time, independent of the tools and systems used for creating, storing or rendering the files. Additionally any text contained in the document can be reliably extracted as a series of Unicode codepoints.

### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) standard. The primary purpose of PDF/UA is to define how to represent electronic documents in the PDF format in a manner that allows the file to be accessible.


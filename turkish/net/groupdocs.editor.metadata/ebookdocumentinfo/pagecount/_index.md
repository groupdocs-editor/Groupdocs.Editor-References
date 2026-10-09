---
title: "PageCount"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "MOBI veya AZW3 durumunda sayfa sayısını, ePub durumunda ise bölüm sayısını döndürür."
type: docs
weight: 30
url: /tr/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

MOBI veya AZW3 durumunda sayfa sayısını, ePub durumunda ise bölüm sayısını döndürür.

```csharp
public int PageCount { get; }
```

### Açıklamalar

e-Book belgeleri genellikle sabit sayfalara sahip değildir ve bu nedenle sayfa sayısı yoktur. ePub durumunda bölüm sayısını hesaplamak mümkündür. Ancak MOBI ve AZW3 formatlarında da bölüm bulunmadığından, bu sayı dikey yönde A4 olarak ayarlanmış standart sayfa boyutundan hesaplanır.

### Ayrıca Bakınız

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

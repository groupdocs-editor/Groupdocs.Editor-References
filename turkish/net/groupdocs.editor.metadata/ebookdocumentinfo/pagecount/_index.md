---
title: PageCount
second_title: .NET API Başvurusu için GroupDocs.Editor
description: MOBI veya AZW3 durumunda sayfa sayısını veya ePub. durumunda bölüm sayısını döndürür
type: docs
weight: 30
url: /tr/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

MOBI veya AZW3 durumunda sayfa sayısını veya ePub. durumunda bölüm sayısını döndürür

```csharp
public int PageCount { get; }
```

### Notlar

e-Kitap belgelerinin genellikle sabit sayfaları yoktur ve dolayısıyla sayfa sayısı vardır. ePub durumunda, birkaç bölüm hesaplamak mümkündür. Ancak, MOBI ve AZW3 formatlarında da bölüm yoktur, dolayısıyla bu sayı dikey yönde A4 olarak ayarlanan standart sayfa boyutundan hesaplanır.

### Ayrıca bakınız

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* ad alanı [GroupDocs.Editor.Metadata](../../ebookdocumentinfo)
* toplantı [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
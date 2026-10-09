---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir eKitap belgesinin meta verilerini temsil eder"
type: docs
weight: 710
url: /tr/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Bir e‑Kitap belgesinin meta verilerini temsil eder

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Bu e-Book'un formatını döndürür |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | e-Book belgeleri parola ile şifrelenemediği için bu özellik her zaman 'false' döndürür |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | MOBI veya AZW3 durumunda sayfa sayısını, ePub durumunda ise bölüm sayısını döndürür. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Bu eKitap belgesinin bayt cinsinden boyutunu döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Bu örneğin, belirtilen diğer EbookDocumentInfo örneğiyle eşit olup olmadığını belirler. |

### Ayrıca Bakınız

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

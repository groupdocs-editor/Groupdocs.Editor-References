---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir Markdown belgesinin meta verilerini temsil eder"
type: docs
weight: 750
url: /tr/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Bir Markdown belgesinin meta verilerini temsil eder

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Bu Markdown belgesinin formatını döndürür — her zaman [`Md`](../../groupdocs.editor.formats/textualformats/md) olur |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Markdown belgeleri parola ile şifrelenemediği için bu özellik her zaman ``false`` döndürür |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Sayfa sayısını döndürür. Markdown belgelerinde genellikle sabit sayfa yoktur ve bu nedenle sayfa sayısı, dikey A4 standart sayfa boyutundan hesaplanır. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Bu Markdown belgesinin bayt cinsinden boyutunu döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Bu örneğin belirtilen diğer [`MarkdownDocumentInfo`](../markdowndocumentinfo) örneğiyle eşit olup olmadığını belirler. |

### Ayrıca Bakınız

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

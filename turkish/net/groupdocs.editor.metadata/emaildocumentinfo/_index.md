---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenen herhangi bir e‑posta formatındaki bir e‑posta belgesinin meta verilerini temsil eder"
type: docs
weight: 720
url: /tr/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Desteklenen herhangi bir e‑posta formatındaki bir e‑posta belgesinin meta verilerini temsil eder

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Bu e-posta belgesinin formatını döndürür |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | E-posta belgeleri parola ile şifrelenemediği için bu özellik her zaman 'false' döndürür |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Her zaman 1 döndürür, çünkü e-posta belgelerinin sayfalı görünümü yoktur |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Bu e-posta belgesinin bayt cinsinden boyutunu döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Bu örneğin belirtilen diğer EmailDocumentInfo örneğiyle eşit olup olmadığını belirler |

### Ayrıca Bakınız

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

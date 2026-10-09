---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir Kelime İşleme belgesinin meta verilerini temsil eder"
type: docs
weight: 790
url: /tr/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

Bir Kelime İşleme belgesinin meta verilerini temsil eder

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | Bu WordProcessing belgesinin biçimini döndürür |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | Bu belirli WordProcessing belgesinin şifrelenip şifrelenmediğini ve açmak için parola gerektirip gerektirmediğini belirler |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | Sayfa sayısını döndürür |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | Bu WordProcessing belgesinin bayt cinsinden boyutunu döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | Bu örneğin belirtilen diğer WordProcessingDocumentInfo örneğiyle eşit olup olmadığını belirler |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | Seçilen sayfanın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür |

### Ayrıca Bakınız

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

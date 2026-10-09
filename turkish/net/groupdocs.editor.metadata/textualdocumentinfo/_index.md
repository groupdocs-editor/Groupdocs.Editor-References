---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir metin belgesinin XML HTML veya düz metin TXT gibi meta verilerini temsil eder"
type: docs
weight: 780
url: /tr/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

XML, HTML veya düz metin (TXT) gibi bir metin belgesinin meta verilerini temsil eder

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Metin belgesinin tespit edilen muhtemel kodlamasını döndürür |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Bu metin belgesinin formatını döndürür. Bazı durumlarda %100 doğru olmayabilir. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Metin belgeleri şifrelenemediği için her zaman ``false`` döndürür |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Her zaman 1 döndürür |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Bu metin belgesinin boyutunu bayt olarak döndürür (karakter sayısı değil) |

### Ayrıca Bakınız

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

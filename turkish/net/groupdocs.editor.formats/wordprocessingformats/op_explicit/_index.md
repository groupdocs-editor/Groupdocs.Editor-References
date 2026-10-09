---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden bir dizeyi WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats nesnesine dönüştürür."
type: docs
weight: 140
url: /tr/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Bir dosya uzantısını temsil eden bir dizeyi [`WordProcessingFormats`](../../wordprocessingformats) nesnesine dönüştürür.

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`WordProcessingFormats`](../../wordprocessingformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

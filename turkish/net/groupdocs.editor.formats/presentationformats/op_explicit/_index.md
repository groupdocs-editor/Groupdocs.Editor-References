---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden bir dizeyi PresentationFormatsgroupdocs.editor.formats/presentationformats nesnesine dönüştürür."
type: docs
weight: 150
url: /tr/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Bir dosya uzantısını temsil eden bir dizeyi [`PresentationFormats`](../../presentationformats) nesnesine dönüştürür.

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`PresentationFormats`](../../presentationformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

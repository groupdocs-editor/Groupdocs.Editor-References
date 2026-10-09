---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden bir dizeyi bir TextualFormatsgroupdocs.editor.formats/textualformats nesnesine dönüştürür."
type: docs
weight: 100
url: /tr/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Bir dosya uzantısını temsil eden bir dizeyi bir [`TextualFormats`](../../textualformats) nesnesine dönüştürür.

```csharp
public static explicit operator TextualFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`TextualFormats`](../../textualformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [TextualFormats](../../textualformats) | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden dizeyi bir EmailFormatsgroupdocs.editor.formats/emailformats nesnesine dönüştürür."
type: docs
weight: 150
url: /tr/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Bir dosya uzantısını temsil eden dizeyi bir [`EmailFormats`](../../emailformats) nesnesine dönüştürür.

```csharp
public static explicit operator EmailFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`EmailFormats`](../../emailformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [EmailFormats](../../emailformats) | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

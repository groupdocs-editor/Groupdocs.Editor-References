---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden bir dizeyi bir EBookFormatsgroupdocs.editor.formats/ebookformats nesnesine dönüştürür."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

Bir dosya uzantısını temsil eden bir dizeyi bir [`EBookFormats`](../../ebookformats) nesnesine dönüştürür.

```csharp
public static explicit operator EBookFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`EBookFormats`](../../ebookformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [EBookFormats](../../ebookformats) | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

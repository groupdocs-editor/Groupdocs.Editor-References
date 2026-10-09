---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dosya uzantısını temsil eden bir dizeyi SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats nesnesine dönüştürür."
type: docs
weight: 180
url: /tr/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

Bir dosya uzantısını temsil eden bir dizeyi [`SpreadsheetFormats`](../../spreadsheetformats) nesnesine dönüştürür.

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| uzantı | String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |

### Dönüş Değeri

Belirtilen dosya uzantısına karşılık gelen bir [`SpreadsheetFormats`](../../spreadsheetformats) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | Belirtilen dosya uzantısı null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

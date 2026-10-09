---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bu uzunluğun belirtilen birim tipinde bir dize temsili döndürür. Sayısal değer, birim tipindeki değişikliğe karşılık gelecek şekilde dönüştürülecektir."
type: docs
weight: 260
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Bu uzunluğun belirtilen birim tipinde bir dize temsili döndürür. Sayısal değer, birim tipindeki değişikliğe karşılık gelecek şekilde dönüştürülecektir.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| unit | Unit | Belirtilen birim, bu örneğin dizeye serileştirilmeden önce dönüştürülmesi gereken birim. Geçerli olmalıdır. Birimsiz olamaz. |

### Dönüş Değeri

Dize temsili

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidEnumArgumentException | Değer tanımlı değil |
| ArgumentOutOfRangeException | Birim içermeyen değer yasaktır |

### Ayrıca Bakınız

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

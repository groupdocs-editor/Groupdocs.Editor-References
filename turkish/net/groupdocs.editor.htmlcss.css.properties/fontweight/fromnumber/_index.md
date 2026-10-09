---
title: "FromNumber"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen sayıdan bir fontweight oluşturur"
type: docs
weight: 50
url: /tr/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

Belirtilen sayıdan bir font-weight oluşturur.

```csharp
public static FontWeight FromNumber(ushort number)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| sayı | UInt16 | İşaretsiz tam sayı, [1..1000] aralığında olmalıdır |

### Dönüş Değeri

Yeni FontWeight örneği veya istisna

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen sayı [1..1000] aralığının dışındadır |

### Ayrıca Bakınız

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

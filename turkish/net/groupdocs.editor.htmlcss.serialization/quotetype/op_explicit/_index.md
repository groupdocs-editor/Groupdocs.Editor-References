---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype örneğini Char tipine dönüştürür"
type: docs
weight: 100
url: /tr/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Belirtilen [`QuoteType`](../../quotetype) örneğini Char tipine dönüştürür

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| quote | QuoteType | Dönüştürülecek Quote türü örneği |

### Ayrıca Bakınız

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Belirli Char değerini karşılık gelen [`QuoteType`](../../quotetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| karakter | Karakter | Tek tırnak (U+0027 APOSTROPHE) veya çift tırnak (U+0022 QUOTATION MARK) karakteri. Başka bir karakter belirtilirse istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen Char ne bir tırnak işareti ne de bir tek tırnak |

### Ayrıca Bakınız

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

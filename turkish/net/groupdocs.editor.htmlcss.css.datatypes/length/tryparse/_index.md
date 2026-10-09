---
title: "TryParse"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen bir dizeyi, sayısal değeri ve birim adı dahil olmak üzere bir Length değeri olarak ayrıştırmaya çalışır."
type: docs
weight: 280
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/length/tryparse/
---
## Length.TryParse method

Belirtilen bir dizeyi bir Length değeri olarak ayrıştırmaya çalışır; sayısal değeri ve birim adını içerir.

```csharp
public static bool TryParse(string input, out Length result)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| girdi | String | Ayrıştırılması gereken giriş dizesi |
| sonuç | Length& | Ayrıştırmanın sonucunu içeren çıktı parametresi. Ayrıştırma başarısız olursa, varsayılan bir Length değeri — birimsiz sıfır — içerir. |

### Dönüş Değeri

Ayrıştırma başarılıysa true, başarısızsa false.

### Ayrıca Bakınız

* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

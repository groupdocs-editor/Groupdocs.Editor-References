---
title: "FromMime"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen MIME türüne sahip belirtilen T tipinde bir örnek alır."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Belirtilen MIME tipine sahip belirtilen *T* tipinde bir örnek getirir.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Parameter | Açıklama |
| --- | --- |
| T | Belge biçiminin türü. |
| mime | Belge biçiminin MIME türü. |

### Dönüş Değeri

Belirtilen MIME türüne sahip belirtilen *T* tipinde bir örnek.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | Eşleşen bir belge biçimi bulunamadığında fırlatılır. |

### Ayrıca Bakınız

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

---
title: "FromName"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen ada sahip belirtilen T tipinde bir örnek alır."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Belirtilen ada sahip belirtilen *T* tipinde bir örnek getirir.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Parameter | Açıklama |
| --- | --- |
| T | Biçim ailesinin türü. |
| ad | Biçim ailesinin adı. |

### Dönüş Değeri

Belirtilen ada sahip belirtilen *T* tipinde bir örnek.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | Eşleşen bir biçim ailesi bulunamadığında fırlatılır. |

### Ayrıca Bakınız

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

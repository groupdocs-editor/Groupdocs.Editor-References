---
title: "FromValue"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen tanımlayıcıya sahip belirtilen T tipinde bir örnek alır."
type: docs
weight: 70
url: /tr/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Belirtilen tanımlayıcıya sahip belirtilen *T* tipinde bir örnek getirir.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Parameter | Açıklama |
| --- | --- |
| T | Biçim ailesinin türü. |
| değer | Biçim ailesinin tanımlayıcısı. |

### Dönüş Değeri

Belirtilen tanımlayıcıya sahip belirtilen *T* tipinde bir örnek.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | Eşleşen bir biçim ailesi bulunamadığında fırlatılır. |

### Ayrıca Bakınız

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

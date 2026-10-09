---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Harcanan kredi sayısını alır."
type: docs
weight: 30
url: /tr/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Harcanan kredi sayısını alır.

```csharp
public static decimal GetConsumptionCredit()
```

### Dönüş Değeri

Zaten kullanılan kredi sayısı

### Örnekler

Aşağıdaki örnek, tüketilen kredi sayısını nasıl alacağınızı gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

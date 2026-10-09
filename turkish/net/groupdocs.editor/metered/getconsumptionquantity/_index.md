---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "İşlenen MB miktarını alır."
type: docs
weight: 40
url: /tr/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

İşlenen MB miktarını alır.

```csharp
public static decimal GetConsumptionQuantity()
```

### Örnekler

Aşağıdaki örnek, işlenen MB miktarını nasıl alacağınızı gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->

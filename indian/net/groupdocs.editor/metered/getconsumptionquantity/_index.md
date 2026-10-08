---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "प्रसंस्कृत MB की मात्रा प्राप्त करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

प्रसंस्कृत MB की मात्रा प्राप्त करता है।

```csharp
public static decimal GetConsumptionQuantity()
```

### उदाहरण

निम्न उदाहरण दर्शाता है कि प्रोसेस किए गए MB की मात्रा कैसे प्राप्त की जाए।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->

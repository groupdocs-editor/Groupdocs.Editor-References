---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "उपयोग किए गए क्रेडिट की संख्या प्राप्त करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

उपयोग किए गए क्रेडिट की संख्या प्राप्त करता है।

```csharp
public static decimal GetConsumptionCredit()
```

### रिटर्न मान

पहले से उपयोग किए गए क्रेडिट की गिनती

### उदाहरण

निम्न उदाहरण दर्शाता है कि उपभोग किए गए क्रेडिट की गिनती कैसे प्राप्त की जाए।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->

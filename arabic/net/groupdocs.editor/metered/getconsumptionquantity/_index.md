---
title: "GetConsumptionQuantity"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع كمية الميجابايتات المعالجة."
type: docs
weight: 40
url: /ar/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

يسترجع كمية الميجابايتات المعالجة.

```csharp
public static decimal GetConsumptionQuantity()
```

### أمثلة

يوضح المثال التالي كيفية استرجاع كمية الـ MBs المعالجة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

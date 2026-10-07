---
title: "GetConsumptionCredit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع عدد الاعتمادات المستهلكة."
type: docs
weight: 30
url: /ar/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

يسترجع عدد الاعتمادات المستهلكة.

```csharp
public static decimal GetConsumptionCredit()
```

### قيمة الإرجاع

عدد الاعتمادات المستخدمة بالفعل

### أمثلة

يوضح المثال التالي كيفية استرجاع عدد الاعتمادات المستهلكة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

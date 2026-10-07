---
title: "SetMeteredKey"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يفعل المنتج باستخدام مفاتيح Metered."
type: docs
weight: 20
url: /ar/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

يفعل المنتج باستخدام مفاتيح Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| publicKey | String | المفتاح العام. |
| privateKey | String | المفتاح الخاص. |

### أمثلة

يوضح المثال التالي كيفية تنشيط المنتج باستخدام مفاتيح Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

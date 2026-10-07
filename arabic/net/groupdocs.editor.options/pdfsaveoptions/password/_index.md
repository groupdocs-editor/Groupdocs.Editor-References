---
title: "كلمة المرور"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "كلمة المرور التي ستُطبق على مستند PDF المُولد ككلمة مرور مستخدم مطلوبة للفتح. إذا كانت NULL أو فارغة لن تُطبق أي كلمة مرور على المستند. وإلا سيتم تشفير المستند باستخدام خوارزمية RC4 بطول مفتاح 128 بت. بشكل افتراضي تكون NULL ولا تُطبق كلمة المرور."
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/pdfsaveoptions/password/
---
## PdfSaveOptions.Password property

كلمة المرور التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور للمستخدم، المطلوبة للفتح. إذا كانت NULL أو فارغة، لن تُطبق أي كلمة مرور على المستند. وإلا، سيتم تشفير المستند باستخدام RC4 (طول المفتاح 128 بت). القيمة الافتراضية هي NULL — لا تُطبق كلمة مرور.

```csharp
public string Password { get; set; }
```

### انظر أيضًا

* class [PdfSaveOptions](../../pdfsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

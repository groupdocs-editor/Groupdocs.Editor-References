---
title: "RecognizeLists"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند استيراد المستند من تنسيق النص العادي. القيمة الافتراضية هي true."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند استيراد المستند من تنسيق النص العادي. القيمة الافتراضية هي true.

```csharp
public bool RecognizeLists { get; set; }
```

### ملاحظات

إذا تم تعيين هذا الخيار إلى false، فإن خوارزمية التعرف على القوائم تكتشف فقرات القوائم عندما تنتهي أرقام القوائم إما بنقطة أو قوس يميني أو رموز نقطية (مثل "•", "*", "-" أو "o"). إذا تم تعيين هذا الخيار إلى true، تُستخدم المسافات البيضاء أيضًا كفواصل لأرقام القوائم: خوارزمية التعرف على القوائم للترقيم النمط العربي (1., 1.1.2.) تستخدم كلًا من المسافات البيضاء والنقطة (".") كرموز.

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

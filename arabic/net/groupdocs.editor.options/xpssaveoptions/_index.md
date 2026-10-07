---
title: "XpsSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات XPS XML Paper Specifications"
type: docs
weight: 1300
url: /ar/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات XPS (مواصفات ورق XML).

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ. القيمة الافتراضية هي false (تحسين الذاكرة معطل من أجل أداء أفضل). |

### ملاحظات

ملف XPS يمثل ملفات تخطيط الصفحات التي تستند إلى مواصفات XML Paper التي أنشأتها مايكروسوفت. تم تطويره كبديل لتنسيق ملف EMF وهو مشابه لتنسيق PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للمستند.

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

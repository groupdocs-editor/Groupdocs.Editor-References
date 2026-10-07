---
title: "PdfSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات PDF (Portable Document Format)."
type: docs
weight: 1070
url: /ar/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات PDF (Portable Document Format)

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | يحدد مستوى الامتثال لمعايير PDF للمستندات الناتجة. القيمة الافتراضية هي PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | مسؤول عن تضمين موارد الخطوط المستخدمة في المستند الأصلي داخل مستند PDF الناتج. بشكل افتراضي لا يتم تضمين أي خطوط (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ. القيمة الافتراضية هي false (تحسين الذاكرة معطل من أجل أداء أفضل). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | كلمة المرور التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور للمستخدم، المطلوبة للفتح. إذا كانت NULL أو فارغة، لن تُطبق أي كلمة مرور على المستند. وإلا، سيتم تشفير المستند باستخدام RC4 (طول المفتاح 128 بت). القيمة الافتراضية هي NULL — لا تُطبق كلمة مرور. |

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

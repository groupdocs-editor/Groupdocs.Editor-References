---
title: "SpreadsheetLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على خيارات لتحميل مستندات خلايا جدول البيانات الثنائية المتوافقة مع Excel مثل XLSX و ODS وغيرها إلى فئة Editor"
type: docs
weight: 1120
url: /ar/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

يحتوي على خيارات تحميل مستندات جداول البيانات الثنائية (Cells، متوافقة مع Excel) مثل XLS(X)، ODS وغيرها إلى فئة Editor

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | منشئ افتراضي بدون معلمات - جميع المعلمات لها قيم افتراضية |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء معالجة المستندات المدخلة، مما قد يضعف الأداء في بعض الحالات الخاصة، لكنه من ناحية أخرى يقلل من استهلاك الذاكرة. مفيد عند معالجة مستندات ضخمة ومواجهة OutOfMemoryException. القيمة الافتراضية هي false (تحسين الذاكرة معطل من أجل أداء أفضل). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند Spreadsheet إذا كان مشفّراً. اضبطها على NULL أو سلسلة فارغة لعدم استخدام كلمة المرور (القيمة الافتراضية). |

### انظر أيضًا

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

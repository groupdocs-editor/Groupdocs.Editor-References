---
title: "DelimitedTextEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "خيارات لتحميل مستندات Spreadsheet النصية مثل CSV و Tab وغيرها التي تستخدم فاصلًا محددًا"
type: docs
weight: 810
url: /ar/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

خيارات تحميل مستندات جدول البيانات النصية (CSV، المستندات المستندة إلى علامات الجدولة وغيرها)، التي تستخدم فاصلًا (delimiter)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | ينشئ نسخة من فئة الخيارات للنص المفصول بفاصل (delimiter) إلزامي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص في المستند النصي يُحوَّل إلى بيانات تاريخ. القيمة الافتراضية هي `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص في المستند النصي يُحوَّل إلى بيانات رقمية. القيمة الافتراضية هي `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء معالجة المستندات المدخلة، مما قد يضعف الأداء في بعض الحالات الخاصة، لكنه من ناحية أخرى يقلل من استهلاك الذاكرة. مفيد عند معالجة مستندات ضخمة ومواجهة OutOfMemoryException. القيمة الافتراضية هي `false` (تحسين الذاكرة معطل من أجل أداء أفضل). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | يسمح بتحديد فاصل نصي (delimiter) لمستندات Spreadsheet النصية. |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | يحدد ما إذا كان يجب اعتبار الفواصل المتتالية كواحدة. القيمة الافتراضية هي `false`. |

### ملاحظات

https://en.wikipedia.org/wiki/Delimiter-separated_values

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

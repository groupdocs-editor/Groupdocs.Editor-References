---
title: "MarkdownSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown"
type: docs
weight: 1000
url: /ar/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | يحدد ما إذا كانت الصور تُحفظ بتنسيق Base64 في ملف الإخراج. القيمة الافتراضية هي `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | يحدد المجلد الفعلي حيث تُحفظ الصور عند تصدير مستند إلى تنسيق Markdown. القيمة الافتراضية هي null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. ضبط هذا الخيار على `true` يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ. القيمة الافتراضية هي `false` (تحسين الذاكرة معطل من أجل أداء أفضل). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow يحدد كيفية محاذاة المحتويات في الجداول عند التصدير إلى تنسيق Markdown. القيمة الافتراضية هي Auto. |

### ملاحظات

يجب على المستخدم تطبيق فئة MarkdownSaveOptions عندما يكون هناك مثيل من فئة EditableDocument، التي تحتوي على محتوى مستند مُعدل، ويتطلب حفظ هذا المحتوى إلى مستند جديد بتنسيق Markdown.

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

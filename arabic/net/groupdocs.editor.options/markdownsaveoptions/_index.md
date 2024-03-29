---
title: MarkdownSaveOptions
second_title: GroupDocs.Editor لمرجع .NET API
description: يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown
type: docs
weight: 990
url: /ar/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | يحدد ما إذا كان سيتم حفظ الصور بتنسيق Base64 في ملف الإخراج. الافتراضي هو`خطأ شنيع` . |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | يحدد المجلد الفعلي حيث يتم حفظ الصور عند تصدير مستند إلى تنسيق Markdown. الافتراضي هو فارغ. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | تمكين آليات تحسين الذاكرة أثناء إنشاء المستند من HTML ، مما يقلل من الأداء كتكلفة لتقليل استخدام الذاكرة . تعيين هذا الخيار على`حقيقي`يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة بتكلفة أبطأ في توفير الوقت. الافتراضي هو`خطأ شنيع` (تم تعطيل تحسين الذاكرة من أجل أداء أفضل) . |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow يحدد كيفية محاذاة المحتويات في الجداول عند التصدير إلى تنسيق Markdown . القيمة الافتراضية هيAuto . |

### ملاحظات

يجب أن يتم تطبيق فئة MarkdownSaveOptions بواسطة المستخدم عندما يكون هناك مثيل لفئة EditableDocument ، التي تحتوي على محتوى مستند تم تحريره ، ويكون مطلوبًا حفظ هذا المحتوى في المستند الجديد بتنسيق Markdown.

### أنظر أيضا

* interface [ISaveOptions](../isaveoptions)
* مساحة الاسم [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

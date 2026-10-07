---
title: "WordProcessingSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستندات المتوافقة مع WordProcessing بعد تحريرها"
type: docs
weight: 1240
url: /ar/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات متوافقة مع معالجة الكلمات بعد تحريرها.

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | هذا المُنشئ بدون معلمات ينشئ مثيلًا جديدًا من WordProcessingSaveOptions بتنسيق إخراج DOCX (يمكن تعديله لاحقًا عبر خاصية [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | ينشئ مثيلًا جديدًا من WordProcessingSaveOptions بتنسيق إخراج WordProcessing المحدد إجباريًا، بينما تكون جميع المعلمات الأخرى افتراضية |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | يسمح بتمكين أو تعطيل الترميز الذي سيُستخدم لحفظ مستند WordProcessing. إذا تم فتح المستند الأصلي وتحريره في وضع الترميز، يجب أيضًا تمكين هذا الخيار. يكون معطلًا بشكل افتراضي. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | مسؤول عن تضمين موارد الخطوط في مستند WordProcessing الناتج. بشكل افتراضي لا يتم تضمين أي خطوط (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) الافتراضي لمستند WordProcessing، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing للنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي RTL للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing للنص شرق آسيوي، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي شرق آسيوي للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ. القيمة الافتراضية هي false (تحسين الذاكرة معطل من أجل أداء أفضل). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | يسمح بتحديد تنسيق WordProcessing الذي سيُستخدم لحفظ المستند |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | يسمح بتحديد أو تعديل أو الحصول على كلمة مرور أو إزالتها، والتي ستُستخدم لتشفير مستند WordProcessing المُنشأ. حدد NULL أو سلسلة فارغة لإزالة (مسح) كلمة المرور. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | يسمح بالتحكم وتطبيق خيارات حماية المستند لمستند WordProcessing بأي تنسيق يدعم حماية المستند. بشكل افتراضي تكون NULL - لن تُستخدم حماية المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | ينشئ ويعيد نسخة كاملة من هذا المثيل من فئة WordProcessingSaveOptions |

### ملاحظات

يُطبق WordProcessingSaveOptions في الحالات التي يكون فيها مثيل من فئة EditableDocument يحتوي على محتوى مستند مُحرَّر، ويتطلب حفظ هذا المحتوى إلى مستند جديد بتنسيق WordProcessing.

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

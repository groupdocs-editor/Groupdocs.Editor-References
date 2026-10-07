---
title: "Locale"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتعيين تجاوز لغة الإعداد المحلي الافتراضية لمستند معالجة الكلمات التي ستُطبق أثناء إنشائه. إذا لم يتم تحديده، سيكتشف MS Word أو أي برنامج آخر القيمة الافتراضية أو يختار الإعداد المحلي للمستند وفقًا لإعداداته أو عوامل أخرى."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) الافتراضي لمستند WordProcessing، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى.

```csharp
public CultureInfo Locale { get; set; }
```

### ملاحظات

يقوم هذا الخيار بفرض تطبيق الإعداد المحلي المحدد على النص بالكامل في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء نصية مختلفة مكتوبة بلغات متعددة.

### انظر أيضًا

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

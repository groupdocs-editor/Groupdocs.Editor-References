---
title: "LocaleFarEast"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتجاوز لغة الإعداد المحلي لمستند معالجة الكلمات للنص شرق آسيوي الذي سيُطبق أثناء إنشائه. إذا لم يتم تحديده، سيكتشف MS Word أو أي برنامج آخر القيمة الافتراضية أو يختار الإعداد المحلي شرق آسيوي للمستند وفقًا لإعداداته أو عوامل أخرى."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing للنص شرق آسيوي، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي شرق آسيوي للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى.

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### ملاحظات

يقوم هذا الخيار بفرض تطبيق الإعداد المحلي المحدد على النص شرق آسيوي بالكامل في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء نصية مختلفة مكتوبة بلغات متعددة.

### انظر أيضًا

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

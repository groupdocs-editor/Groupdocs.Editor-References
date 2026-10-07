---
title: "LocaleBi"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتعيين تجاوز لغة الإعداد المحلي لمستند معالجة الكلمات للنص من اليمين إلى اليسار (RTL) الذي سيُطبق أثناء إنشائه. إذا لم يتم تحديده، سيكتشف MS Word أو أي برنامج آخر القيمة الافتراضية أو يختار الإعداد المحلي RTL للمستند وفقًا لإعداداته أو عوامل أخرى."
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing للنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء إنشائه. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) باكتشاف (أو اختيار) الإعداد الإقليمي RTL للمستند وفقًا لإعداداته الخاصة أو عوامل أخرى.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### ملاحظات

يقوم هذا الخيار بفرض تطبيق الإعداد المحلي المحدد على النص RTL بالكامل في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء نصية مختلفة مكتوبة بلغات متعددة.

### انظر أيضًا

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

---
title: LocaleBi
second_title: GroupDocs.Editor لمرجع .NET API
description: يسمح بتعيين لغة التجاوز اللغة لمستند معالجة Word لنص RTL من اليمين إلى اليسار  والذي سيتم تطبيقه أثناء إنشائه . عندما لا يتم تحديد القيمة الافتراضية  MS Word أو برنامج آخر سيكتشف أو يختار المستند RTL locale وفقًا لإعداداته الخاصة أو عوامل أخرى.
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

يسمح بتعيين لغة التجاوز (اللغة) لمستند معالجة Word لنص RTL (من اليمين إلى اليسار) ، والذي سيتم تطبيقه أثناء إنشائه . عندما لا يتم تحديد (القيمة الافتراضية) ، MS Word (أو برنامج آخر) سيكتشف (أو يختار) المستند RTL locale وفقًا لإعداداته الخاصة أو عوامل أخرى.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### ملاحظات

يقوم هذا الخيار بتطبيق الإعدادات المحلية بشكل قسري على نص RTL الكلي في المستند. لا تستخدمه ، إذا كان المستند يحتوي على أجزاء مختلفة من النص ، والتي تمت كتابتها بلغات مختلفة.

### أنظر أيضا

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* مساحة الاسم [GroupDocs.Editor.Options](../../wordprocessingsaveoptions)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

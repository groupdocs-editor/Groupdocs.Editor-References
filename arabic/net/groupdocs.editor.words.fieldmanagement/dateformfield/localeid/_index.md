---
title: "LocaleId"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحصل أو يعيّن معرف اللغة (Locale ID) لحقل النموذج الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج."
type: docs
weight: 30
url: /ar/net/groupdocs.editor.words.fieldmanagement/dateformfield/localeid/
---
## DateFormField.LocaleId property

يحصل أو يعيّن معرف اللغة (Locale ID) لحقل النموذج، والذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج.

```csharp
public int LocaleId { get; set; }
```

### ملاحظات

خاصية LocaleId تحدد معرف اللغة (LCID) الذي يتCorrespond إلى ثقافة أو منطقة معينة.

### أمثلة

المثال التالي يوضح كيفية تعيين خاصية LocaleId:

```csharp
Set the LocaleId to represent the English (United States) culture
dateField.LocaleId = new CultureInfo("en-US").LCID;
```

### انظر أيضًا

* class [DateFormField](../../dateformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

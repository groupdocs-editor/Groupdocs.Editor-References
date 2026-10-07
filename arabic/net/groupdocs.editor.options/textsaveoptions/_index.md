---
title: "TextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات نصية عادية بصيغة TXT"
type: docs
weight: 1170
url: /ar/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات النص العادي (TXT)

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند التصدير بصيغة نص عادي. القيمة الافتراضية هي 'false' — لا تقم بإضافة علامات BiDi. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | ترميز الأحرف لمستند النص، والذي سيُطبق عند حفظه |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تخطيط الجداول عند الحفظ بصيغة نص عادي. القيمة الافتراضية هي false. |

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

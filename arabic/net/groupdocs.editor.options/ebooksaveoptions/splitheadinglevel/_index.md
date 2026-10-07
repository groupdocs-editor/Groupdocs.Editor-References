---
title: "SplitHeadingLevel"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف الكتاب الإلكتروني. القيمة الافتراضية هي 2. ضبطه على 0 سيعطل التقسيم بحيث يتم دمج كل محتوى الكتاب الإلكتروني في حزمة واحدة داخل الملف الناتج."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف e-Book. القيمة الافتراضية هي `2`. ضبطها على `0` سيعطل التقسيم، لذا سيتم دمج جميع محتوى e-Book في حزمة واحدة داخل الملف الناتج.

```csharp
public int SplitHeadingLevel { get; set; }
```

### ملاحظات

عند ضبط هذه الخاصية على قيمة من 1 إلى 9، سيتم تقسيم المستند عند الفقرات المنسقة باستخدام أنماط **Heading 1**, **Heading 2**, **Heading 3** وغيرها حتى مستوى العنوان المحدد.

بشكل افتراضي، فقط فقرات **Heading 1** و **Heading 2** تتسبب في تقسيم المستند. ضبط هذه الخاصية على الصفر (أو أقل من الصفر) سيمنع تقسيم المستند عند فقرات العناوين تمامًا.

### انظر أيضًا

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

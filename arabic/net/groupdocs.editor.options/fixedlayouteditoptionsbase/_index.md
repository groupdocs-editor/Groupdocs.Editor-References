---
title: "FixedLayoutEditOptionsBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الفئة الأساسية المجردة للخيارات لجميع مستندات صيغ fixedlayout مثل PDF و XPS."
type: docs
weight: 870
url: /ar/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

الفئة الأساسية المجردة للخيارات الخاصة بجميع المستندات ذات تنسيقات التخطيط الثابت مثل PDF و XPS

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. افتراضيًا يكون معطلًا (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | يسمح بتعيين نطاق الصفحات للمعالجة. افتراضيًا يتم معالجة جميع صفحات مستند fixed-layout. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | يحصل أو يعيّن العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل مستند fixed-layout المدخل إلى HTML الناتج. القيمة الافتراضية هي `false` - تُحافظ على الصور. |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

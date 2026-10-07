---
title: "PdfEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لتحرير مستندات PDF"
type: docs
weight: 1050
url: /ar/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

يسمح بتحديد خيارات مخصصة لتحرير مستندات PDF

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | ينشئ ويعيد مثالًا جديدًا من الفئة PdfEditOptions، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | ينشئ ويعيد مثالًا جديدًا من الفئة PdfEditOptions مع ترقيم الصفحات المحدد وتعيين باقي الخيارات إلى قيمها الافتراضية |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | يسمح بتمكين (true) أو تعطيل (false) الترقيم في مستند HTML الناتج. افتراضيًا يكون معطلًا (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | يسمح بتعيين نطاق الصفحات للمعالجة. افتراضيًا يتم معالجة جميع صفحات مستند fixed-layout. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | يحصل أو يعيّن العلامة التي تشير إلى ما إذا كان يجب تخطي الصور أثناء تحويل مستند fixed-layout المدخل إلى HTML الناتج. القيمة الافتراضية هي `false` - تُحافظ على الصور. |

### انظر أيضًا

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

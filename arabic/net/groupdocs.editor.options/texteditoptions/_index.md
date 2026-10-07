---
title: "TextEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لتحميل مستندات النص العادي TXT."
type: docs
weight: 1150
url: /ar/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

يسمح بتحديد خيارات مخصصة لتحميل مستندات النص العادي (TXT)

```csharp
public class TextEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextEditOptions](texteditoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | يسمح بتحديد اتجاه تدفق النص في مستند النص العادي الإدخالي. بشكل افتراضي يكون من اليسار إلى اليمين. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | يسمح بتمكين أو تعطيل الترميز الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | ترميز الأحرف لمستند النص، الذي سيُطبق عند فتحه. |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | يحصل أو يضبط الخيار المفضل لمعالجة المسافات البادئة. بشكل افتراضي يحول المسافات البادئة إلى مسافة اليسار. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عند استيراد المستند من تنسيق النص العادي. القيمة الافتراضية هي true. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | يحصل أو يضبط الخيار المفضل لمعالجة المسافات اللاحقة. بشكل افتراضي يقتطع جميع المسافات اللاحقة. |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

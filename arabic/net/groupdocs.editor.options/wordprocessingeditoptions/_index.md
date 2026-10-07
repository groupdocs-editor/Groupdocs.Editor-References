---
title: "WordProcessingEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة من WordProcessing المتوافقة مثل DOCX و RTF و ODT وغيرها."
type: docs
weight: 1200
url: /ar/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع صيغ معالجة الكلمات (متوافقة مع Words) المدعومة مثل DOC(X)، RTF، ODT وغيرها.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | ينشئ ويعيد نسخة جديدة من فئة WordProcessingEditOptions، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | ينشئ ويعيد نسخة جديدة من فئة WordProcessingEditOptions مع ترقيم الصفحات المحدد وتكون جميع الخيارات الأخرى افتراضية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML على شكل سمة HTML 'lang'. قد يكون هذا الخيار مفيدًا لتحويل المستندات متعددة اللغات ذهابًا وإيابًا. يكون معطَّلًا بشكل افتراضي (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | يسمح بتمكين أو تعطيل الترميز الصفحات في مستند HTML الناتج. بشكل افتراضي يكون معطلاً (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | يحصل على أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخراج موارد الخطوط المستخدمة فقط في المحتوى النصي للمستند. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | مسؤول عن استخراج موارد الخطوط المستخدمة في مستند WordProcessing المدخل. بشكل افتراضي لا يتم استخراج أي خطوط (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | يسمح بتحديد اسم فئة سيتم وضعه في سمة 'class' في كل عنصر HTML يمثل حقلًا ما في مستند WordProcessing المدخل. يكون القيمة الافتراضية NULL - لا تُطبق سمات 'class'. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية (`false`) أو كأنماط مضمنة في ترميز HTML (`true`). بشكل افتراضي تُستخدم الأنماط الخارجية (`false`). |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

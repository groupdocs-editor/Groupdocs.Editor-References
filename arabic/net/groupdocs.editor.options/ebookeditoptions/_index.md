---
title: "EbookEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد وضبط خيارات مخصصة لتحرير مستندات Ebook بجميع الصيغ المدعومة ePub و MOBI و AZW3."
type: docs
weight: 830
url: /ar/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

يسمح بتحديد وضبط خيارات مخصصة لتحرير مستندات الكتب الإلكترونية بجميع الصيغ المدعومة: ePub، MOBI، و AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | يُهيئ مثالًا جديدًا من الفئة [`EbookEditOptions`](../ebookeditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | يُهيئ مثالًا جديدًا من الفئة [`EbookEditOptions`](../ebookeditoptions) مع وضع ترقيم الصفحات المحدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | يحدد ما إذا كان يتم تصدير معلومات اللغة إلى ترميز HTML على شكل سمة HTML 'lang'. قد يكون هذا الخيار مفيدًا لتحويل ذهابًا وإيابًا للمستندات متعددة اللغات. بشكل افتراضي هو معطل (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بشكل افتراضي معطل (`false`). |

### ملاحظات

تنسيقات الكتب الإلكترونية المدعومة:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (النشر الإلكتروني)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (تنسيق Kindle 8t)

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

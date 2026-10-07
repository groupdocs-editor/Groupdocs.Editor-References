---
title: "EbookSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستند بجميع صيغ eBook المدعومة ePub وMOBI وAZW3."
type: docs
weight: 840
url: /ar/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستند بجميع صيغ الكتب الإلكترونية المدعومة: ePub، MOBI، و AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | هذا المُنشئ بدون معلمات ينشئ مثيلاً جديداً من EbookSaveOptions بصيغة إخراج ePub (يمكن تعديلها لاحقاً عبر خاصية [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | ينشئ مثيلاً جديدًا من [`EbookSaveOptions`](../ebooksaveoptions) مع تنسيق إخراج e-Book الإلزامي المحدد، بينما تكون جميع المعلمات الأخرى افتراضية |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة في الملف الناتج. القيمة الافتراضية هي `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | يحدد تنسيق ملف e-Book الناتج: IDPF ePub أو MOBI أو AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف e-Book. القيمة الافتراضية هي `2`. ضبطها على `0` سيعطل التقسيم، لذا سيتم دمج جميع محتوى e-Book في حزمة واحدة داخل الملف الناتج. |

### ملاحظات

تنسيقات الكتب الإلكترونية المدعومة:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (النشر الإلكتروني)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (تنسيق Kindle 8t)

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

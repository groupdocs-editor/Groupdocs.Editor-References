---
title: "EBookFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يغلف جميع صيغ الكتب الإلكترونية. يتضمن أنواع الملفات التالية Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /ar/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

يغلف جميع صيغ الكتب الإلكترونية. يتضمن أنواع الملفات التالية: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`EBookFormats`](../ebookformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | يسترجع نسخة من النوع المحدد [`EBookFormats`](../ebookformats) التي لها الامتداد المحدد للملف. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [`EBookFormats`](../ebookformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من صيغة ملف الكتاب الإلكتروني AZW التي تم تطويرها لأجهزة Amazon Kindle. الصيغة تم تحسينها مقارنة بملفات AZW القديمة. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | صيغة النشر الإلكتروني (IDPF ePub) هي صيغة ملف كتاب إلكتروني توفر صيغة نشر رقمية معيارية للناشرين والمستهلكين. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI هو الاسم المعطى للصيغة التي تم تطويرها لقارئ MobiPocket. تُعرف أيضًا باسم PRC، AZW. يتم استخدامها حاليًا من قبل Amazon بنظام DRM مختلف قليلًا وتسمى AZW. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/ebook/mobi/). |

### ملاحظات

تعرف على المزيد حول صيغة Mobi [هنا](https://docs.fileformat.com/ebook/mobi/), حول صيغة AZW3 [هنا](https://docs.fileformat.com/ebook/azw3/), وعلى صيغة ePub [هنا](https://docs.fileformat.com/ebook/epub/).

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

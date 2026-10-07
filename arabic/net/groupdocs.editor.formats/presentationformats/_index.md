---
title: "PresentationFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يغلف جميع صيغ العروض التقديمية. يتضمن الصيغ التالية"
type: docs
weight: 120
url: /ar/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

يحتوي على جميع صيغ العروض التقديمية. يتضمن الصيغ التالية:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

تعرف على المزيد حول صيغ العروض التقديمية [هنا](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`PresentationFormats`](../presentationformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | يسترجع نسخة من النوع المحدد [`PresentationFormats`](../presentationformats) التي لها الامتداد المحدد للملف. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | يحول سلسلة تمثل امتداد ملف إلى كائن [`PresentationFormats`](../presentationformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | عرض OpenDocument (ODP). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | قالب عرض OpenDocument (OTP). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | قالب عرض Microsoft PowerPoint 97-2003 (POT). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | قالب Microsoft Office Open XML PresentationML Macro-Enabled (POTM). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | قالب Microsoft Office Open XML PresentationML Macro-Free (POTX). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | عرض شرائح Microsoft PowerPoint 97-2003 (PPS). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | عرض شرائح Microsoft Office Open XML PresentationML Macro-Enabled (PPSM). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | عرض شرائح Microsoft Office Open XML PresentationML Macro-Free (PPSX). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | عرض Microsoft PowerPoint 97-2003 (PPT). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | عرض Microsoft PowerPoint 95 (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | مستند Microsoft Office Open XML PresentationML مع تمكين الماكرو (PPTM). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | مستند Microsoft Office Open XML PresentationML خالٍ من الماكرو (PPTX). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptx). |

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

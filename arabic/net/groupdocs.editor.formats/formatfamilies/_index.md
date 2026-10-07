---
title: "عائلات التنسيق"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل عائلات الصيغ المختلفة المتاحة في النظام."
type: docs
weight: 110
url: /ar/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

يمثل عائلات الصيغ المختلفة المتاحة في النظام.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | يمثل عائلة تنسيقات الكتب الإلكترونية. تعرف على تنسيق Mobi [هنا](https://docs.fileformat.com/ebook/mobi/)، وعلى تنسيق AZW3 [هنا](https://docs.fileformat.com/ebook/azw3/)، وعلى تنسيق ePub [هنا](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | يمثل عائلة تنسيقات البريد الإلكتروني. تعرف على تنسيق البريد الإلكتروني [هنا](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | يمثل عائلة تنسيقات التخطيط الثابت. تسمح تطبيقات عرض أو نشر المستندات المختلفة للمستخدمين بفتح (Adobe Acrobat، XPS Viewer)، وأحيانًا تعديل (Adobe InDesign) مستندات بتنسيقات محددة. عادةً ما تنتج هذه التطبيقات ما يُسمى مستندات “fixed-page”. يصف هذا التنسيق للمستند بدقة مكان وضع محتوى المستند على كل صفحة. داخليًا، يحتوي تنسيق PDF أو XPS على وصف لكل صفحة، بالإضافة إلى تعليمات رسم تحدد تخطيط المحتوى على الصفحة. هذا مشابه لتنسيقات الصور، التي تصف مكان عرض المحتوى إما بصيغة نقطية أو متجهية. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | يمثل عائلة تنسيقات العروض التقديمية. تعرف على تنسيقات العروض التقديمية [هنا](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | يمثل عائلة تنسيقات جداول البيانات. جميع تنسيقات جداول البيانات الثنائية، XML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV، TSV، المفصولة بفواصل منقوطة، إلخ)، التي يمكن حفظ المصنف فيها. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | يمثل عائلة تنسيقات النصوص. يضم جميع التنسيقات النصية (المعتمدة على النص)، بما في ذلك العلامات (XML، HTML) وغيرها. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | يمثل عائلة تنسيقات معالجة النصوص. تعرف على تنسيقات معالجة النصوص [هنا](https://wiki.fileformat.com/word-processing). |

### انظر أيضًا

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

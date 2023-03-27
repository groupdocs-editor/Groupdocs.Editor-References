---
title: WordProcessingFormats
second_title: GroupDocs.Editor لمرجع .NET API
description: لتضمين جميع تنسيقات معالجة الكلمات. يتضمن أنواع الملفات التالية Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . تعرف على المزيد حول تنسيقات معالجة الكلماتهناhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /ar/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

لتضمين جميع تنسيقات معالجة الكلمات. يتضمن أنواع الملفات التالية: [`Doc`](./doc) ، [`Docm`](./docm) ، [`Docx`](./docx) ، [`Dot`](./dot) ، [`Dotm`](./dotm) ، [`Dotx`](./dotx) ، [`FlatOpc`](./flatopc) ، [`Odt`](./odt) ، [`Ott`](./ott) ، [`Rtf`](./rtf) ، [`WordML`](./wordml) . تعرف على المزيد حول تنسيقات معالجة الكلمات[هنا](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | إرجاع امتداد (بدون حرف النقطة البادئة) لتنسيق معالجة Word هذا بأحرف صغيرة |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | إرجاع رمز MIME لهذا التنسيق |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | إرجاع الاسم الكامل الرسمي لتنسيق معالجة Word |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | إرجاع مثيل[`WordProcessingFormats`](../wordprocessingformats) الهيكل ، المرتبط بامتداد اسم الملف المحدد ، أو يطرح استثناءً ، إذا كان التمديد لا يمكن تحليله بشكل صحيح |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | تحديد ما إذا كان هذا المثيل مساويًا لمثيل IDocumentFormat المحدد الآخر. |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | تحديد ما إذا كان هذا المثيل مساويًا للكائن المحدد الآخر ، والذي يُفترض أنه من تنسيقات WordProcessingFormats المعبأة |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | تحديد ما إذا كان هذا المثيل مساويًا لتنسيقات WordProcessingFormats المحددة الأخرى ، والمثيل |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | إرجاع رمز تجزئة غير قابل للتغيير في هذا المثال |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | إرجاع اسم هذا التنسيق المحدد ، مثل "الاسم" property |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | يتحقق من مثيلين معينين لمعالجة WordProcessingFormats عند المساواة |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | إرجاع قيمة بايت من الحقل الأساسي لتنسيقات WordProcessingFormats المحددة. (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | يتحقق من مثيلين معينين لـ WordProcessingFormats على عدم المساواة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Mac Document (DOCM) ملفات Microsoft Word 2007 أو أحدث مع إمكانية تشغيل وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع إصدار Microsoft Office 2007 ، وتم تغيير هيكل تنسيق المستند الجديد هذا من ثنائي عادي إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | قالب MS Word 97-2007 عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لإنشاء المزيد من ملفات DOC أو DOCX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) يمثل ملف القالب الذي تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات منسقة مسبقًا لإنشاء المزيد من ملفات DOCX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML مخزّن في ملف XML ثابت بدلاً من حزمة ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | ملفات Open Document Text Text Document (ODT) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تستند إلى تنسيق OpenDocument Text File . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | قالب مستند نصي بتنسيق Open Document (OTT) يمثل مستندات النموذج التي تم إنشاؤها بواسطة التطبيقات وفقًا للتنسيق القياسي OpenDocument الخاص بـ OASIS . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | يمثل تنسيق Rich Text (RTF) طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | تنسيق Microsoft Office Word 2003 XML - WordProcessingML أو WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | إرجاع فئة داخلية توفر احتمالات لا تعد ولا تحصى على جميع تنسيقات معالجة الكلمات الحالية |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | تطبيقات I واجهة عامة قابلة للعدد ، والتي تتيح إمكانية "foreach" لـ WordProcessingFormats type |

### ملاحظات

يتم الحصول على رموز MIME من الموارد المحددة: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### أنظر أيضا

* interface [IDocumentFormat](../idocumentformat)
* مساحة الاسم [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

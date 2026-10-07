---
title: "WordProcessingFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على جميع صيغ معالجة النصوص. يتضمن أنواع الملفات التالية"
type: docs
weight: 150
url: /ar/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

يحتوي على جميع صيغ معالجة النصوص. يتضمن أنواع الملفات التالية:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

تعرّف على المزيد حول صيغ معالجة النصوص [هنا](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`WordProcessingFormats`](../wordprocessingformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | يسترجع نسخة من النوع المحدد [`WordProcessingFormats`](../wordprocessingformats) التي لها امتداد الملف المحدد. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [`WordProcessingFormats`](../wordprocessingformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | تنسيق ملف ثنائي MS Word 97-2007 (DOC) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بصيغة ملف ثنائي. تعرّف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | ملفات Office Open XML WordProcessingML Macro-Enabled Document (DOCM) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل وحدات الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | ملفات Office Open XML WordProcessingML Macro-Free Document (DOCX) هي تنسيق معروف جيدًا لمستندات Microsoft Word. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | قوالب MS Word 97-2007 (DOT) هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | قالب Office Open XML WordprocessingML Macro-Enabled (DOTM) يمثل ملفات قوالب تم إنشاؤها باستخدام Microsoft Word 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | قالب Office Open XML WordprocessingML Macro-Free (DOTX) هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | يتم تخزين Office Open XML WordprocessingML في ملف XML مسطح بدلاً من حزمة ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | ملفات Open Document Format Text Document (ODT) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص التي تعتمد على تنسيق ملف OpenDocument Text. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | قالب Open Document Format Text Document (OTT) يمثل مستندات قوالب تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | تنسيق Rich Text Format (RTF) يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | تنسيق Microsoft Office Word 2003 XML — WordProcessingML أو WordML (.XML). |

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

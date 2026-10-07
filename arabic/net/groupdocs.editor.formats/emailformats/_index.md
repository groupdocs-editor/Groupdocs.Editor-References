---
title: "EmailFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يغلف جميع صيغ البريد الإلكتروني. يتضمن أنواع الملفات التالية Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /ar/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

يغلف جميع صيغ البريد الإلكتروني. يتضمن أنواع الملفات التالية: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | يحصل على مجموعة قابلة للتعداد من جميع [`EmailFormats`](../emailformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | يسترجع نسخة من النوع المحدد [`EmailFormats`](../emailformats) التي لها الامتداد المحدد للملف. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [`EmailFormats`](../emailformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | صيغة ملف EML تمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | تم تنفيذ وتطوير صيغة ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail صيغة EMLX لتصدير الرسائل الإلكترونية. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | رسائل بريد إلكتروني بتنسيق HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | مواصفة كائن الإنترنت للتقويم والجدولة (iCalendar) هي معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | صيغة ملف MBox هي مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML، اختصار لـ "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG هي صيغة ملف يستخدمها Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | الملفات ذات الامتداد .oft هي ملفات قالب يتم إنشاؤها باستخدام Microsoft Outlook. تعرف على المزيد حول هذه الصيغة [هنا](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | ملف جدول التخزين غير المتصل (OST) يمثل بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل مع خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | الملفات ذات الامتداد .pst تمثل ملفات تخزين شخصية لـ Outlook (وتسمى أيضاً جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | تنسيق التغليف المحايد للنقل (TNEF) هو تنسيق مملوك لشركة Microsoft لتغليف مرفقات البريد الإلكتروني بناءً على واجهة برمجة تطبيقات الرسائل (MAPI). تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات جهات الاتصال. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/email/vcf/). |

### ملاحظات

تعرف على المزيد حول تنسيق البريد الإلكتروني [هنا](https://docs.fileformat.com/email/).

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->

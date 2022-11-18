---
title: EmailFormats
second_title: GroupDocs.Editor لمرجع .NET API
description: يغلف كافة تنسيقات رسائل البريد الإلكتروني. يتضمن أنواع الملفات التالية Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /ar/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

يغلف كافة تنسيقات رسائل البريد الإلكتروني. يتضمن أنواع الملفات التالية: [`Tnef`](./tnef) ، [`Eml`](./eml) ، [`Emlx`](./emlx) ، [`Msg`](./msg) ، [`Html`](./html) ، [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | في نوع التنفيذ ، يجب إرجاع امتداد الملف بتنسيق (بدون حرف النقطة البادئة) . |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | في نوع التنفيذ ، يجب إرجاع رمز MIME للتنسيق المحدد |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | في نوع التنفيذ ، يجب إرجاع الاسم بالتنسيق الرسمي الكامل |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | إرجاع مثيل[`EmailFormats`](../emailformats)الهيكل ، المرتبط بامتداد اسم الملف المحدد ، أو يطرح استثناءً ، إذا كان التمديد لا يمكن تحليله بشكل صحيح |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | يحدد ما إذا كان هذا المثيل يساوي مثيل البريد الإلكتروني المحدد الآخر |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | تحديد ما إذا كان هذا المثيل مساويًا لمثيل IDocumentFormat المحدد الآخر. |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | لتحديد ما إذا كان هذا المثيل مساويًا للكائن المحدد الآخر ، والذي يُفترض أنه من Email المعبأ |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | إرجاع رمز تجزئة غير قابل للتغيير في هذا المثال |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | إرجاع اسم تنسيق بهذا التنسيق |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | يتحقق من مثيلين بريد إلكتروني معينين بشأن المساواة |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | يتحقق من مثيلين بريد إلكتروني معينين على عدم المساواة |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | يمثل تنسيق ملف EML رسائل البريد الإلكتروني المحفوظة باستخدام Outlook والتطبيقات الأخرى ذات الصلة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير رسائل البريد الإلكتروني. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | رسائل بريد إلكتروني بتنسيق HTML . |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | تقويم الإنترنت وجدولة المواصفات الأساسية للكائن (iCalendar) هو معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | تنسيق ملف MBox هو مصطلح عام يمثل حاوية لتجميع رسائل البريد الإلكتروني. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML ، بداية "تغليف MIME لمستندات HTML المجمعة" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني أو جهة الاتصال أو الموعد أو المهام الأخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | الملفات ذات الامتداد .oft هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Outlook . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | يمثل ملف جدول التخزين غير المتصل (OST) بيانات صندوق بريد المستخدم في وضع عدم الاتصال على الجهاز المحلي عند التسجيل مع Exchange Server باستخدام Microsoft Outlook . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | تمثل الملفات ذات الامتداد .pst ملفات التخزين الشخصية في Outlook (تسمى أيضًا جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | تنسيق تغليف النقل المحايد (TNEF) هو ملكية مملوكة لشركة Microsoft ، لتغليف مرفقات البريد الإلكتروني استنادًا إلى واجهة برمجة تطبيقات المراسلة (MAPI) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات جهات الاتصال. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | إرجاع فئة داخلية توفر احتمالات لا تعد ولا تحصى على جميع تنسيقات البريد الإلكتروني الموجودة |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | تطبيقات I واجهة عامة قابلة للعدد ، والتي تتيح إمكانية "foreach" لنوع البريد الإلكتروني |

### ملاحظات

تعرف على المزيد حول تنسيق رسائل البريد الإلكتروني[هنا](https://docs.fileformat.com/email/) .

### أنظر أيضا

* interface [IDocumentFormat](../idocumentformat)
* مساحة الاسم [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

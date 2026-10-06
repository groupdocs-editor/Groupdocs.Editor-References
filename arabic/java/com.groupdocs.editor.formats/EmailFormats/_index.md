---
title: "EmailFormats"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على جميع تنسيقات البريد الإلكتروني."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

يحتوي على جميع صيغ البريد الإلكتروني. يتضمن أنواع الملفات التالية:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

تعرف على المزيد حول صيغ البريد الإلكتروني [هنا](../https://docs.fileformat.com/email/).

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Tnef](#Tnef) | تنسيق التغليف المحايد للنقل (TNEF) هو تنسيق مملوك لشركة Microsoft لتغليف مرفقات البريد الإلكتروني بناءً على واجهة برمجة تطبيقات الرسائل (MAPI). |
|
|  | [Eml](#Eml) | تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. |
|
|  | [Emlx](#Emlx) | تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. |
|
|  | [Msg](#Msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. |
|
|  | [Html](#Html) | رسائل بريد إلكتروني بتنسيق HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML، اختصار لـ "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | مواصفة كائن الإنترنت للتقويم والجدولة (iCalendar) هي معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال. |
|
|  | [Pst](#Pst) | الملفات ذات الامتداد .pst تمثل ملفات التخزين الشخصية لـ Outlook (المعروفة أيضًا باسم Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم. |
|
|  | [Mbox](#Mbox) | تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. |
|
|  | [Oft](#Oft) | الملفات ذات الامتداد .oft هي ملفات قالب يتم إنشاؤها باستخدام Microsoft Outlook. |
|
|  | [Ost](#Ost) | ملف جدول التخزين غير المتصل (OST) يمثل بيانات صندوق بريد المستخدم\u2019s في وضع عدم الاتصال على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [EmailFormats](../../com.groupdocs.editor.formats/emailformats) التي لها الامتداد المحدد. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


تنسيق التغليف المحايد للنقل (TNEF) هو تنسيق مملوك لشركة Microsoft لتغليف مرفقات البريد الإلكتروني بناءً على واجهة برمجة تطبيقات الرسائل (MAPI).
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير رسائل البريد الإلكتروني.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG هو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


رسائل بريد إلكتروني بتنسيق HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML، اختصار لـ "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


مواصفة كائن الإنترنت للتقويم والجدولة (iCalendar) هي معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


الملفات ذات الامتداد .pst تمثل ملفات التخزين الشخصية لـ Outlook (المعروفة أيضًا باسم Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


الملفات ذات الامتداد .oft هي ملفات قالب يتم إنشاؤها باستخدام Microsoft Outlook.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


ملف جدول التخزين غير المتصل (OST) يمثل بيانات صندوق بريد المستخدم\u2019s في وضع عدم الاتصال على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
القيمة: IEnumerable{EmailFormats} يحتوي على جميع نسخ [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [EmailFormats](../../com.groupdocs.editor.formats/emailformats) التي لها الامتداد المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | ملحق الملف للتحويل. إذا كان الملحق يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.


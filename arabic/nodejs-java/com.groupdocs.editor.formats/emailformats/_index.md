---
title: "EmailFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على جميع تنسيقات البريد الإلكتروني."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات البريد الإلكتروني. يتضمن أنواع الملفات التالية:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

تعرف على المزيد حول تنسيق البريد الإلكتروني [هنا](../https://docs.fileformat.com/email/).

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
|  | [Msg](#Msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني أو جهات الاتصال أو المواعيد أو مهام أخرى. |
|
|  | [Html](#Html) | رسائل بريد إلكتروني مُنسقة بـHTML. |
|
|  | [Mhtml](#Mhtml) | MHTML، اختصار لـ"تغليف MIME للوثائق HTML المجمعة". |
|
|  | [Ics](#Ics) | المواصفة الأساسية لكائنات تقويم الإنترنت والجدولة (iCalendar) هي معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة. |
|
|  | [Vcf](#Vcf) | VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال. |
|
|  | [Pst](#Pst) | الملفات ذات امتداد .pst تمثل ملفات تخزين شخصية لبرنامج Outlook (تُعرف أيضاً بجدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. |
|
|  | [Mbox](#Mbox) | تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني. |
|
|  | [Oft](#Oft) | الملفات ذات امتداد .oft هي ملفات قالب يتم إنشاؤها باستخدام Microsoft Outlook. |
|
|  | [Ost](#Ost) | ملف جدول التخزين غير المتصل (OST) يمثل بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل مع Exchange Server باستخدام Microsoft Outlook. |
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
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


تنسيق ملف EMLX تم تنفيذه وتطويره من قبل Apple. تطبيق Apple Mail يستخدم تنسيق ملف EMLX لتصدير الرسائل الإلكترونية.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG هو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني أو جهات الاتصال أو المواعيد أو مهام أخرى.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


رسائل بريد إلكتروني مُنسقة بـHTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML، اختصار لـ"تغليف MIME للوثائق HTML المجمعة".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


المواصفة الأساسية لكائنات تقويم الإنترنت والجدولة (iCalendar) هي معيار إنترنت (RFC 2445) لتبادل ونشر أحداث التقويم والجدولة.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (تنسيق البطاقة الافتراضية) أو vCard هو تنسيق ملف رقمي لتخزين معلومات الاتصال.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


الملفات ذات امتداد .pst تمثل ملفات تخزين شخصية لبرنامج Outlook (تُعرف أيضاً بجدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


تنسيق ملف MBox هو مصطلح عام يمثل حاوية لمجموعة من رسائل البريد الإلكتروني.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


الملفات ذات امتداد .oft هي ملفات قالب يتم إنشاؤها باستخدام Microsoft Outlook.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


ملف جدول التخزين غير المتصل (OST) يمثل بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل مع Exchange Server باستخدام Microsoft Outlook.
اعرف المزيد عن تنسيق الملف هذا
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
|  | الامتداد | java.lang.String | امتداد الملف للتحويل. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.


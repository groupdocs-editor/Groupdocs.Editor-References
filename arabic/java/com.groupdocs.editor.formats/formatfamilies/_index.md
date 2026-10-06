---
title: "FormatFamilies"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل عائلات التنسيقات المختلفة المتاحة في النظام."
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

يمثل عائلات التنسيقات المختلفة المتاحة في النظام.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [EBook](#EBook) | يمثل عائلة صيغ الكتب الإلكترونية. |
|
|  | [Email](#Email) | يمثل عائلة صيغ البريد الإلكتروني. |
|
|  | [FixedLayout](#FixedLayout) | يمثل عائلة صيغ التخطيط الثابت. |
|
|  | [Presentation](#Presentation) | يمثل عائلة صيغ العروض التقديمية. |
|
|  | [Spreadsheet](#Spreadsheet) | يمثل عائلة صيغ الجداول الحسابية. |
|
|  | [Textual](#Textual) | يمثل عائلة صيغ النصية. |
|
|  | [WordProcessing](#WordProcessing) | يمثل عائلة صيغ معالجة النصوص. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


يمثل عائلة صيغ الكتب الإلكترونية.
تعرف على المزيد حول صيغة Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
حول تنسيق AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
وعن تنسيق ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


يمثل عائلة صيغ البريد الإلكتروني.
تعرف على المزيد حول تنسيق البريد الإلكتروني
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


يمثل عائلة صيغ التخطيط الثابت.
تسمح تطبيقات عرض أو نشر المستندات المتنوعة للمستخدمين بفتح (Adobe Acrobat، XPS Viewer)، وأحيانًا تعديل (Adobe InDesign) مستندات ذات تنسيقات محددة.
عادةً ما تنتج هذه التطبيقات مستندات بتنسيق \u201cصفحة ثابتة\u201d.
يصف مثل هذا التنسيق للمستند بدقة مكان وضع محتوى المستند\u2019 على كل صفحة.
داخليًا، يحتوي تنسيق PDF أو XPS على وصف لكل صفحة، بالإضافة إلى تعليمات الرسم التي تحدد تخطيط المحتوى على الصفحة.
هذا مشابه لتنسيقات الصور، حيث يصف مكان عرض المحتوى إما بصيغة نقطية أو متجهة.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


يمثل عائلة صيغ العروض التقديمية.
تعرف على المزيد حول تنسيقات العرض التقديمي.
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


يمثل عائلة صيغ الجداول الحسابية.
جميع تنسيقات الجداول الإلكترونية الثنائية، XML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV، TSV، المفصولة بفواصل منقوطة، إلخ)، التي يمكن حفظ المصنف فيها.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


يمثل عائلة صيغ النصية.
يحتوي على جميع التنسيقات النصية (المعتمدة على النص)، بما في ذلك العلامات (XML، HTML) وغيرها.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


يمثل عائلة صيغ معالجة النصوص.
تعرف على المزيد حول تنسيقات معالجة النصوص.
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

يتم جلب رموز MIME من الموارد المذكورة: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />




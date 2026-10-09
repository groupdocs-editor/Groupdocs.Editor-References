---
title: "FormatFamilies"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل عائلات التنسيقات المختلفة المتاحة في النظام."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
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
|  | [EBook](#EBook) | يمثل عائلة تنسيق الكتب الإلكترونية. |
|
|  | [Email](#Email) | يمثل عائلة تنسيق البريد الإلكتروني. |
|
|  | [FixedLayout](#FixedLayout) | يمثل عائلة تنسيق التخطيط الثابت. |
|
|  | [Presentation](#Presentation) | يمثل عائلة تنسيق العرض. |
|
|  | [Spreadsheet](#Spreadsheet) | يمثل عائلة تنسيق الجداول. |
|
|  | [Textual](#Textual) | يمثل عائلة تنسيق النصوص. |
|
|  | [WordProcessing](#WordProcessing) | يمثل عائلة تنسيق معالجة النصوص. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


يمثل عائلة تنسيق الكتب الإلكترونية.
اعرف المزيد عن تنسيق Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
حول تنسيق AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
و حول تنسيق ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


يمثل عائلة تنسيق البريد الإلكتروني.
اعرف المزيد عن تنسيق البريد الإلكتروني
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


يمثل عائلة تنسيق التخطيط الثابت.
تسمح تطبيقات عرض أو نشر المستندات المتنوعة للمستخدمين بفتح (Adobe Acrobat, XPS Viewer)، وأحيانًا تعديل (Adobe InDesign) المستندات ذات الصيغ المحددة.
عادةً ما تُنتج هذه التطبيقات ما يُسمى “fixed-page” مستندات ذات تنسيق ثابت للصفحة.
يصف مثل هذا التنسيق للمستند بدقة مكان وضع محتوى المستند على كل صفحة.
داخليًا، يحتوي تنسيق PDF أو XPS على وصف لكل صفحة، بالإضافة إلى تعليمات الرسم التي تحدد تخطيط المحتوى على الصفحة.
هذا مشابه لتنسيقات الصور، حيث يصف مكان عرض المحتوى إما بصيغة نقطية أو متجهة.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


يمثل عائلة تنسيق العرض.
اعرف المزيد عن تنسيقات العرض
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


يمثل عائلة تنسيق الجداول.
جميع تنسيقات الجداول الإلكترونية الثنائية، XML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV، TSV، المفصولة بفواصل منقوطة، إلخ)، التي يمكن حفظ المصنف فيها.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


يمثل عائلة تنسيق النصوص.
يحتوي على جميع التنسيقات النصية (المعتمدة على النص)، بما في ذلك العلامات (XML، HTML) وغيرها.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


يمثل عائلة تنسيق معالجة النصوص.
اعرف المزيد عن تنسيقات معالجة النصوص
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

تم استخراج رموز MIME من الموارد المذكورة: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />




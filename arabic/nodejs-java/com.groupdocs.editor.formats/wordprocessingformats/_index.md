---
title: "WordProcessingFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على جميع تنسيقات معالجة الكلمات."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات WordProcessing. يتضمن أنواع الملفات التالية:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
تعرف على المزيد حول تنسيقات Word Processing [هنا](../https://wiki.fileformat.com/word-processing).

يتم استخراج رموز MIME من الموارد المذكورة:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Doc](#Doc) | تنسيق ملف ثنائي لـ MS Word 97-2007 (DOC) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو غيرها من مستندات معالجة النصوص بصيغة ملف ثنائي. |
|
|  | [Docx](#Docx) | مستند Office Open XML WordProcessingML خالٍ من الماكرو (DOCX) هو تنسيق معروف لمستندات Microsoft Word. |
|
|  | [Dot](#Dot) | قالب MS Word 97-2007 (DOT) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOC أو DOCX إضافية. |
|
|  | [Docm](#Docm) | ملفات Office Open XML WordProcessingML مع تمكين الماكرو (DOCM) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. |
|
|  | [Dotx](#Dotx) | قالب Office Open XML WordprocessingML خالٍ من الماكرو (DOTX) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOCX إضافية. |
|
|  | [Dotm](#Dotm) | قالب Office Open XML WordprocessingML مع تمكين الماكرو (DOTM) يمثل ملفات القالب التي تم إنشاؤها باستخدام Microsoft Word 2007 أو أحدث. |
|
|  | [FlatOpc](#FlatOpc) | يتم تخزين Office Open XML WordprocessingML في ملف XML مسطح بدلاً من حزمة ZIP. |
|
|  | [Rtf](#Rtf) | تنسيق النص الغني (RTF) يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. |
|
|  | [Odt](#Odt) | ملفات Open Document Format Text Document (ODT) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. |
|
|  | [Ott](#Ott) | قالب Open Document Format Text Document (OTT) يمثل مستندات القالب التي تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق OASIS OpenDocument القياسي. |
|
|  | [WordML](#WordML) | تنسيق XML لـ Microsoft Office Word 2003 — WordProcessingML أو WordML (.XML). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) التي لها امتداد الملف المحدد. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


تنسيق ملف ثنائي لـ MS Word 97-2007 (DOC) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو غيرها من مستندات معالجة النصوص بصيغة ملف ثنائي.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


مستند Office Open XML WordProcessingML خالٍ من الماكرو (DOCX) هو تنسيق معروف لمستندات Microsoft Word.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


قالب MS Word 97-2007 (DOT) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOC أو DOCX إضافية.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


ملفات Office Open XML WordProcessingML مع تمكين الماكرو (DOCM) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


قالب Office Open XML WordprocessingML خالٍ من الماكرو (DOTX) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOCX إضافية.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


قالب Office Open XML WordprocessingML مع تمكين الماكرو (DOTM) يمثل ملفات القالب التي تم إنشاؤها باستخدام Microsoft Word 2007 أو أحدث.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


يتم تخزين Office Open XML WordprocessingML في ملف XML مسطح بدلاً من حزمة ZIP.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


تنسيق النص الغني (RTF) يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


ملفات Open Document Format Text Document (ODT) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


قالب Open Document Format Text Document (OTT) يمثل مستندات القالب التي تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق OASIS OpenDocument القياسي.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


تنسيق XML لـ Microsoft Office Word 2003 — WordProcessingML أو WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
القيمة: IEnumerable{WordProcessingFormats} يحتوي على جميع نسخ [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) التي لها امتداد الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف للتحويل. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.


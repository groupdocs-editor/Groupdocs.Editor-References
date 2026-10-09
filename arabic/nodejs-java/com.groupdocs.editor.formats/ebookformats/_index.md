---
title: "EBookFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على جميع تنسيقات eBook."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات الكتب الإلكترونية. يتضمن أنواع الملفات التالية:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
تعرف على المزيد حول تنسيق Mobi [هنا](../https://docs.fileformat.com/ebook/mobi/)، وعلى تنسيق ePub [هنا](../https://docs.fileformat.com/ebook/epub/).

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI هو الاسم المعطى للتنسيق المطور لقارئ MobiPocket. |
|
|  | [Epub](#Epub) | تنسيق النشر الإلكتروني (IDPF ePub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. |
|
|  | [Azw3](#Azw3) | AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من تنسيق ملف الكتاب الإلكتروني AZW الذي تم تطويره لأجهزة Amazon Kindle. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) التي لها امتداد الملف المحدد. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI هو الاسم المعطى للتنسيق المطور لقارئ MobiPocket. يُعرف أيضًا باسم PRC، AZW.
يتم استخدامه حاليًا من قبل Amazon بنظام DRM مختلف قليلًا ويُسمى AZW.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


تنسيق النشر الإلكتروني (IDPF ePub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من تنسيق ملف الكتاب الإلكتروني AZW الذي تم تطويره لأجهزة Amazon Kindle.
التنسيق هو تحسين لملفات AZW القديمة.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
القيمة: IEnumerable{EBookFormats} يحتوي على جميع نسخ [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) التي لها امتداد الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف للتحويل. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.


---
title: "EBookFormats"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على جميع تنسيقات الكتب الإلكترونية."
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

يحتوي على جميع صيغ eBook. يتضمن أنواع الملفات التالية:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
تعرف على المزيد حول صيغة Mobi [هنا](../https://docs.fileformat.com/ebook/mobi/)، وعلى صيغة ePub [هنا](../https://docs.fileformat.com/ebook/epub/).

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI هو الاسم الممنوح للصيغة التي تم تطويرها لقارئ MobiPocket. |
|
|  | [Epub](#Epub) | صيغة النشر الإلكتروني (IDPF ePub) هي صيغة ملف إلكتروني توفر صيغة نشر رقمية قياسية للناشرين والمستهلكين. |
|
|  | [Azw3](#Azw3) | AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من صيغة ملف eBook الرقمي AZW التي تم تطويرها لأجهزة Amazon Kindle. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع مثيلًا من النوع المحدد [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) الذي يمتلك الامتداد المحدد للملف. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن من نوع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI هو الاسم الممنوح للصيغة التي تم تطويرها لقارئ MobiPocket. يُعرف أيضًا باسم PRC أو AZW.
يتم استخدامها حاليًا من قبل Amazon بنظام DRM مختلف قليلًا وتُسمى AZW.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


صيغة النشر الإلكتروني (IDPF ePub) هي صيغة ملف إلكتروني توفر صيغة نشر رقمية قياسية للناشرين والمستهلكين.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3، المعروف أيضًا باسم Kindle Format 8 (KF8)، هو النسخة المعدلة من صيغة ملف eBook الرقمي AZW التي تم تطويرها لأجهزة Amazon Kindle.
الصيغة هي تحسين لملفات AZW القديمة.
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
القيمة: IEnumerable{EBookFormats} يحتوي على جميع مثيلات [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


يسترجع مثيلًا من النوع المحدد [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) الذي يمتلك الامتداد المحدد للملف.


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


يحوّل سلسلة تمثل امتداد ملف إلى كائن من نوع [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | ملحق الملف للتحويل. إذا كان الملحق يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.


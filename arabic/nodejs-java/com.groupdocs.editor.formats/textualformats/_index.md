---
title: "TextualFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على جميع الصيغ النصية القائمة على النص بما في ذلك XML وHTML وغيرها."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

يحتوي على جميع التنسيقات النصية (المعتمدة على النص)، بما في ذلك العلامات (XML، HTML) وغيرها.
يتضمن الصيغ التالية:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Html](#Html) | مستند HyperText Markup Language (HTML) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. |
|
|  | [Xml](#Xml) | مستند eXtensible Markup Language (XML) يشبه HTML لكنه يختلف في استخدام العلامات لتعريف الكائنات. |
|
|  | [Txt](#Txt) | مستند نص عادي (TXT) يمثل مستندًا نصيًا يحتوي على نص عادي على شكل أسطر. |
|
|  | [Md](#Md) | Markdown هي لغة ترميز خفيفة لإنشاء نص منسق باستخدام محرر نص عادي. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) هو تنسيق ملف مفتوح المعيار لمشاركة البيانات يستخدم نصًا قابلًا للقراءة من قبل البشر لتخزين ونقل البيانات. |
|
|  | [Mhtml](#Mhtml) | تغليف MIME للوثائق المتعددة HTML هو تنسيق أرشيف صفحات ويب يُستخدم لدمج كود HTML وموارده المرافقة في ملف حاسوبي واحد. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help هو تنسيق مساعدة عبر الإنترنت مملوك لشركة Microsoft، ويتكون من مجموعة من صفحات HTML وفهرس وأدوات تنقل أخرى. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [TextualFormats](../../com.groupdocs.editor.formats/textualformats) التي لها الامتداد المحدد للملف. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


مستند HyperText Markup Language (HTML) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


مستند eXtensible Markup Language (XML) يشبه HTML لكنه يختلف في استخدام العلامات لتعريف الكائنات.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


مستند نص عادي (TXT) يمثل مستندًا نصيًا يحتوي على نص عادي على شكل أسطر.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown هي لغة ترميز خفيفة لإنشاء نص منسق باستخدام محرر نص عادي.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) هو تنسيق ملف مفتوح المعيار لمشاركة البيانات يستخدم نصًا قابلًا للقراءة من قبل البشر لتخزين ونقل البيانات.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


تغليف MIME للوثائق المتعددة HTML هو تنسيق أرشيف صفحات ويب يُستخدم لدمج كود HTML وموارده المرافقة في ملف حاسوبي واحد.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help هو تنسيق مساعدة عبر الإنترنت مملوك لشركة Microsoft، ويتكون من مجموعة من صفحات HTML وفهرس وأدوات تنقل أخرى.
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
القيمة: IEnumerable{TextualFormats} يحتوي على جميع نسخ [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [TextualFormats](../../com.groupdocs.editor.formats/textualformats) التي لها الامتداد المحدد للملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف للتحويل. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.


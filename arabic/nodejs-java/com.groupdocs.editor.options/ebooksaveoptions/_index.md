---
title: "EbookSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستند بجميع صيغ الكتب الإلكترونية المدعومة ePub و MOBI و AZW3."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستند بجميع صيغ الكتب الإلكترونية المدعومة: ePub، MOBI، و AZW3.

<br />

*** ** * ** ***

الصيغ المدعومة للكتب الإلكترونية:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (نشر إلكتروني)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (صيغة Kindle 8t)

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من EbookSaveOptions بصيغة إخراج ePub (يمكن تعديلها لاحقًا عبر |
OutputFormat
(خاصية (#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)))
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | ينشئ نسخة جديدة من [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) بصيغة إخراج كتاب إلكتروني إلزامية محددة، بينما تكون جميع المعلمات الأخرى افتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف الكتاب الإلكتروني. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف الكتاب الإلكتروني. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة في الملف الناتج. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة في الملف الناتج. |
|
|  | [getOutputFormat()](#getOutputFormat--) | يحدد صيغة ملف الكتاب الإلكتروني الناتج: IDPF ePub أو MOBI أو AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | يحدد صيغة ملف الكتاب الإلكتروني الناتج: IDPF ePub أو MOBI أو AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من EbookSaveOptions بصيغة إخراج ePub (يمكن تعديلها لاحقًا عبر
OutputFormat
(خاصية (#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)))


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


ينشئ نسخة جديدة من [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) بصيغة إخراج كتاب إلكتروني إلزامية محددة، بينما تكون جميع المعلمات الأخرى افتراضية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | صيغة الإخراج الإلزامية التي يجب حفظ الكتاب الإلكتروني بها |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف الكتاب الإلكتروني. القيمة الافتراضية هي
2
.
ضبطه على
0
سيؤدي ذلك إلى تعطيل التقسيم، بحيث يتم دمج جميع محتويات الكتاب الإلكتروني في حزمة واحدة داخل الملف الناتج.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على قيمة من 1 إلى 9، سيتم تقسيم المستند عند الفقرات المنسقة باستخدام

**Heading 1**
,
**Heading 2**
,
**Heading 3**
إلخ. الأنماط حتى مستوى العنوان المحدد.

بشكل افتراضي، فقط
**Heading 1**
و
**Heading 2**
الفقرات تتسبب في تقسيم المستند.
ضبط هذه الخاصية على الصفر (أو أقل من الصفر) سيؤدي إلى عدم تقسيم المستند على الإطلاق عند فقرات العناوين.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


يحدد الحد الأقصى لمستوى العناوين التي يتم عندها تقسيم ملف الكتاب الإلكتروني. القيمة الافتراضية هي
2
.
ضبطه على
0
سيؤدي ذلك إلى تعطيل التقسيم، بحيث يتم دمج جميع محتويات الكتاب الإلكتروني في حزمة واحدة داخل الملف الناتج.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على قيمة من 1 إلى 9، سيتم تقسيم المستند عند الفقرات المنسقة باستخدام

**Heading 1**
,
**Heading 2**
,
**Heading 3**
إلخ. الأنماط حتى مستوى العنوان المحدد.

بشكل افتراضي، فقط
**Heading 1**
و
**Heading 2**
الفقرات تتسبب في تقسيم المستند.
ضبط هذه الخاصية على الصفر (أو أقل من الصفر) سيؤدي إلى عدم تقسيم المستند على الإطلاق عند فقرات العناوين.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة في الملف الناتج.
القيمة الافتراضية هي
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة في الملف الناتج.
القيمة الافتراضية هي
false
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


يحدد صيغة ملف الكتاب الإلكتروني الناتج: IDPF ePub أو MOBI أو AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


يحدد صيغة ملف الكتاب الإلكتروني الناتج: IDPF ePub أو MOBI أو AZW3.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |


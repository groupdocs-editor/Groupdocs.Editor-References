---
title: "MhtmlSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ تغليف MIME الخاص بـ MHTML للوثائق HTML المجمعة"
type: docs
weight: 26
url: /ar/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات MHTML (MIME encapsulation of aggregate HTML documents).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | يحدد ما إذا كان سيتم استخدام عناوين URL من نوع CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المتضمنة في مستندات MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | يحدد ما إذا كان سيتم استخدام عناوين URL من نوع CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المتضمنة في مستندات MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة إلى MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة إلى MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | يحدد ما إذا كان سيتم تصدير معلومات اللغة إلى MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | يحدد ما إذا كان سيتم تصدير معلومات اللغة إلى MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


يحدد ما إذا كان سيتم استخدام عناوين URL من نوع CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المتضمنة في مستندات MHTML. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***


بشكل افتراضي، يتم الإشارة إلى الموارد في مستندات MHTML بواسطة اسم الملف (على سبيل المثال، "image.png")، والذي يتم مطابقته مع رؤوس "Content-Location" لأجزاء MIME. يتيح هذا الخيار طريقة بديلة، حيث تُكتب الإشارات إلى ملفات الموارد كعناوين URL من نوع CID (Content-ID) (على سبيل المثال، "cid:image.png") وتُطابق مع رؤوس "Content-ID".


نظريًا، لا ينبغي أن يكون هناك فرق بين طريقتي الإشارة ويجب أن تعمل أي منهما بشكل جيد في أي متصفح أو عميل بريد. عمليًا، ومع ذلك، بعض العملاء يفشلون في جلب الموارد بواسطة اسم الملف. إذا كان متصفحك أو عميل البريد يرفض تحميل الموارد المتضمنة في مستند MTHML (لا يعرض الصور أو لا يحمل أنماط CSS)، جرّب تصدير المستند باستخدام عناوين URL من نوع CID.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


يحدد ما إذا كان سيتم استخدام عناوين URL من نوع CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المتضمنة في مستندات MHTML. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***


بشكل افتراضي، يتم الإشارة إلى الموارد في مستندات MHTML بواسطة اسم الملف (على سبيل المثال، "image.png")، والذي يتم مطابقته مع رؤوس "Content-Location" لأجزاء MIME. يتيح هذا الخيار طريقة بديلة، حيث تُكتب الإشارات إلى ملفات الموارد كعناوين URL من نوع CID (Content-ID) (على سبيل المثال، "cid:image.png") وتُطابق مع رؤوس "Content-ID".


نظريًا، لا ينبغي أن يكون هناك فرق بين طريقتي الإشارة ويجب أن تعمل أي منهما بشكل جيد في أي متصفح أو عميل بريد. عمليًا، ومع ذلك، بعض العملاء يفشلون في جلب الموارد بواسطة اسم الملف. إذا كان متصفحك أو عميل البريد يرفض تحميل الموارد المتضمنة في مستند MTHML (لا يعرض الصور أو لا يحمل أنماط CSS)، جرّب تصدير المستند باستخدام عناوين URL من نوع CID.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة إلى MHTML. القيمة الافتراضية هي
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة إلى MHTML. القيمة الافتراضية هي
false
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


يحدد ما إذا كان سيتم تصدير معلومات اللغة إلى MHTML. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على true، يقوم GroupDocs.Editor بإصدار سمة HTML ‎lang‎ على عناصر المستند التي تحدد اللغة. قد يكون ذلك ضروريًا للحفاظ على الدلالات المتعلقة باللغة.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


يحدد ما إذا كان سيتم تصدير معلومات اللغة إلى MHTML. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على true، يقوم GroupDocs.Editor بإصدار سمة HTML ‎lang‎ على عناصر المستند التي تحدد اللغة. قد يكون ذلك ضروريًا للحفاظ على الدلالات المتعلقة باللغة.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |


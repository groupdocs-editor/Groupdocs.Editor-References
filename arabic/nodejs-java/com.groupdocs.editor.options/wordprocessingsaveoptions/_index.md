---
title: "WordProcessingSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستندات المتوافقة مع WordProcessing بعد تحريرها"
type: docs
weight: 48
url: /ar/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة للتوليد والحفظ
مستندات متوافقة مع WordProcessing بعد تحريرها


*** ** * ** ***

يتم تطبيق WordProcessingSaveOptions في الحالات التي يوجد فيها كائن من فئة EditableDocument، والذي يحتوي على محتوى مستند تم تحريره، ويتطلب حفظ هذا المحتوى إلى مستند جديد بصيغة WordProcessing.

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء كائن جديد من WordProcessingSaveOptions بصيغة إخراج DOCX (يمكن تعديلها لاحقًا عبر |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | ينشئ كائنًا جديدًا من WordProcessingSaveOptions بالمحدد |
صيغة إخراج WordProcessing الإلزامية، بينما جميع المعلمات الأخرى هي
افتراضي
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل الترقيم الصفحات الذي سيُستخدم لحفظ |
المستند.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل الترقيم الصفحات الذي سيُستخدم لحفظ |
المستند.
|
|  | [getPassword()](#getPassword--) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ |
تُستخدم لتشفير مستند WordProcessing المُولد.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ |
تُستخدم لتشفير مستند WordProcessing المُولد.
|
|  | [getOutputFormat()](#getOutputFormat--) | يسمح بتحديد صيغة WordProcessing، والتي ستُستخدم للحفظ |
المستند
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | يسمح بتحديد صيغة WordProcessing، والتي ستُستخدم للحفظ |
المستند
|
|  | [getLocale()](#getLocale--) | يسمح بتعيين تجاوز الإعداد الإقليمي الافتراضي (اللغة) لـ WordProcessing |
المستند، والذي سيُطبق أثناء إنشائه.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | يسمح بتعيين تجاوز الإعداد الإقليمي الافتراضي (اللغة) لـ WordProcessing |
المستند، والذي سيُطبق أثناء إنشائه.
|
|  | [getLocaleBi()](#getLocaleBi--) | يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing |
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشائه.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing |
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشائه.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing |
لنص شرق آسيا، والذي سيُطبق أثناء إنشائه.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing |
لنص شرق آسيا، والذي سيُطبق أثناء إنشائه.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء توليد المستند من |
HTML، مما يقلل الأداء كتكلفة لتقليل استخدام الذاكرة.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء توليد المستند من |
HTML، مما يقلل الأداء كتكلفة لتقليل استخدام الذاكرة.
|
|  | [getProtection()](#getProtection--) | يسمح بالتحكم وتطبيق خيارات حماية المستند لـ |
مستند WordProcessing بأي صيغة، والذي يدعم
الحماية.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | يسمح بالتحكم وتطبيق خيارات حماية المستند لـ |
مستند WordProcessing بأي صيغة، والذي يدعم
الحماية.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing |
المستند.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing |
المستند.
|
|  | [deepClone()](#deepClone--) | ينشئ ويعيد نسخة كاملة من هذه المثيلة من |
فئة WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


يقوم هذا المُنشئ بدون معلمات بإنشاء كائن جديد من WordProcessingSaveOptions بصيغة إخراج DOCX (يمكن تعديلها لاحقًا عبر
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


ينشئ كائنًا جديدًا من WordProcessingSaveOptions بالمحدد
صيغة إخراج WordProcessing الإلزامية، بينما جميع المعلمات الأخرى هي
افتراضي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | تنسيق الإخراج الإلزامي، الذي يجب حفظ مستند WordProcessing فيه |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل الترقيم الصفحات الذي سيُستخدم لحفظ
المستند. إذا تم فتح المستند الأصلي وتحريره في وضع الترقيم
الوضع، يجب تمكين هذا الخيار أيضًا. بشكل افتراضي يكون معطلاً.


**Returns:**
منطقي -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل الترقيم الصفحات الذي سيُستخدم لحفظ
المستند. إذا تم فتح المستند الأصلي وتحريره في وضع الترقيم
الوضع، يجب تمكين هذا الخيار أيضًا. بشكل افتراضي يكون معطلاً.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ
يُستخدم لتشفير مستند WordProcessing المُولد. حدد NULL أو
سلسلة فارغة لإزالة (تنظيف) كلمة المرور.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ
يُستخدم لتشفير مستند WordProcessing المُولد. حدد NULL أو
سلسلة فارغة لإزالة (تنظيف) كلمة المرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


يسمح بتحديد صيغة WordProcessing، والتي ستُستخدم للحفظ
المستند


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


يسمح بتحديد صيغة WordProcessing، والتي ستُستخدم للحفظ
المستند


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


يسمح بتعيين تجاوز الإعداد الإقليمي الافتراضي (اللغة) لـ WordProcessing
المستند، الذي سيُطبق أثناء إنشائه. عندما لا يكون
محددًا (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف (أو
اختيار) لغة المستند وفقًا لإعداداته الخاصة أو غيرها
العوامل.


*** ** * ** ***

يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص العام في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من النص مكتوبة بلغات مختلفة.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


يسمح بتعيين تجاوز الإعداد الإقليمي الافتراضي (اللغة) لـ WordProcessing
المستند، الذي سيُطبق أثناء إنشائه. عندما لا يكون
محددًا (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف (أو
اختيار) لغة المستند وفقًا لإعداداته الخاصة أو غيرها
العوامل.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص العام في
المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوب بلغات مختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشاء. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو غيره
البرنامج) بالكشف (أو الاختيار) عن لغة المستند RTL وفقًا لـ
إعداداته الخاصة أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص RTL العام
في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوب بلغات مختلفة.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


يسمح بتعيين تجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشاء. عندما لا يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو غيره
البرنامج) بالكشف (أو الاختيار) عن لغة المستند RTL وفقًا لـ
إعداداته الخاصة أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص RTL العام
في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوب بلغات مختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing
لنص شرق آسيا، الذي سيُطبق أثناء إنشائه. عندما
لم يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف
(أو الاختيار) لغة المستند شرق آسيا وفقًا لإعداداته الخاصة
أو عوامل أخرى.

*** ** * ** ***


هذا الخيار يفرض تطبيق الإعداد الإقليمي المحدد على الإجمالي
نص شرق آسيوي في المستند. لا تستخدمه إذا كان المستند يحتوي على
أجزاء مختلفة من النص، المكتوبة بلغات مختلفة
لغات.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


يسمح بتجاوز الإعداد الإقليمي (اللغة) لمستند WordProcessing
لنص شرق آسيا، الذي سيُطبق أثناء إنشائه. عندما
لم يتم تحديده (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف
(أو الاختيار) لغة المستند شرق آسيا وفقًا لإعداداته الخاصة
أو عوامل أخرى.

*** ** * ** ***


هذا الخيار يفرض تطبيق الإعداد الإقليمي المحدد على الإجمالي
نص شرق آسيوي في المستند. لا تستخدمه إذا كان المستند يحتوي على
أجزاء مختلفة من النص، المكتوبة بلغات مختلفة
لغات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء توليد المستند من
HTML، مما يقلل الأداء كتكلفة لتقليل استخدام الذاكرة.
تعيين هذا الخيار إلى true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة
أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل
الأداء).


**Returns:**
منطقي -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء توليد المستند من
HTML، مما يقلل الأداء كتكلفة لتقليل استخدام الذاكرة.
تعيين هذا الخيار إلى true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة
أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل
الأداء).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


يسمح بالتحكم وتطبيق خيارات حماية المستند لـ
مستند WordProcessing بأي صيغة، والذي يدعم
الحماية. القيمة الافتراضية هي NULL - لن يتم استخدام حماية المستند.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


يسمح بالتحكم وتطبيق خيارات حماية المستند لـ
مستند WordProcessing بأي صيغة، والذي يدعم
الحماية. القيمة الافتراضية هي NULL - لن يتم استخدام حماية المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing
المستند. القيمة الافتراضية لا تضم أي خطوط (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing
المستند. القيمة الافتراضية لا تضم أي خطوط (NotEmbed).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


ينشئ ويعيد نسخة كاملة من هذه المثيلة من
فئة WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance


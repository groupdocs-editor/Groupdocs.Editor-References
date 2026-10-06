---
title: "WordProcessingSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ المستندات المتوافقة مع معالجة النصوص بعد تعديلها."
type: docs
weight: 48
url: /ar/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة للإنشاء والحفظ
المستندات المتوافقة مع معالجة النصوص بعد تعديلها


*** ** * ** ***

يُطبق WordProcessingSaveOptions في الحالات التي يكون فيها كائن من فئة EditableDocument يحتوي على محتوى مستند معدل، ويُطلب حفظ هذا المحتوى إلى مستند جديد بصيغة معالجة النصوص.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من WordProcessingSaveOptions بصيغة إخراج DOCX (يمكن تعديلها لاحقًا عبر |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) الخاصية)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | إنشاء نسخة جديدة من WordProcessingSaveOptions مع المحدد |
تنسيق إخراج WordProcessing الإلزامي، بينما تكون جميع المعلمات الأخرى
الافتراضي
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات الذي سيُستخدم لحفظ |
المستند.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات الذي سيُستخدم لحفظ |
المستند.
|
|  | [getPassword()](#getPassword--) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستكون |
مستخدمة لتشفير المستند WordProcessing المُنشأ.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستكون |
مستخدمة لتشفير المستند WordProcessing المُنشأ.
|
|  | [getOutputFormat()](#getOutputFormat--) | يسمح بتحديد تنسيق WordProcessing، والذي سيُستخدم للحفظ |
المستند
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | يسمح بتحديد تنسيق WordProcessing، والذي سيُستخدم للحفظ |
المستند
|
|  | [getLocale()](#getLocale--) | يسمح بتعيين تجاوز اللغة الافتراضية (locale) لـ WordProcessing |
المستند، والذي سيُطبق أثناء إنشائه.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | يسمح بتعيين تجاوز اللغة الافتراضية (locale) لـ WordProcessing |
المستند، والذي سيُطبق أثناء إنشائه.
|
|  | [getLocaleBi()](#getLocaleBi--) | يسمح بتعيين تجاوز locale (اللغة) للمستند WordProcessing |
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشائه.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | يسمح بتعيين تجاوز locale (اللغة) للمستند WordProcessing |
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
إنشائه.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | يسمح بتجاوز locale (اللغة) للمستند WordProcessing |
لنص شرق آسيا، والذي سيُطبق أثناء إنشائه.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | يسمح بتجاوز locale (اللغة) للمستند WordProcessing |
لنص شرق آسيا، والذي سيُطبق أثناء إنشائه.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من |
HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من |
HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
|
|  | [getProtection()](#getProtection--) | يسمح بالتحكم وتطبيق خيارات حماية المستند لـ |
مستند WordProcessing بأي تنسيق، والذي يدعم
الحماية.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | يسمح بالتحكم وتطبيق خيارات حماية المستند لـ |
مستند WordProcessing بأي تنسيق، والذي يدعم
الحماية.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing |
المستند.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | مسؤول عن تضمين موارد الخطوط في مخرجات WordProcessing |
المستند.
|
|  | [deepClone()](#deepClone--) | ينشئ ويعيد نسخة كاملة من هذه الحالة من |
فئة WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من WordProcessingSaveOptions بصيغة إخراج DOCX (يمكن تعديلها لاحقًا عبر
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) الخاصية)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


إنشاء نسخة جديدة من WordProcessingSaveOptions مع المحدد
تنسيق إخراج WordProcessing الإلزامي، بينما تكون جميع المعلمات الأخرى
الافتراضي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | تنسيق الإخراج الإلزامي، الذي يجب حفظ مستند WordProcessing به |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل ترقيم الصفحات الذي سيُستخدم لحفظ
المستند. إذا تم فتح المستند الأصلي وتحريره في وضع الترقيم
الوضع، يجب تمكين هذا الخيار أيضًا. بشكل افتراضي يكون معطلاً.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل ترقيم الصفحات الذي سيُستخدم لحفظ
المستند. إذا تم فتح المستند الأصلي وتحريره في وضع الترقيم
الوضع، يجب تمكين هذا الخيار أيضًا. بشكل افتراضي يكون معطلاً.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستكون
يُستخدم لتشفير مستند WordProcessing المُولد. حدد NULL أو
سلسلة فارغة لإزالة (تنظيف) كلمة المرور.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستكون
يُستخدم لتشفير مستند WordProcessing المُولد. حدد NULL أو
سلسلة فارغة لإزالة (تنظيف) كلمة المرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


يسمح بتحديد تنسيق WordProcessing، والذي سيُستخدم للحفظ
المستند


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


يسمح بتحديد تنسيق WordProcessing، والذي سيُستخدم للحفظ
المستند


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


يسمح بتعيين تجاوز اللغة الافتراضية (locale) لـ WordProcessing
المستند، الذي سيُطبق أثناء إنشائه. عندما لا يكون
محددًا (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف (أو
اختيار) إعداد لغة المستند وفقًا لإعداداته الخاصة أو غيرها
العوامل.


*** ** * ** ***

يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص الكامل في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من النص مكتوبة بلغات مختلفة.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


يسمح بتعيين تجاوز اللغة الافتراضية (locale) لـ WordProcessing
المستند، الذي سيُطبق أثناء إنشائه. عندما لا يكون
محددًا (القيمة الافتراضية)، سيقوم MS Word (أو برنامج آخر) بالكشف (أو
اختيار) إعداد لغة المستند وفقًا لإعداداته الخاصة أو غيرها
العوامل.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص الكامل في
المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوبة بلغات مختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


يسمح بتعيين تجاوز locale (اللغة) للمستند WordProcessing
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
الإنشاء. عندما لا يتم تحديده (القيمة الافتراضية)، MS Word (أو غير ذلك
البرنامج) سيكتشف (أو يختار) إعداد لغة RTL للمستند وفقًا لـ
إعداداته الخاصة أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص الكامل RTL
في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوبة بلغات مختلفة.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


يسمح بتعيين تجاوز locale (اللغة) للمستند WordProcessing
لنص RTL (من اليمين إلى اليسار)، والذي سيُطبق أثناء
الإنشاء. عندما لا يتم تحديده (القيمة الافتراضية)، MS Word (أو غير ذلك
البرنامج) سيكتشف (أو يختار) إعداد لغة RTL للمستند وفقًا لـ
إعداداته الخاصة أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على النص الكامل RTL
في المستند. لا تستخدمه إذا كان المستند يحتوي على أجزاء مختلفة من
النص، المكتوبة بلغات مختلفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


يسمح بتجاوز locale (اللغة) للمستند WordProcessing
لنص شرق آسيا، الذي سيُطبق أثناء إنشائه. عندما
لا يتم تحديده (القيمة الافتراضية)، MS Word (أو برنامج آخر) سيكتشف
(أو يختار) إعداد لغة شرق آسيا للمستند وفقًا لإعداداته الخاصة
أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على الإجمالي
نص شرق آسيا في المستند. لا تستخدمه إذا كان المستند يحتوي على
أجزاء مختلفة من النص، المكتوبة على مختلفة
لغات.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


يسمح بتجاوز locale (اللغة) للمستند WordProcessing
لنص شرق آسيا، الذي سيُطبق أثناء إنشائه. عندما
لا يتم تحديده (القيمة الافتراضية)، MS Word (أو برنامج آخر) سيكتشف
(أو يختار) إعداد لغة شرق آسيا للمستند وفقًا لإعداداته الخاصة
أو عوامل أخرى.

*** ** * ** ***


يقوم هذا الخيار بفرض تطبيق اللغة المحددة على الإجمالي
نص شرق آسيا في المستند. لا تستخدمه إذا كان المستند يحتوي على
أجزاء مختلفة من النص، المكتوبة على مختلفة
لغات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من
HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
تعيين هذا الخيار إلى true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة
أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أفضل
أداء).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من
HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
تعيين هذا الخيار إلى true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة
أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أفضل
أداء).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


يسمح بالتحكم وتطبيق خيارات حماية المستند لـ
مستند WordProcessing بأي تنسيق، والذي يدعم
الحماية. القيمة الافتراضية هي NULL - لن يتم استخدام حماية المستند.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


يسمح بالتحكم وتطبيق خيارات حماية المستند لـ
مستند WordProcessing بأي تنسيق، والذي يدعم
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
| القيمة | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


ينشئ ويعيد نسخة كاملة من هذه الحالة من
فئة WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance


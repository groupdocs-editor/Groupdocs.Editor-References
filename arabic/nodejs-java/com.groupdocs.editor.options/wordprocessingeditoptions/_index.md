---
title: "WordProcessingEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة المتوافقة مع WordProcessing Words مثل DOCX وRTF وODT وغيرها."
type: docs
weight: 44
url: /ar/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة
صيغ WordProcessing (متوافقة مع Words) مثل DOC(X) وRTF وODT وغيرها.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions |
فئة، حيث يتم ضبط جميع الخيارات على القيم الافتراضية
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions |
فئة مع ترقيم صفحات محدد وجميع الخيارات الأخرى الافتراضية
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في |
شكل سمات HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في |
شكل سمات HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي |
تُستخدم في المحتوى النصي للمستند.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي |
تُستخدم في المحتوى النصي للمستند.
|
|  | [getFontExtraction()](#getFontExtraction--) | مسؤول عن استخراج موارد الخط التي تُستخدم في الإدخال |
مستند WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | مسؤول عن استخراج موارد الخط التي تُستخدم في الإدخال |
مستند WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | يسمح بتحديد اسم فئة، سيتم وضعه في الخاصية 'class' |
السمات في كل عنصر HTML، التي تمثل حقلًا ما في الإدخال
مستند WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | يسمح بتحديد اسم فئة، سيتم وضعه في الخاصية 'class' |
السمات في كل عنصر HTML، التي تمثل حقلًا ما في الإدخال
مستند WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية ( |
false
) أو كأنماط مضمنة في ترميز HTML (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية ( |
false
) أو كأنماط مضمنة في ترميز HTML (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions
فئة، حيث يتم ضبط جميع الخيارات على القيم الافتراضية


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions
فئة مع ترقيم صفحات محدد وجميع الخيارات الأخرى الافتراضية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | enablePagination | boolean | علامة ترقيم الصفحات، التي تمكّن إخراج HTML، مُعدّة لوضع الصفحات |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بواسطة
القيمة الافتراضية معطلة (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بواسطة
القيمة الافتراضية معطلة (false).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في
شكل من سمات HTML 'lang'. قد يكون هذا الخيار مفيدًا للعودة
تحويل المستندات متعددة اللغات. بشكل افتراضي يكون معطلاً
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في
شكل من سمات HTML 'lang'. قد يكون هذا الخيار مفيدًا للعودة
تحويل المستندات متعددة اللغات. بشكل افتراضي يكون معطلاً
(false).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي
تُستخدم في المحتوى النصي للمستند.
القيمة: true إذا كان من الضروري استخراج موارد الخطوط التي تُستخدم فقط في محتوى النص بالمستند؛ وإلا، false. القيمة الافتراضية هي false.


*** ** * ** ***

ليس كل الخطوط المستخدمة في مستند WordProcessing تُستَخدم مباشرة بنسبة 100% (مُطبقة على نص ما). قد يحدث أن يُشار إلى خط في المستند وقد يكون مضمّنًا، لكنه لا يُطبّق على أي جزء من النص. على سبيل المثال، قد يُرفق خط ما بنمط معين، لكن هذا النمط لا يُطبق على أي جزء من النص. يتحكم هذا الخيار في كيفية معالجة مثل هذه الحالات.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي
تُستخدم في المحتوى النصي للمستند.
القيمة: true إذا كان من الضروري استخراج موارد الخطوط التي تُستخدم فقط في محتوى النص بالمستند؛ وإلا، false. القيمة الافتراضية هي false.


*** ** * ** ***

ليس كل الخطوط المستخدمة في مستند WordProcessing تُستَخدم مباشرة بنسبة 100% (مُطبقة على نص ما). قد يحدث أن يُشار إلى خط في المستند وقد يكون مضمّنًا، لكنه لا يُطبّق على أي جزء من النص. على سبيل المثال، قد يُرفق خط ما بنمط معين، لكن هذا النمط لا يُطبق على أي جزء من النص. يتحكم هذا الخيار في كيفية معالجة مثل هذه الحالات.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


مسؤول عن استخراج موارد الخط التي تُستخدم في الإدخال
مستند WordProcessing. بشكل افتراضي لا يستخرج أي خطوط
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


مسؤول عن استخراج موارد الخط التي تُستخدم في الإدخال
مستند WordProcessing. بشكل افتراضي لا يستخرج أي خطوط
(NotExtract).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


يسمح بتحديد اسم فئة، سيتم وضعه في الخاصية 'class'
السمات في كل عنصر HTML، التي تمثل حقلًا ما في الإدخال
مستند WordProcessing. بشكل افتراضي هو NULL - سمات 'class' ليست
مطبقة.


*** ** * ** ***

تقريبًا جميع الصيغ من عائلة صيغ WordProcessing تحتوي على حقول \\u2014 كيانات مستند محددة، تسمح بالحصول على بيانات الإدخال من المستخدمين. هناك مجموعة واسعة من الحقول: صناديق نصية، مربعات اختيار، قوائم منسدلة، أزرار، محددات تاريخ/وقت، إلخ. جميعها تُترجم إلى هياكل وعناصر HTML الأنسب، مع الحفاظ على البيانات التي أدخلها المستخدم إذا كانت موجودة في المستند الأصلي. في حالات الاستخدام المحددة قد يكون المطلوب فقط جمع البيانات المدخلة على جانب العميل بدلاً من تعديل محتوى المستند بالكامل. لهذا الغرض يلزم تحديد عناصر التحكم في الإدخال بطريقة ما لجمعها مع بياناتها على جانب العميل. تسمح هذه الخاصية بتحديد اسم فئة سيتم تطبيقه على كل عنصر تحكم إدخال في ترميز HTML، بحيث يتمكن كود العميل من استعراض بنية مستند HTML وجمع البيانات.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


يسمح بتحديد اسم فئة، سيتم وضعه في الخاصية 'class'
السمات في كل عنصر HTML، التي تمثل حقلًا ما في الإدخال
مستند WordProcessing. بشكل افتراضي هو NULL - سمات 'class' ليست
مطبقة.


*** ** * ** ***

تقريبًا جميع الصيغ من عائلة صيغ WordProcessing تحتوي على حقول \\u2014 كيانات مستند محددة، تسمح بالحصول على بيانات الإدخال من المستخدمين. هناك مجموعة واسعة من الحقول: صناديق نصية، مربعات اختيار، قوائم منسدلة، أزرار، محددات تاريخ/وقت، إلخ. جميعها تُترجم إلى هياكل وعناصر HTML الأنسب، مع الحفاظ على البيانات التي أدخلها المستخدم إذا كانت موجودة في المستند الأصلي. في حالات الاستخدام المحددة قد يكون المطلوب فقط جمع البيانات المدخلة على جانب العميل بدلاً من تعديل محتوى المستند بالكامل. لهذا الغرض يلزم تحديد عناصر التحكم في الإدخال بطريقة ما لجمعها مع بياناتها على جانب العميل. تسمح هذه الخاصية بتحديد اسم فئة سيتم تطبيقه على كل عنصر تحكم إدخال في ترميز HTML، بحيث يتمكن كود العميل من استعراض بنية مستند HTML وجمع البيانات.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية (
false
) أو كأنماط مضمنة في ترميز HTML (
true
). بشكل افتراضي تُستخدم الأنماط الخارجية (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية (
false
) أو كأنماط مضمنة في ترميز HTML (
true
). بشكل افتراضي تُستخدم الأنماط الخارجية (
false
).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |


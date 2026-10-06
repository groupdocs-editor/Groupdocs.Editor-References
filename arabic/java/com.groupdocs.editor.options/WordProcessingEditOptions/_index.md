---
title: "WordProcessingEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المتوافقة مع WordProcessing والتي تدعمها مثل DOCX وRTF وODT وغيرها"
type: docs
weight: 44
url: /ar/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة
صيغ WordProcessing (متوافقة مع Words) مثل DOC(X)، RTF، ODT إلخ.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions |
class، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions |
class مع ترقيم محدد وجميع الخيارات الأخرى افتراضية
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في |
شكل من سمات HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في |
شكل من سمات HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي |
تُستخدم في المحتوى النصي للمستند.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي |
تُستخدم في المحتوى النصي للمستند.
|
|  | [getFontExtraction()](#getFontExtraction--) | مسؤول عن استخراج موارد الخط التي تُستخدم في |
مستند WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | مسؤول عن استخراج موارد الخط التي تُستخدم في |
مستند WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | يسمح بتحديد اسم class، الذي سيُوضع في السمة 'class' |
السمات في كل عنصر HTML، الذي يمثل حقلًا ما في الإدخال
مستند WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | يسمح بتحديد اسم class، الذي سيُوضع في السمة 'class' |
السمات في كل عنصر HTML، الذي يمثل حقلًا ما في الإدخال
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
class، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


ينشئ ويعيد نسخة جديدة من WordProcessingEditOptions
class مع ترقيم محدد وجميع الخيارات الأخرى افتراضية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | enablePagination | boolean | علامة Pagination التي تُتيح إخراج HTML، مُعدَّلة للوضع الصفحي |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بواسطة
الإعداد الافتراضي معطل (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. بواسطة
الإعداد الافتراضي معطل (false).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في
شكل من سمات HTML 'lang'. قد يكون هذا الخيار مفيدًا للعودة المتبادلة
تحويل المستندات متعددة اللغات. بشكل افتراضي يكون معطَّلًا
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


يحدد ما إذا كانت معلومات اللغة تُصدَّر إلى ترميز HTML في
شكل من سمات HTML 'lang'. قد يكون هذا الخيار مفيدًا للعودة المتبادلة
تحويل المستندات متعددة اللغات. بشكل افتراضي يكون معطَّلًا
(false).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي
تُستخدم في المحتوى النصي للمستند.
القيمة:  true  إذا كان من الضروري استخراج موارد الخط فقط التي تُستخدم في المحتوى النصي للمستند؛ وإلا،  false . القيمة الافتراضية هي  false .


*** ** * ** ***

ليس كل الخطوط المستخدمة في مستند WordProcessing تُستَخدم مباشرة بنسبة 100٪ (مُطبقة على نص ما). قد يحدث أن يُشار إلى خط في المستند وقد يكون مضمّنًا، لكنه لا يُطبق على أي جزء من النص. على سبيل المثال، قد يُرفق خط ما بنمط معين، لكن هذا النمط لا يُطبق على أي جزء من النص. هذا الخيار يتحكم في كيفية معالجة مثل هذه الحالات.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخراج موارد الخط فقط التي
تُستخدم في المحتوى النصي للمستند.
القيمة:  true  إذا كان من الضروري استخراج موارد الخط فقط التي تُستخدم في المحتوى النصي للمستند؛ وإلا،  false . القيمة الافتراضية هي  false .


*** ** * ** ***

ليس كل الخطوط المستخدمة في مستند WordProcessing تُستَخدم مباشرة بنسبة 100٪ (مُطبقة على نص ما). قد يحدث أن يُشار إلى خط في المستند وقد يكون مضمّنًا، لكنه لا يُطبق على أي جزء من النص. على سبيل المثال، قد يُرفق خط ما بنمط معين، لكن هذا النمط لا يُطبق على أي جزء من النص. هذا الخيار يتحكم في كيفية معالجة مثل هذه الحالات.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


مسؤول عن استخراج موارد الخط التي تُستخدم في
مستند WordProcessing. بشكل افتراضي لا يستخرج أي خطوط
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


مسؤول عن استخراج موارد الخط التي تُستخدم في
مستند WordProcessing. بشكل افتراضي لا يستخرج أي خطوط
(NotExtract).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


يسمح بتحديد اسم class، الذي سيُوضع في السمة 'class'
السمات في كل عنصر HTML، الذي يمثل حقلًا ما في الإدخال
مستند WordProcessing. بشكل افتراضي هو NULL - سمات 'class' غير موجودة
مطبق.


*** ** * ** ***

تقريبًا جميع الصيغ من عائلة صيغ معالجة النصوص تحتوي على حقول \\u2014 كيانات مستند محددة، تسمح بالحصول على بيانات الإدخال من المستخدمين. هناك مجموعة واسعة من الحقول: صناديق نصية، مربعات اختيار، قوائم منسدلة، أزرار، مختارات التاريخ/الوقت، إلخ. يتم تحويل جميعها إلى هياكل وعناصر HTML الأنسب، مع الحفاظ على بيانات المستخدم المدخلة إذا كانت موجودة في المستند الأصلي. في حالات الاستخدام المحددة قد يُطلب جمع البيانات المدخلة فقط على جانب العميل بدلاً من تحرير محتوى المستند بالكامل. لهذا الغرض يلزم تحديد عناصر التحكم في الإدخال بطريقة ما لجلبها مع بياناتها على جانب العميل. تسمح هذه الخاصية بتحديد اسم فئة سيتم تطبيقه على كل عنصر تحكم إدخال في ترميز HTML، بحيث يتمكن كود العميل من التجول في بنية مستند HTML وجمع البيانات.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


يسمح بتحديد اسم class، الذي سيُوضع في السمة 'class'
السمات في كل عنصر HTML، الذي يمثل حقلًا ما في الإدخال
مستند WordProcessing. بشكل افتراضي هو NULL - سمات 'class' غير موجودة
مطبق.


*** ** * ** ***

تقريبًا جميع الصيغ من عائلة صيغ معالجة النصوص تحتوي على حقول \\u2014 كيانات مستند محددة، تسمح بالحصول على بيانات الإدخال من المستخدمين. هناك مجموعة واسعة من الحقول: صناديق نصية، مربعات اختيار، قوائم منسدلة، أزرار، مختارات التاريخ/الوقت، إلخ. يتم تحويل جميعها إلى هياكل وعناصر HTML الأنسب، مع الحفاظ على بيانات المستخدم المدخلة إذا كانت موجودة في المستند الأصلي. في حالات الاستخدام المحددة قد يُطلب جمع البيانات المدخلة فقط على جانب العميل بدلاً من تحرير محتوى المستند بالكامل. لهذا الغرض يلزم تحديد عناصر التحكم في الإدخال بطريقة ما لجلبها مع بياناتها على جانب العميل. تسمح هذه الخاصية بتحديد اسم فئة سيتم تطبيقه على كل عنصر تحكم إدخال في ترميز HTML، بحيث يتمكن كود العميل من التجول في بنية مستند HTML وجمع البيانات.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


يتحكم في مكان تخزين بيانات التنسيق والتصميم لمستند WordProcessing المدخل: في ورقة أنماط خارجية (
false
) أو كأنماط مضمنة في ترميز HTML (
true
). بشكل افتراضي يتم استخدام الأنماط الخارجية (
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
). بشكل افتراضي يتم استخدام الأنماط الخارجية (
false
).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |


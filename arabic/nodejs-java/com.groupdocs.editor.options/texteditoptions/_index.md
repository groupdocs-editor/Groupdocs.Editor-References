---
title: "TextEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحميل مستندات النص العادي TXT"
type: docs
weight: 39
url: /ar/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحميل مستندات النص العادي (TXT).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الفتح
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الفتح
|
|  | [getRecognizeLists()](#getRecognizeLists--) | يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عندما يكون المستند |
مستوردًا من تنسيق النص العادي.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عندما يكون المستند |
مستوردًا من تنسيق النص العادي.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | يحصل أو يضبط الخيار المفضل لمعالجة المسافة البادئة. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | يحصل أو يضبط الخيار المفضل لمعالجة المسافة البادئة. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | يحصل أو يضبط الخيار المفضل لمعالجة المسافة اللاحقة. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | يحصل أو يضبط الخيار المفضل لمعالجة المسافة اللاحقة. |
|
|  | [getEnablePagination()](#getEnablePagination--) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | يسمح بتمكين أو تعطيل ترقيم الصفحات في مستند HTML الناتج. |
|
|  | [getDirection()](#getDirection--) | يسمح بتحديد اتجاه تدفق النص في النص العادي المدخل |
المستند.
|
|  | [setDirection(int value)](#setDirection-int-) | يسمح بتحديد اتجاه تدفق النص في النص العادي المدخل |
المستند.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الفتح


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الفتح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عندما يكون المستند
مستوردًا من تنسيق النص العادي. القيمة الافتراضية هي true.


*** ** * ** ***

إذا تم تعيين هذا الخيار إلى false، يكتشف خوارزمية التعرف على القوائم فقرات القوائم عندما تنتهي أرقام القوائم إما بنقطة أو قوس右 أو رموز تعداد (مثل "\\u2022", "\*", "-" أو "o"). إذا تم تعيين هذا الخيار إلى true، تُستخدم الفراغات أيضًا كفواصل لأرقام القوائم: خوارزمية التعرف على القوائم للترقيم النمط العربي (1., 1.1.2.) تستخدم كلًا من الفراغات والنقطة (".") كرموز.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


يسمح بتحديد كيفية التعرف على عناصر القوائم المرقمة عندما يكون المستند
مستوردًا من تنسيق النص العادي. القيمة الافتراضية هي true.


*** ** * ** ***

إذا تم تعيين هذا الخيار إلى false، يكتشف خوارزمية التعرف على القوائم فقرات القوائم عندما تنتهي أرقام القوائم إما بنقطة أو قوس右 أو رموز تعداد (مثل "\\u2022", "\*", "-" أو "o"). إذا تم تعيين هذا الخيار إلى true، تُستخدم الفراغات أيضًا كفواصل لأرقام القوائم: خوارزمية التعرف على القوائم للترقيم النمط العربي (1., 1.1.2.) تستخدم كلًا من الفراغات والنقطة (".") كرموز.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


يحصل أو يضبط الخيار المفضل لمعالجة المسافة البادئة. بشكل افتراضي
يحوِّل المسافات البادئة إلى مسافة إزاحة إلى اليسار.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


يحصل أو يضبط الخيار المفضل لمعالجة المسافة البادئة. بشكل افتراضي
يحوِّل المسافات البادئة إلى مسافة إزاحة إلى اليسار.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


يحصل أو يضبط الخيار المفضل لمعالجة المسافة اللاحقة. بشكل افتراضي
يقص جميع المسافات الزائدة في النهاية.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


يحصل أو يضبط الخيار المفضل لمعالجة المسافة اللاحقة. بشكل افتراضي
يقص جميع المسافات الزائدة في النهاية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

### getDirection() {#getDirection--}
```
public final int getDirection()
```


يسمح بتحديد اتجاه تدفق النص في النص العادي المدخل
المستند. بشكل افتراضي من اليسار إلى اليمين.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


يسمح بتحديد اتجاه تدفق النص في النص العادي المدخل
المستند. بشكل افتراضي من اليسار إلى اليمين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |


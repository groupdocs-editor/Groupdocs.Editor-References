---
title: "FormatFamilyBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل الفئة الأساسية لعائلات التنسيق التي توفر وظائف مشتركة لمثيلات عائلة التنسيق."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

يمثل الفئة الأساسية لعائلات التنسيق، ويقدم وظائف مشتركة لنسخ عائلة التنسيق.

<br />

*** ** * ** ***

هذه الفئة مجردة ويجب أن يرثها صف مشتق يحدد تفاصيل عائلة التنسيق الفعلية.

<br />


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getId()](#getId--) | يحصل على المعرف الفريد لعائلة التنسيق. |
|
|  | [getName()](#getName--) | يحصل على اسم عائلة الصيغة. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت هذه الحالة مساوية للحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة. |
|
|  | [toString()](#toString--) | يرجع سلسلة تمثل الكائن الحالي. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | يسترجع جميع الحالات من النوع المحدد |
T
التي تُشتق من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة. |
|
|  | [hashCode()](#hashCode--) | يعيد رمز تجزئة للكائن الحالي. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | يسترجع نسخة من النوع المحدد |
T
التي لها المعرف المحدد.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | يسترجع نسخة من النوع المحدد |
T
التي لها الاسم المحدد.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت حالتين من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت حالتين من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | يحدد ما إذا كانت حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) مساوية لاسم سلسلة محدد. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | يحدد ما إذا كانت حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير مساوية لاسم سلسلة محدد. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحوّل حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى عدد صحيح ضمنيًا. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحوّل حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى سلسلة ضمنيًا. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | يحوّل سلسلة تمثل اسم عائلة الصيغة إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | يحوّل عددًا صحيحًا يمثل معرف عائلة الصيغة إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


يحصل على المعرف الفريد لعائلة التنسيق.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم عائلة الصيغة.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


يحدد ما إذا كانت هذه الحالة مساوية للحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | الحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة مع الحالة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة مساوية للحالة الحالية؛ وإلا،  false .

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل الكائن الحالي.


**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي، وهي قيمة الخاصية  Name .

<br />

*** ** * ** ***

تُعيد هذه الطريقة تجاوز object.ToString لإرجاع خاصية  Name  للكائن.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


يسترجع جميع الحالات من النوع المحدد
T
التي تُشتق من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - مجموعة قابلة للتعداد من الحالات من النوع المحدد  T .


T
: نوع عائلة الصيغة.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | الحالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة مع الحالة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة مساوية للحالة الحالية؛ وإلا،  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة للكائن الحالي.


**Returns:**
int - رمز تجزئة للكائن الحالي، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

<br />

*** ** * ** ***

تُعيد هذه الطريقة تجاوز object.GetHashCode. يتم حساب رمز التجزئة باستخدام خصائص  Id  و  Name  للكائن. يتيح السياق  unchecked  تجاوز السعة، وهو مقبول في سياق حساب رمز التجزئة.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


يسترجع نسخة من النوع المحدد
T
التي لها المعرف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | القيمة | int | معرف عائلة الصيغة. |


T
: نوع عائلة الصيغة.
|

**Returns:**
T - حالة من النوع المحدد  T  مع المعرف المحدد.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


يسترجع نسخة من النوع المحدد
T
التي لها الاسم المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | الاسم | java.lang.String | اسم عائلة التنسيق. |


T
: نوع عائلة الصيغة.
|

**Returns:**
T - نسخة من النوع المحدد  T  بالاسم المحدد.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


يحدد ما إذا كانت حالتين من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الأولى من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الثانية من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|

**Returns:**
boolean - true إذا كانت النسختان من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين؛ وإلا false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


يحدد ما إذا كانت حالتين من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الأولى من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الثانية من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|

**Returns:**
boolean - true إذا كانت النسختان من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين؛ وإلا false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


يحدد ما إذا كانت حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) مساوية لاسم سلسلة محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | name | java.lang.String | اسم السلسلة للمقارنة مع نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true إذا كان اسم نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) يساوي اسم السلسلة المحدد؛ وإلا false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


يحدد ما إذا كانت حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير مساوية لاسم سلسلة محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | name | java.lang.String | اسم السلسلة للمقارنة مع نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true إذا كان اسم نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) لا يساوي اسم السلسلة المحدد؛ وإلا false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


يحوّل حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى عدد صحيح ضمنيًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للتحويل. |
|

**Returns:**
int - المعرف الفريد لنسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


يحوّل حالة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى سلسلة ضمنيًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للتحويل. |
|

**Returns:**
java.lang.String - اسم نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


يحوّل سلسلة تمثل اسم عائلة الصيغة إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | عائلة | java.lang.String | اسم عائلة التنسيق للتحويل. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


يحوّل عددًا صحيحًا يمثل معرف عائلة الصيغة إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | معرف | int | معرف عائلة التنسيق للتحويل. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.


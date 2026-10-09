---
title: "FormatFamilyBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل الفئة الأساسية لعائلات الصيغ التي توفر وظائف مشتركة لمثيلات عائلة الصيغ."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

يمثل الفئة الأساسية لعائلات التنسيق، موفرًا وظائف مشتركة لنسخ عائلة التنسيق.

<br />

*** ** * ** ***

هذه الفئة مجردة ويجب أن يرثها صف مشتق يحدد تفاصيل عائلة التنسيق الفعلية.

<br />


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getId()](#getId--) | يحصل على المعرف الفريد لعائلة التنسيق. |
|
|  | [getName()](#getName--) | يحصل على اسم عائلة التنسيق. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة المحددة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [toString()](#toString--) | يرجع سلسلة تمثل الكائن الحالي. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | يسترجع جميع المثيلات من النوع المحدد |
T
التي تُشتق من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة المحددة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [hashCode()](#hashCode--) | يعيد رمز تجزئة (hash code) للكائن الحالي. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | يسترجع مثيلاً من النوع المحدد |
T
التي لها المعرف المحدد.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | يسترجع مثيلاً من النوع المحدد |
T
التي لها الاسم المحدد.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت مثيلتا [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحدد ما إذا كانت مثيلتا [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | يحدد ما إذا كانت مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) مساوية لاسم سلسلة محدد. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | يحدد ما إذا كانت مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير مساوية لاسم سلسلة محدد. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحول مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى عدد صحيح ضمنيًا. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | يحول مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى سلسلة ضمنيًا. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | يحول سلسلة تمثل اسم عائلة تنسيق إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | يحول عددًا صحيحًا يمثل معرف عائلة تنسيق إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
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


يحصل على اسم عائلة التنسيق.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة المحددة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة مع المثيلة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة مساوية للمثيلة الحالية؛ وإلا،  false .

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل الكائن الحالي.


**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي، وهي قيمة خاصية  Name .

<br />

*** ** * ** ***

هذه الطريقة تتجاوز  object.ToString  لإرجاع خاصية  Name  للكائن.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


يسترجع جميع المثيلات من النوع المحدد
T
التي تُشتق من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - مجموعة قابلة للتعداد من المثيلات من النوع المحدد  T .


T
: نوع عائلة التنسيق.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة المحددة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة مع المثيلة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) المحددة مساوية للمثيلة الحالية؛ وإلا،  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة (hash code) للكائن الحالي.


**Returns:**
int - رمز تجزئة للكائن الحالي، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

<br />

*** ** * ** ***

هذه الطريقة تتجاوز  object.GetHashCode . يتم حساب رمز التجزئة باستخدام خاصيتي  Id  و  Name  للكائن. يسمح السياق  unchecked  بحدوث تجاوز، وهو مقبول في سياق حساب رمز التجزئة.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


يسترجع مثيلاً من النوع المحدد
T
التي لها المعرف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | قيمة | int | معرف عائلة التنسيق. |


T
: نوع عائلة التنسيق.
|

**Returns:**
T - نسخة من النوع المحدد  T  مع المعرف المحدد.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


يسترجع مثيلاً من النوع المحدد
T
التي لها الاسم المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | الاسم | java.lang.String | اسم عائلة التنسيق. |


T
: نوع عائلة التنسيق.
|

**Returns:**
T - نسخة من النوع المحدد  T  مع الاسم المحدد.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


يحدد ما إذا كانت مثيلتا [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الأولى من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الثانية من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|

**Returns:**
boolean - صحيح إذا كانت النسختان من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) متساويتين؛ وإلا، خطأ.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


يحدد ما إذا كانت مثيلتا [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الأولى من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | النسخة الثانية من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|

**Returns:**
boolean - صحيح إذا كانت النسختان من [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير متساويتين؛ وإلا، خطأ.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


يحدد ما إذا كانت مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) مساوية لاسم سلسلة محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | name | java.lang.String | اسم السلسلة للمقارنة مع نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - صحيح إذا كان اسم نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) يساوي اسم السلسلة المحدد؛ وإلا، خطأ.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


يحدد ما إذا كانت مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) غير مساوية لاسم سلسلة محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) للمقارنة. |
|
|  | name | java.lang.String | اسم السلسلة للمقارنة مع نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - صحيح إذا كان اسم نسخة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) لا يساوي اسم السلسلة المحدد؛ وإلا، خطأ.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


يحول مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى عدد صحيح ضمنيًا.


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


يحول مثيلة [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) إلى سلسلة ضمنيًا.


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


يحول سلسلة تمثل اسم عائلة تنسيق إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


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


يحول عددًا صحيحًا يمثل معرف عائلة تنسيق إلى كائن [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | معرف | int | معرف عائلة التنسيق للتحويل. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.


---
title: "WorksheetProtection"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يغلف خيارات حماية ورقة العمل التي تسمح بحماية ورقة عمل في مستند Spreadsheet الناتج من تعديل من النوع المحدد باستخدام كلمة مرور محددة."
type: docs
weight: 49
url: /ar/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

يغلف خيارات حماية ورقة العمل، التي تسمح بحماية ورقة عمل
في مستند Spreadsheet الناتج من تعديل من النوع المحدد بـ
كلمة مرور محددة.


*** ** * ** ***

معظم صيغ Spreadsheet مثل XLSX تسمح بحماية ورقة عمل من التحرير باستخدام كلمة مرور. تسمح هذه الفئة بتمكين مثل هذه الحماية وتحديد خياراتها.

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | ينشئ مثيلاً جديدًا باستخدام المعلمات الافتراضية. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | ينشئ مثيلاً جديدًا بنوع حماية ورقة العمل المحدد و |
كلمة المرور
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | يسمح بتحديد نوع حماية ورقة العمل. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | يسمح بتحديد نوع حماية ورقة العمل. |
|
|  | [getPassword()](#getPassword--) | كلمة المرور، التي تُستخدم لحماية ورقة عمل. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | كلمة المرور، التي تُستخدم لحماية ورقة عمل. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


ينشئ مثيلاً جديدًا باستخدام المعلمات الافتراضية. إذا لم يتم تعديلها وتمريرها
إلى SpreadsheetSaveOptions، لن يتم تطبيق أي حماية على ورقة العمل


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


ينشئ مثيلاً جديدًا بنوع حماية ورقة العمل المحدد و
كلمة المرور


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | protectionType | int | نوع حماية ورقة العمل |
|
|  | كلمة المرور | java.lang.String | كلمة المرور، التي تقفل الحماية |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


يسمح بتحديد نوع حماية ورقة العمل. بشكل افتراضي هو 'None' -
لا يتم تطبيق الحماية.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


يسمح بتحديد نوع حماية ورقة العمل. بشكل افتراضي هو 'None' -
لا يتم تطبيق الحماية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة المرور، التي تُستخدم لحماية ورقة عمل. إذا كانت NULL أو فارغة
سلسلة، لن يتم تطبيق الحماية.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


كلمة المرور، التي تُستخدم لحماية ورقة عمل. إذا كانت NULL أو فارغة
سلسلة، لن يتم تطبيق الحماية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |


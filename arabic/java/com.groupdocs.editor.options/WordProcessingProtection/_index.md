---
title: "WordProcessingProtection"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على خيارات حماية المستند لوثيقة WordProcessing التي تم إنشاؤها من HTML"
type: docs
weight: 46
url: /ar/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

يحتوي على خيارات حماية المستند لوثيقة WordProcessing،
التي تم إنشاؤها من HTML

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | منشئ بدون معلمات - جميع المعلمات لها قيم افتراضية |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | يسمح بتعيين جميع المعلمات أثناء إنشاء الفئة |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | يسمح بتعيين نوع الحماية للمستند. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | يسمح بتعيين نوع الحماية للمستند. |
|
|  | [getPassword()](#getPassword--) | كلمة المرور لحماية المستند |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | كلمة المرور لحماية المستند |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


منشئ بدون معلمات - جميع المعلمات لها قيم افتراضية


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


يسمح بتعيين جميع المعلمات أثناء إنشاء الفئة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | protectionType | int | تعيين نوع الحماية للمستند |
|
|  | كلمة المرور | java.lang.String | تعيين كلمة مرور الحماية |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


يسمح بتعيين نوع حماية للمستند. بشكل افتراضي يتم تعيينه إلى عدم
عدم حماية المستند على الإطلاق.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


يسمح بتعيين نوع حماية للمستند. بشكل افتراضي يتم تعيينه إلى عدم
عدم حماية المستند على الإطلاق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة المرور لحماية المستند بـ. إذا كانت null أو سلسلة فارغة - الـ
لن يتم تطبيق الحماية على المستند.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


كلمة المرور لحماية المستند بـ. إذا كانت null أو سلسلة فارغة - الـ
لن يتم تطبيق الحماية على المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int

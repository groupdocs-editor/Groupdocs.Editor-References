---
title: "InvalidFormatException"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الاستثناء الذي يُرمى عندما يحاول المستخدم فتح مستند ما باستخدام خيارات خاصة بالتنسيق غير متوافقة مع تنسيق المستند الأصلي."
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

الاستثناء الذي يُرمى عندما يحاول المستخدم فتح مستند ما باستخدام
خيارات خاصة بالتنسيق غير متوافقة مع تنسيق المستند الأصلي.


*** ** * ** ***

على سبيل المثال، سيتم رمي هذا الاستثناء إذا تم محاولة فتح مستند جدول بيانات باستخدام خيارات مستند معالجة النصوص.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String |  |
| داخلي | java.lang.RuntimeException |  |


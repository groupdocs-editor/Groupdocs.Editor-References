---
title: "InvalidFontFormatException"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الاستثناء الذي يُرمى عند محاولة فتح أو تحميل أو حفظ أو معالجة محتوى ما يُفترض أنه خط بتنسيق معروف مدعوم، لكنه في الواقع خط بتنسيق غير مدعوم أو غير متوقع أو ليس خطًا على الإطلاق."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

الاستثناء الذي يُرمى عند محاولة فتح أو تحميل أو حفظ أو معالجة محتوى ما بطريقة ما، والذي يُفترض أنه خط بتنسيق مدعوم (معروف)، لكنه في الواقع خط بتنسيق غير مدعوم أو غير متوقع أو ليس خطًا على الإطلاق.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | ينشئ مثيلًا جديدًا من مع رسالة خطأ محددة |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | ينشئ مثيلًا جديدًا من @see "InvalidFontFormatException" مع رسالة خطأ محددة وإشارة إلى innerException الذي هو سبب هذا الاستثناء |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


ينشئ مثيلًا جديدًا من مع رسالة خطأ محددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو خالية |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


ينشئ مثيلًا جديدًا من @see "InvalidFontFormatException" مع رسالة خطأ محددة وإشارة إلى innerException الذي هو سبب هذا الاستثناء


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو خالية |
|
|  | innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي، أو إشارة فارغة إذا لم يتم تحديد innerException. |
|


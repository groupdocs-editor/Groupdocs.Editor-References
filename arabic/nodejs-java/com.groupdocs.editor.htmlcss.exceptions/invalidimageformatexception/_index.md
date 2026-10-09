---
title: "InvalidImageFormatException"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الاستثناء الذي يُرمى عند محاولة فتح أو تحميل أو حفظ أو معالجة محتوى ما يُفترض أنه صورة نقطية أو متجهة، لكنه في الواقع صورة من نوع غير متوقع أو ليس صورة على الإطلاق."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

الاستثناء الذي يُرمى عند محاولة فتح أو تحميل أو حفظ أو معالجة
محتوى ما بطريقة ما، يُفترض أنه صورة (نقطية أو متجهة)،
لكن في الواقع هو صورة من نوع غير متوقع أو ليس صورة على الإطلاق.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | ينشئ مثيلًا جديدًا من InvalidImageFormatException مع رسالة خطأ محددة |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | ينشئ مثيلًا جديدًا من InvalidImageFormatException مع رسالة خطأ محددة وإشارة إلى innerException الذي هو سبب هذا الاستثناء |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


ينشئ مثيلًا جديدًا من InvalidImageFormatException مع رسالة خطأ محددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو خالية |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


ينشئ مثيلًا جديدًا من InvalidImageFormatException مع رسالة خطأ محددة وإشارة إلى innerException الذي هو سبب هذا الاستثناء


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو خالية |
|
|  | innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي، أو إشارة فارغة إذا لم يتم تحديد innerException. |
|


---
title: "InvalidImageFormatException"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الاستثناء الذي يُرمى عند محاولة فتح أو تحميل أو حفظ أو معالجة أي محتوى يُفترض أنه صورة نقطية أو متجهة، لكنه في الواقع صورة من نوع غير متوقع أو ليس صورة على الإطلاق."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

الاستثناء الذي يُرمى عند محاولة الفتح أو التحميل أو الحفظ أو المعالجة
أي محتوى آخر يُفترض أنه صورة (نقطية أو متجهة)،
ولكنه في الواقع صورة من نوع غير متوقع أو ليس صورة على الإطلاق.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | ينشئ مثيلاً جديداً من InvalidImageFormatException مع رسالة الخطأ المحددة |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | ينشئ مثيلاً جديداً من InvalidImageFormatException مع رسالة الخطأ المحددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


ينشئ مثيلاً جديداً من InvalidImageFormatException مع رسالة الخطأ المحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو null |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


ينشئ مثيلاً جديداً من InvalidImageFormatException مع رسالة الخطأ المحددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | رسالة | java.lang.String | رسالة نصية تصف الخطأ، يمكن أن تكون فارغة أو null |
|
|  | innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي، أو إشارة null إذا لم يتم تحديد استثناء داخلي. |
|


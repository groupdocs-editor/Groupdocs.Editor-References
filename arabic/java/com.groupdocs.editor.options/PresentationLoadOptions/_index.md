---
title: "PresentationLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحميل المستندات لجميع صيغ العرض المدعومة مثل PPTX و PPTM و PPSX وغيرها."
type: docs
weight: 33
url: /ar/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

يسمح بتحديد خيارات مخصصة لتحميل المستندات لجميع المدعومة
صيغ العرض مثل PPT(X)، PPTM، PPS(X) وغيرها.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند العرض إذا كان مشفّراً.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند العرض إذا كان مشفّراً.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند العرض إذا كان مشفّراً. اضبطه على NULL أو فارغ
سلسلة لإزالة كلمة المرور.


*** ** * ** ***

بشكل افتراضي، تكون قيمة هذه الخاصية NULL \\u2014 أي أن كلمة المرور غير محددة. إذا كان مستند العرض المدخل محميًا بكلمة مرور، تكون كلمة المرور إلزامية وسيتم رمي استثناء إذا لم تُحدد كلمة المرور أو كانت غير صالحة. إذا لم يكن مستند العرض المدخل محميًا بكلمة مرور، ولكن تم تعيين كلمة مرور، فسيتم تجاهلها.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند العرض إذا كان مشفّراً. اضبطه على NULL أو فارغ
سلسلة لإزالة كلمة المرور.


*** ** * ** ***

بشكل افتراضي، تكون قيمة هذه الخاصية NULL \\u2014 أي أن كلمة المرور غير محددة. إذا كان مستند العرض المدخل محميًا بكلمة مرور، تكون كلمة المرور إلزامية وسيتم رمي استثناء إذا لم تُحدد كلمة المرور أو كانت غير صالحة. إذا لم يكن مستند العرض المدخل محميًا بكلمة مرور، ولكن تم تعيين كلمة مرور، فسيتم تجاهلها.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |


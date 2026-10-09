---
title: "PresentationLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحميل المستندات بجميع صيغ Presentation المدعومة مثل PPTX و PPTM و PPSX إلخ"
type: docs
weight: 33
url: /ar/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

يسمح بتحديد خيارات مخصصة لتحميل المستندات من جميع الصيغ المدعومة
صيغ Presentation مثل PPT(X)، PPTM، PPS(X) إلخ.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Presentation إذا كان مشفرًا.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Presentation إذا كان مشفرًا.
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
فتح مستند Presentation إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لإزالة كلمة المرور.


*** ** * ** ***

بشكل افتراضي، هذه الخاصية لها قيمة NULL — كلمة المرور غير محددة. إذا كان مستند Presentation المدخل محميًا بكلمة مرور، تكون كلمة المرور إلزامية وسيتم إلقاء استثناء إذا لم يتم تحديد كلمة المرور أو كانت غير صالحة. إذا كان مستند Presentation المدخل غير محمي بكلمة مرور، ولكن تم تعيين كلمة مرور، فسيتم تجاهلها.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند Presentation إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لإزالة كلمة المرور.


*** ** * ** ***

بشكل افتراضي، هذه الخاصية لها قيمة NULL — كلمة المرور غير محددة. إذا كان مستند Presentation المدخل محميًا بكلمة مرور، تكون كلمة المرور إلزامية وسيتم إلقاء استثناء إذا لم يتم تحديد كلمة المرور أو كانت غير صالحة. إذا كان مستند Presentation المدخل غير محمي بكلمة مرور، ولكن تم تعيين كلمة مرور، فسيتم تجاهلها.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |


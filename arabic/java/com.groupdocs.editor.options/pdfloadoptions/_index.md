---
title: "PdfLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "تحتوي على خيارات لتحميل مستندات PDF إلى فئة Editor"
type: docs
weight: 30
url: /ar/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

تحتوي على خيارات لتحميل مستندات PDF إلى فئة Editor

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفرًا. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفرًا. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفرًا.
اضبطه على NULL أو سلسلة فارغة لعدم استخدام كلمة المرور (القيمة الافتراضية).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفرًا.
اضبطه على NULL أو سلسلة فارغة لعدم استخدام كلمة المرور (القيمة الافتراضية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |


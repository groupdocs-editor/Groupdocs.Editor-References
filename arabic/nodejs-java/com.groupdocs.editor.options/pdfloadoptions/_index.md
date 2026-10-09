---
title: "PdfLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات لتحميل مستندات PDF إلى فئة Editor."
type: docs
weight: 30
url: /ar/nodejs-java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

يحتوي على خيارات لتحميل مستندات PDF إلى فئة Editor.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفراً. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفراً. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفراً.
عيّن إلى NULL أو سلسلة خالية لعدم استخدام كلمة المرور (القيمة الافتراضية).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند PDF إذا كان مشفراً.
عيّن إلى NULL أو سلسلة خالية لعدم استخدام كلمة المرور (القيمة الافتراضية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |


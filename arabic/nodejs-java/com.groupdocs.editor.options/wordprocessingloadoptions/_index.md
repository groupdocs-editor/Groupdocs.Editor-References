---
title: "WordProcessingLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات لتحميل مستندات WordProcessing المتوافقة مع Word مثل DOCX وRTF وODT وغيرها."
type: docs
weight: 45
url: /ar/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

يحتوي على خيارات لتحميل مستندات WordProcessing (متوافقة مع Word) مثل
DOC(X)، RTF، ODT وغيرها إلى فئة Editor

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند WordProcessing إذا كان مشفرًا.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند WordProcessing إذا كان مشفرًا.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند WordProcessing، إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند WordProcessing، إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |


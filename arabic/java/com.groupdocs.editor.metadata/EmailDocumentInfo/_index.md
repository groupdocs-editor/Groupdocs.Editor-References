---
title: "EmailDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات تعريفية لوثيقة بريد إلكتروني واحدة بأي تنسيق بريد إلكتروني مدعوم"
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة بريد إلكتروني واحدة بأي تنسيق بريد إلكتروني مدعوم

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد صيغة لهذا مستند البريد الإلكتروني |
|
|  | [getPageCount()](#getPageCount--) | دائمًا يعيد 1، لأن مستندات البريد الإلكتروني لا تحتوي على عرض صفحات |
|
|  | [getSize()](#getSize--) | يعيد الحجم بالبايت لهذا مستند البريد الإلكتروني |
|
|  | [isEncrypted()](#isEncrypted--) | نظرًا لأن مستندات البريد الإلكتروني لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تعيد 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل EmailDocumentInfo المحدد الآخر |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يعيد صيغة لهذا مستند البريد الإلكتروني


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


دائمًا يعيد 1، لأن مستندات البريد الإلكتروني لا تحتوي على عرض صفحات


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد الحجم بالبايت لهذا مستند البريد الإلكتروني


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


نظرًا لأن مستندات البريد الإلكتروني لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تعيد 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


يحدد ما إذا كان هذا المثيل مساويًا للمثيل EmailDocumentInfo المحدد الآخر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | مثال آخر من EmailDocumentInfo، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


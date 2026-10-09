---
title: "EbookDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل بيانات تعريفية لوثيقة EBook واحدة"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة EBook واحدة

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد تنسيقًا لهذا المستند |
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub. |
|
|  | [getSize()](#getSize--) | يعيد حجم هذا المستند الإلكتروني بالبايتات |
|
|  | [isEncrypted()](#isEncrypted--) | نظرًا لأن المستندات الإلكترونية لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة الأخرى المحددة من EbookDocumentInfo |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يعيد تنسيقًا لهذا المستند


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يعيد عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub.

<br />

*** ** * ** ***

عادةً لا تحتوي المستندات الإلكترونية على صفحات ثابتة وبالتالي لا يوجد عدد صفحات. في حالة ePub يمكن حساب عدد الفصول. ومع ذلك، لا تحتوي صيغتي MOBI و AZW3 على فصول أيضًا، لذا يتم حساب هذا العدد بناءً على حجم الصفحة القياسي المحدد إلى A4 في الوضع العمودي.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد حجم هذا المستند الإلكتروني بالبايتات


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


نظرًا لأن المستندات الإلكترونية لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


يحدد ما إذا كانت هذه النسخة مساوية للنسخة الأخرى المحددة من EbookDocumentInfo


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | نسخة أخرى من EbookDocumentInfo يجب فحص مساواتها مع هذه النسخة |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


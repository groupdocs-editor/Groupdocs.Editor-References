---
title: "EbookDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات تعريفية لوثيقة كتاب إلكتروني واحدة"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة كتاب إلكتروني واحدة

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد صيغة هذه الوثيقة |
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub. |
|
|  | [getSize()](#getSize--) | يعيد حجم هذا المستند الإلكتروني بالبايت |
|
|  | [isEncrypted()](#isEncrypted--) | نظرًا لأن المستندات الإلكترونية لا يمكن تشفيرها بكلمة مرور، فإن هذه الخاصية دائمًا تُعيد 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | يحدد ما إذا كانت هذه الحالة مساوية للحالة الأخرى المحددة من نوع EbookDocumentInfo |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يعيد صيغة هذه الوثيقة


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يعيد عدد الصفحات في حالة MOBI أو AZW3 أو عدد الفصول في حالة ePub.

<br />

*** ** * ** ***

عادةً لا تحتوي المستندات الإلكترونية على صفحات ثابتة وبالتالي لا يوجد عدد صفحات. في حالة ePub يمكن حساب عدد الفصول. ومع ذلك، لا تحتوي صيغتي MOBI و AZW3 على فصول أيضًا، لذا يتم حساب هذا العدد بناءً على حجم الصفحة القياسي المحدد إلى A4 في وضعية portrait.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد حجم هذا المستند الإلكتروني بالبايت


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


يحدد ما إذا كانت هذه الحالة مساوية للحالة الأخرى المحددة من نوع EbookDocumentInfo


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | مثيل آخر من EbookDocumentInfo يجب فحص مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


---
title: "FixedLayoutDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل بيانات تعريفية لوثيقة واحدة ذات تنسيق تخطيط ثابت مثل PDF أو XPS"
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة واحدة ذات تنسيق تخطيط ثابت مثل PDF أو XPS

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد تنسيق هذا المستند fixed-layout |
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد الصفحات |
|
|  | [getSize()](#getSize--) | يعيد الحجم بالبايت لهذا المستند fixed-layout |
|
|  | [isEncrypted()](#isEncrypted--) | يحدد ما إذا كان هذا المستند fixed-layout المحدد مشفرًا ويتطلب كلمة مرور للفتح |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | يحدد ما إذا كان هذا المثال مساويًا للمثال FixedLayoutDocumentInfo المحدد الآخر |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يعيد تنسيق هذا المستند fixed-layout


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يعيد عدد الصفحات


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد الحجم بالبايت لهذا المستند fixed-layout


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


يحدد ما إذا كان هذا المستند fixed-layout المحدد مشفرًا ويتطلب كلمة مرور للفتح


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


يحدد ما إذا كان هذا المثال مساويًا للمثال FixedLayoutDocumentInfo المحدد الآخر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | مثال آخر من FixedLayoutDocumentInfo، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


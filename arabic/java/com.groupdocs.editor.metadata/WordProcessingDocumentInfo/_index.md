---
title: "WordProcessingDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات تعريفية لوثيقة معالجة كلمات واحدة"
type: docs
weight: 17
url: /ar/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة معالجة كلمات واحدة

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد صيغة لهذا مستند WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد الصفحات |
|
|  | [getSize()](#getSize--) | يعيد الحجم بالبايت لهذا مستند WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | يحدد ما إذا كان هذا المستند WordProcessing المحدد مشفرًا و |
يتطلب كلمة مرور للفتح
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | ينشئ ويعيد معاينة للصفحة المحددة على شكل صورة SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد |
مثيل WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


يعيد صيغة لهذا مستند WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
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


يعيد الحجم بالبايت لهذا مستند WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


يحدد ما إذا كان هذا المستند WordProcessing المحدد مشفرًا و
يتطلب كلمة مرور للفتح


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


ينشئ ويعيد معاينة للصفحة المحددة على شكل صورة SVG


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageIndex | int | فهرس يبدأ من 0 للصفحة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد الصفحات في هذا المستند WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد
مثيل WordProcessingDocumentInfo


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | مثيل WordProcessingDocumentInfo آخر، يجب فحصه للمساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


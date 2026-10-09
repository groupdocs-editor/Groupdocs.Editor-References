---
title: "PresentationDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل بيانات تعريفية لوثيقة عرض تقديمي واحدة"
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة عرض تقديمي واحدة

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يُرجع تنسيق هذا المستند Presentation |
|
|  | [getPageCount()](#getPageCount--) | يُرجع عدد الشرائح في هذا المستند Presentation |
|
|  | [getSize()](#getSize--) | يُرجع الحجم بالبايت لهذا المستند Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | يشير إلى ما إذا كان مستند Presentation المحدد مشفراً ويتطلب كلمة مرور للفتح |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | ينشئ ويعيد معاينة للشريحة المحددة على شكل صورة SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


يُرجع تنسيق هذا المستند Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يُرجع عدد الشرائح في هذا المستند Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يُرجع الحجم بالبايت لهذا المستند Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


يشير إلى ما إذا كان مستند Presentation المحدد مشفراً ويتطلب كلمة مرور للفتح


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


ينشئ ويعيد معاينة للشريحة المحددة على شكل صورة SVG


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | slideIndex | int | فهرس يبدأ من 0 للشفرة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد الشرائح في هذا العرض التقديمي. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class


---
title: "SpreadsheetDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات تعريفية لوثيقة جدول بيانات واحدة"
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة جدول بيانات واحدة

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد صيغة هذه وثيقة Spreadsheet |
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد علامات التبويب |
|
|  | [getSize()](#getSize--) | يعيد الحجم بالبايت لهذه وثيقة Spreadsheet |
|
|  | [isEncrypted()](#isEncrypted--) | يشير إلى ما إذا كانت هذه الوثيقة Spreadsheet محددة مشفرة و |
يتطلب كلمة مرور للفتح
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | ينشئ ويعيد معاينة للورقة المختارة في شكل صورة SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد |
مثال SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


يعيد صيغة هذه وثيقة Spreadsheet


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يعيد عدد علامات التبويب


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد الحجم بالبايت لهذه وثيقة Spreadsheet


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


يشير إلى ما إذا كانت هذه الوثيقة Spreadsheet محددة مشفرة و
يتطلب كلمة مرور للفتح


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


ينشئ ويعيد معاينة للورقة المختارة في شكل صورة SVG


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | worksheetIndex | int | فهرس يبدأ من 0 للورقة المطلوبة. لا يمكن أن يكون أقل من 0، ولا يمكن أن يتجاوز عدد الأوراق في هذه الـ spreadsheet. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد
مثال SpreadsheetDocumentInfo


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | مثال آخر من SpreadsheetDocumentInfo، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


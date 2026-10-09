---
title: "MarkdownDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل بيانات تعريفية لوثيقة Markdown واحدة"
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة Markdown واحدة

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يعيد تنسيق هذا المستند Markdown \\u2014 دائمًا هو |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | يعيد عدد الصفحات. |
|
|  | [getSize()](#getSize--) | يعيد حجم هذا المستند Markdown بالبايتات |
|
|  | [isEncrypted()](#isEncrypted--) | نظرًا لأن مستندات Markdown لا يمكن تشفيرها بكلمة مرور، فإن هذا |
الخاصية دائمًا ما تعيد 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يعيد تنسيق هذا المستند Markdown \\u2014 دائمًا هو
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يعيد عدد الصفحات. عادةً لا تحتوي مستندات Markdown على صفحات ثابتة
وبالتالي عدد الصفحات، لذا يتم حساب هذا الرقم بناءً على حجم الصفحة القياسي
محدد إلى A4 في وضعية عمودية.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد حجم هذا المستند Markdown بالبايتات


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


نظرًا لأن مستندات Markdown لا يمكن تشفيرها بكلمة مرور، فإن هذا
الخاصية دائمًا ما تعيد 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | كائن آخر [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) يجب فحصه للمساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


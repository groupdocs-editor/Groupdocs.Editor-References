---
title: "MarkdownDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات تعريفية لوثيقة ماركداون واحدة"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

يمثل بيانات تعريفية لوثيقة ماركداون واحدة

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يرجع تنسيق هذا المستند Markdown \u2014 دائمًا هو |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | يرجع عدد الصفحات. |
|
|  | [getSize()](#getSize--) | يرجع الحجم بالبايت لهذا المستند Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | نظرًا لأنه لا يمكن تشفير مستندات Markdown باستخدام كلمة مرور، فإن هذا |
الخاصية دائمًا ما تُرجع 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | يحدد ما إذا كانت هذه الحالة مساوية للآخر المحدد |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


يرجع تنسيق هذا المستند Markdown \u2014 دائمًا هو
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


يرجع عدد الصفحات. عادةً لا تحتوي مستندات Markdown على صفحات ثابتة
وبالتالي عدد الصفحات، لذا يتم حساب هذا الرقم من حجم الصفحة القياسي
مضبوطة على A4 في وضعية العمودي.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يرجع الحجم بالبايت لهذا المستند Markdown


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


نظرًا لأنه لا يمكن تشفير مستندات Markdown باستخدام كلمة مرور، فإن هذا
الخاصية دائمًا ما تُرجع 'false'


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
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | مثال آخر لـ [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo)، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين


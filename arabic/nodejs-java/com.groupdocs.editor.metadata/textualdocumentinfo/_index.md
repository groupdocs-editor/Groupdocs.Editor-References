---
title: "TextualDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل بيانات التعريف لوثيقة نصية واحدة مثل XML أو HTML أو نص عادي TXT"
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

يمثل بيانات التعريف لوثيقة نصية واحدة مثل XML أو HTML أو نص عادي
(TXT)

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormat()](#getFormat--) | يُرجع تنسيق هذه الوثيقة النصية. |
|
|  | [getPageCount()](#getPageCount--) | دائمًا يُرجع 1 |
|
|  | [getSize()](#getSize--) | يُرجع الحجم بالبايت (ليس عدد الأحرف) لهذه النصية |
وثيقة
|
|  | [isEncrypted()](#isEncrypted--) | دائمًا يُرجع 'false'، لأن الوثائق النصية لا يمكن تشفيرها. |
|
|  | [getEncoding()](#getEncoding--) | يُرجع الترميز المكتشف المفترض للوثيقة النصية |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


يُرجع تنسيق هذه الوثيقة النصية. قد لا يكون صحيحًا بنسبة 100% في
بعض الحالات.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


دائمًا يُرجع 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يُرجع الحجم بالبايت (ليس عدد الأحرف) لهذه النصية
وثيقة


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


دائمًا يُرجع 'false'، لأن الوثائق النصية لا يمكن تشفيرها.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يُرجع الترميز المكتشف المفترض للوثيقة النصية


**Returns:**
java.nio.charset.Charset

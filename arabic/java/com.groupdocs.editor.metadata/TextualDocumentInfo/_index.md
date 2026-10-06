---
title: "TextualDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل بيانات التعريف لوثيقة نصية واحدة مثل XML وHTML أو نص عادي TXT"
type: docs
weight: 16
url: /ar/java/com.groupdocs.editor.metadata/textualdocumentinfo/
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
|  | [getFormat()](#getFormat--) | يعيد صيغة هذه الوثيقة النصية. |
|
|  | [getPageCount()](#getPageCount--) | دائمًا ما يعيد 1 |
|
|  | [getSize()](#getSize--) | يعيد الحجم بالبايت (ليس عدد الأحرف) لهذه النصية |
وثيقة
|
|  | [isEncrypted()](#isEncrypted--) | دائمًا ما يعيد 'false'، لأن الوثائق النصية لا يمكن تشفيرها. |
|
|  | [getEncoding()](#getEncoding--) | يعيد الترميز المفترض المكتشف للوثيقة النصية |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


يعيد صيغة هذه الوثيقة النصية. قد لا تكون صحيحة بنسبة 100% في
بعض الحالات.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


دائمًا ما يعيد 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


يعيد الحجم بالبايت (ليس عدد الأحرف) لهذه النصية
وثيقة


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


دائمًا ما يعيد 'false'، لأن الوثائق النصية لا يمكن تشفيرها.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يعيد الترميز المفترض المكتشف للوثيقة النصية


**Returns:**
java.nio.charset.Charset

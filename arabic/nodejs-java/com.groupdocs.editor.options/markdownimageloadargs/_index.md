---
title: "MarkdownImageLoadArgs"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يوفر البيانات لحدث MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /ar/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

يوفر البيانات ل

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

حدث.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | يحصل أو يعيّن اسم الملف (كما هو في مستند Markdown) الذي سيكون |
معالجة.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | يحصل أو يعيّن اسم الملف (كما هو في مستند Markdown) الذي سيكون |
معالجة.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | احصل على قيمة تشير إلى ما إذا كانت هذه الصورة لها رابط URI مطلق. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | احصل على قيمة تشير إلى ما إذا كانت هذه الصورة لها رابط URI مطلق. |
|
|  | [setData(byte[] data)](#setData-byte---) | يضبط البيانات التي قدمها المستخدم للمورد والتي تُستخدم إذا |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


يحصل أو يعيّن اسم الملف (كما هو في مستند Markdown) الذي سيكون
معالجة.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


يحصل أو يعيّن اسم الملف (كما هو في مستند Markdown) الذي سيكون
معالجة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


احصل على قيمة تشير إلى ما إذا كانت هذه الصورة لها رابط URI مطلق.
القيمة: true إذا كانت هذه الصورة لها رابط URI مطلق؛ وإلا false.


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


احصل على قيمة تشير إلى ما إذا كانت هذه الصورة لها رابط URI مطلق.
القيمة: true إذا كانت هذه الصورة لها رابط URI مطلق؛ وإلا false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


يضبط البيانات التي قدمها المستخدم للمورد والتي تُستخدم إذا

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] |  |


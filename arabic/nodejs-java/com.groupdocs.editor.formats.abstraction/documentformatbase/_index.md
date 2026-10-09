---
title: "DocumentFormatBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل الفئة الأساسية لتنسيقات المستندات التي توفر وظائف مشتركة لنسخ التنسيق"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

يمثل الفئة الأساسية لتنسيقات المستندات، موفرًا وظائف مشتركة لنسخ التنسيق.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMime()](#getMime--) | يحصل على نوع MIME لتنسيق المستند. |
|
|  | [getExtension()](#getExtension--) | يحصل على امتداد الملف لتنسيق المستند. |
|
|  | [getFormatFamily()](#getFormatFamily--) | يحصل على عائلة الصيغة التي ينتمي إليها تنسيق المستند. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | يسترجع مثيلاً من النوع المحدد |
T
الذي لديه نوع MIME المحدد.
|
|  | [hashCode()](#hashCode--) | يعيد رمز تجزئة (hash code) للكائن الحالي. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) المحددة. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) المحددة. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | يحوّل مثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) إلى سلسلة نصية ضمنيًا. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


يحصل على نوع MIME لتنسيق المستند.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


يحصل على امتداد الملف لتنسيق المستند.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


يحصل على عائلة الصيغة التي ينتمي إليها تنسيق المستند.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


يسترجع مثيلاً من النوع المحدد
T
الذي لديه نوع MIME المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | نوع MIME لتنسيق المستند. |


T
: نوع تنسيق المستند.
|

**Returns:**
T - مثيل من النوع المحدد T مع نوع MIME المحدد.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة (hash code) للكائن الحالي.


**Returns:**
int - رمز تجزئة للكائن الحالي، يجمع رموز التجزئة للكائن الأساسي، ونوع MIME، وامتداد الملف، وعائلة الصيغة.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | مثيلة [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) للمقارنة مع المثيلة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) المحددة مساوية للمثيلة الحالية؛ وإلا،  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه المثيلة مساوية للمثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) للمقارنة مع المثيلة الحالية. |
|

**Returns:**
boolean -  true  إذا كانت [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) المحددة مساوية للمثيلة الحالية؛ وإلا،  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


يحوّل مثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) إلى سلسلة نصية ضمنيًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | مثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) للتحويل. |
|

**Returns:**
java.lang.String - امتداد الملف لمثيلة [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).


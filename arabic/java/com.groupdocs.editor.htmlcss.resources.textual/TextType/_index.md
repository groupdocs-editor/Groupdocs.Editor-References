---
title: "TextType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل نوعًا واحدًا من الموارد النصية القابلة للدعم"
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

يمثل نوعًا واحدًا من الموارد النصية القابلة للدعم

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextType()](#TextType--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | قيمة خاصة، تُشير إلى نص غير معرف أو غير معروف أو غير مدعوم |
المورد
|
|  | [getCss()](#getCss--) | نوع CSS لمورد النص |
|
|  | [getXml()](#getXml--) | نوع XML لمورد النص |
|
|  | [getFormalName()](#getFormalName--) | يرجع اسمًا رسميًا لهذا النوع من موارد النص |
|
|  | [getFileExtension()](#getFileExtension--) | امتداد الملف (بدون نقطة البداية) لنص معين |
المورد
|
|  | [getMimeCode()](#getMimeCode--) | رمز MIME لنوع مورد نص معين |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كانت هذه الحالة مساوية لـ "TextType" المحدد |
مثيل
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد، |
والذي من المفترض أنه مثيل "TextType" آخر
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كان مثليا "TextType" المحددين متساويين |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كان مثليا "TextType" المحددين غير متساويين |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة |
نوع
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | يرجع قيمة TextType، وهي ما يعادل امتداد اسم الملف، المستخرج من اسم ملف محدد مع الامتداد أو من امتداد بحد ذاته |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


قيمة خاصة، تُشير إلى نص غير معرف أو غير معروف أو غير مدعوم
المورد


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


نوع CSS لمورد النص


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


نوع XML لمورد النص


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


يرجع اسمًا رسميًا لهذا النوع من موارد النص


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


امتداد الملف (بدون نقطة البداية) لنص معين
المورد


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


رمز MIME لنوع مورد نص معين


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


يحدد ما إذا كانت هذه الحالة مساوية لـ "TextType" المحدد
مثيل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | مثيل TextType آخر يجب مقارنته بهذا في المساواة |
|

**Returns:**
منطقي - يرجع true إذا كانا متساويين أو false إذا كانا غير متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد،
والذي من المفترض أنه مثيل "TextType" آخر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيل TextType آخر، يتم تغليفه إلى كائن |
|

**Returns:**
منطقي - يرجع true إذا كانا متساويين أو false إذا كانا غير متساويين

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


يحدد ما إذا كان مثليا "TextType" المحددين متساويين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | مثيل TextType الأول |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | مثيل TextType الثاني |
|

**Returns:**
منطقي - يرجع true إذا كانا متساويين أو false إذا كانا غير متساويين

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


يحدد ما إذا كان مثليا "TextType" المحددين غير متساويين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | مثيل TextType الأول |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | مثيل TextType الثاني |
|

**Returns:**
منطقي - يرجع true إذا كانا غير متساويين أو false إذا كانا متساويين

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة
نوع


**Returns:**
int - عدد صحيح موقع 4 بايت. يرجع 0 إذا كانت هذه الحالة لها القيمة الافتراضية.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


يرجع قيمة TextType، وهي ما يعادل امتداد اسم الملف، المستخرج من اسم ملف محدد مع الامتداد أو من امتداد بحد ذاته


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم ملف مع الامتداد، يمكن أن يكون مسارًا نسبيًا أو مطلقًا، أو الامتداد نفسه |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure


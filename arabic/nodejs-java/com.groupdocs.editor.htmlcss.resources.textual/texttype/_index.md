---
title: "TextType"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل نوعًا واحدًا من الموارد النصية القابلة للدعم"
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
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

| المنشئ | الوصف |
| --- | --- |
| [TextType()](#TextType--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | قيمة خاصة، تُشير إلى نص غير معرف أو غير معروف أو غير مدعوم |
مورد
|
|  | [getCss()](#getCss--) | نوع CSS للمورد النصي |
|
|  | [getXml()](#getXml--) | نوع XML للمورد النصي |
|
|  | [getFormalName()](#getFormalName--) | يرجع الاسم الرسمي لهذا النوع من المورد النصي |
|
|  | [getFileExtension()](#getFileExtension--) | امتداد الملف (بدون حرف النقطة في البداية) لنص معين |
مورد
|
|  | [getMimeCode()](#getMimeCode--) | رمز MIME لنوع مورد نصي معين. |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كانت هذه الحالة مساوية للـ "TextType" المحدد |
حالة
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، |
الذي من المفترض أنه حالة "TextType" أخرى
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كانت حالتين محددتين من "TextType" متساويتين |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | يحدد ما إذا كانت حالتين محددتين من "TextType" غير متساويتين |
|
|  | [hashCode()](#hashCode--) | يعيد رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة |
نوع
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | يعيد قيمة TextType، وهي ما يعادل امتداد اسم الملف، المستخرج من اسم الملف المحدد مع الامتداد أو الامتداد النقي |
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
مورد


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


نوع CSS للمورد النصي


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


نوع XML للمورد النصي


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


يرجع الاسم الرسمي لهذا النوع من المورد النصي


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


امتداد الملف (بدون حرف النقطة في البداية) لنص معين
مورد


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


رمز MIME لنوع مورد نصي معين.


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


يحدد ما إذا كانت هذه الحالة مساوية للـ "TextType" المحدد
حالة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | حالة TextType أخرى، يجب مقارنتها بهذه الحالة من حيث المساواة |
|

**Returns:**
منطقي - يعيد true إذا كانا متساويين أو false إذا كانا غير متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد،
الذي من المفترض أنه حالة "TextType" أخرى


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | حالة TextType أخرى، تم تغليفها إلى كائن |
|

**Returns:**
منطقي - يعيد true إذا كانا متساويين أو false إذا كانا غير متساويين

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


يحدد ما إذا كانت حالتين محددتين من "TextType" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | الحالة الأولى من TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | الحالة الثانية من TextType |
|

**Returns:**
منطقي - يعيد true إذا كانا متساويين أو false إذا كانا غير متساويين

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


يحدد ما إذا كانت حالتين محددتين من "TextType" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | الحالة الأولى من TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | الحالة الثانية من TextType |
|

**Returns:**
منطقي - يعيد true إذا كانا غير متساويين أو false إذا كانا متساويين

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة
نوع


**Returns:**
int - عدد صحيح موقع بحجم 4 بايت. يعيد 0 إذا كانت هذه الحالة لها القيمة الافتراضية.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


يعيد قيمة TextType، وهي ما يعادل امتداد اسم الملف، المستخرج من اسم الملف المحدد مع الامتداد أو الامتداد النقي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم الملف مع الامتداد، يمكن أن يكون مسارًا نسبيًا أو مطلقًا، أو الامتداد النقي نفسه |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure


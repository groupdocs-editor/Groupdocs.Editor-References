---
title: "FontType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل نوع خط قابل للدعم."
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

يمثل نوع خط قابل للدعم.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontType()](#FontType--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | قيمة خاصة، تُشير إلى خط غير معرف أو غير معروف أو غير مدعوم |
المورد
|
|  | [getWoff()](#getWoff--) | يمثل نوع خط WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | يمثل نوع خط WOFF2 (Web Open Font Format الإصدار 2) |
|
|  | [getTtf()](#getTtf--) | يمثل نوع خط TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | يمثل نوع خط OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | يمثل خط مجموعة TrueType (TTC) |
|
|  | [getEot()](#getEot--) | يمثل نوع خط EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | يعيد اسمًا متوافقًا مع CSS لهذا النوع من الخطوط، والذي يُستخدم في |
|
|  | [getFormalName()](#getFormalName--) | يعيد اسمًا رسميًا لهذا النوع من الخطوط |
|
|  | [getFileExtension()](#getFileExtension--) | امتداد اسم الملف (بدون علامة النقطة) لهذا النوع من الخطوط |
|
|  | [getFontFormat()](#getFontFormat--) | تنسيق الخط لتنسيق @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | رمز MIME لنوع خط معين |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | يعيد قيمة FontType، والتي تعادل CSS-compatible المحدد |
اسم نوع الخط
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | يعيد قيمة FontType، والتي تعادل امتداد اسم الملف، والذي |
يتم استخراجها من اسم الملف المحدد
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | يعيد قيمة FontType، والتي تعادل MIME-code المحدد |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | يعيد أول نوع خط من المجموعة المحددة، والذي ليس "Undefined" |
قيمة، أو نوع الخط "Undefined" خلاف ذلك (عندما تكون جميع العناصر
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | يحدد ما إذا كانت هذه العينة مساوية لـ "FontType" المحدد |
مثيل
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد، |
والتي من المفترض أنها عينة "FontType" أخرى
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | يفحص ما إذا كانت قيمتي "FontType" متساويتين |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | يفحص ما إذا كانت قيمتي "FontType" غير متساويتين |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة |
نوع
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


قيمة خاصة، تُشير إلى خط غير معرف أو غير معروف أو غير مدعوم
المورد


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


يمثل نوع خط WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


يمثل نوع خط WOFF2 (Web Open Font Format الإصدار 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


يمثل نوع خط TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


يمثل نوع خط OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


يمثل خط مجموعة TrueType (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


يمثل نوع خط EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


يعيد اسمًا متوافقًا مع CSS لهذا النوع من الخطوط، والذي يُستخدم في


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


يعيد اسمًا رسميًا لهذا النوع من الخطوط


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


امتداد اسم الملف (بدون علامة النقطة) لهذا النوع من الخطوط


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


تنسيق الخط لتنسيق @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


رمز MIME لنوع خط معين


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


يعيد قيمة FontType، والتي تعادل CSS-compatible المحدد
اسم نوع الخط


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم متوافق مع CSS لنوع الخط |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


يعيد قيمة FontType، والتي تعادل امتداد اسم الملف، والذي
يتم استخراجها من اسم الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم الملف مع الامتداد، قد يكون اسمًا كاملاً |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


يعيد قيمة FontType، والتي تعادل MIME-code المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | mimeCode | java.lang.String | رمز MIME |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


يعيد أول نوع خط من المجموعة المحددة، والذي ليس "Undefined"
قيمة، أو نوع الخط "Undefined" خلاف ذلك (عندما تكون جميع العناصر
"Undefined")


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | قيمة أو أكثر من FontType، لا يُسمح بـ NULL أو مجموعة فارغة |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


يحدد ما إذا كانت هذه العينة مساوية لـ "FontType" المحدد
مثيل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | عينة FontType أخرى للتحقق معها |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد،
والتي من المفترض أنها عينة "FontType" أخرى


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | عينة أخرى من المفترض أنها بنية FontType، تم تغليفها إلى System.Object |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


يفحص ما إذا كانت قيمتي "FontType" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | أول FontType للتحقق |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | ثاني FontType للتحقق |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


يفحص ما إذا كانت قيمتي "FontType" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | أول FontType للتحقق |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | ثاني FontType للتحقق |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة، وهو رقم ثابت لهذه القيمة المحددة
نوع


**Returns:**
int - عدد صحيح موقع 4 بايت، 0 للقيمة Undefined


---
title: "AudioType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل تنسيق نوع صوتي مدعوم واحد"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

يمثل نوعًا صوتيًا مدعومًا واحدًا (تنسيق).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | الاسم الرسمي لهذا التنسيق الصوتي |
|
|  | [getFileExtension()](#getFileExtension--) | امتداد اسم الملف (بدون علامة النقطة) لهذا التنسيق الصوتي |
|
|  | [getMimeCode()](#getMimeCode--) | رمز MIME لهذا التنسيق الصوتي |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | يحدد ما إذا كان هذا الكائن مساويًا للنسخة المحددة من "AudioType" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا الكائن مساويًا للعنصر غير المحول المحدد، والذي من المفترض أنه نسخة أخرى من "AudioType" |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | يفحص ما إذا كانت قيمتي "AudioType" متساويتين |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | يتحقق مما إذا كانت قيمتي "AudioType" غير متساويتين |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة، وهو رقم ثابت لهذا النوع القيمي المحدد |
|
|  | [getUndefined()](#getUndefined--) | قيمة خاصة، تُشير إلى تنسيق صوت غير معرف أو غير معروف أو غير مدعوم |
|
|  | [getMp3()](#getMp3--) | يمثل تنسيق صوت MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | يرجع قيمة AudioType، التي تعادل امتداد اسم الملف المستخرج من اسم الملف المحدد |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


الاسم الرسمي لهذا التنسيق الصوتي


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


امتداد اسم الملف (بدون علامة النقطة) لهذا التنسيق الصوتي


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


رمز MIME لهذا التنسيق الصوتي


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


يحدد ما إذا كان هذا الكائن مساويًا للنسخة المحددة من "AudioType"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | مثيل AudioType آخر للتحقق معه |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا الكائن مساويًا للعنصر غير المحول المحدد، والذي من المفترض أنه نسخة أخرى من "AudioType"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيل آخر يُفترض أنه من بنية AudioType، تم تغليفه إلى System.Object |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


يفحص ما إذا كانت قيمتي "AudioType" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType الأول للتحقق منه |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType الثاني للتحقق منه |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


يتحقق مما إذا كانت قيمتي "AudioType" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType الأول للتحقق منه |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | AudioType الثاني للتحقق منه |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة، وهو رقم ثابت لهذا النوع القيمي المحدد


**Returns:**
int - عدد صحيح موقع 4 بايت، 0 للقيمة Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


قيمة خاصة، تُشير إلى تنسيق صوت غير معرف أو غير معروف أو غير مدعوم


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


يمثل تنسيق صوت MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


يرجع قيمة AudioType، التي تعادل امتداد اسم الملف المستخرج من اسم الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم ملف عشوائي، يمكن أن يكون مسارًا نسبيًا أو مسارًا كاملًا |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.


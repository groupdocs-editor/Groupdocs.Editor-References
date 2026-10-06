---
title: "TextDirection"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل 3 متغيرات ممكنة لكيفية معالجة اتجاه النص في المستندات النصية العادية."
type: docs
weight: 38
url: /ar/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

يمثل 3 متغيرات ممكنة لكيفية معالجة اتجاه النص في النص العادي.
المستندات

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | اتجاه من اليسار إلى اليمين، نص عادي، القيمة الافتراضية. |
|
|  | [RightToLeft](#RightToLeft) | اتجاه من اليمين إلى اليسار |
|
|  | [Auto](#Auto) | اكتشاف الاتجاه تلقائيًا. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


اتجاه من اليسار إلى اليمين، نص عادي، القيمة الافتراضية.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


اتجاه من اليمين إلى اليسار


### Auto {#Auto}
```
public static final int Auto
```


اكتشاف الاتجاه تلقائيًا. عندما يتم اختيار هذا الخيار ويحتوي النص على
حروف تنتمي إلى سكريبتات RTL، سيتم تعيين اتجاه المستند
تلقائيًا إلى RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]

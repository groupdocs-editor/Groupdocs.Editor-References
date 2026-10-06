---
title: "PresentationEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع تنسيقات العروض التقديمية المتوافقة مع PowerPoint المدعومة"
type: docs
weight: 32
url: /ar/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة
تنسيقات العروض التقديمية (متوافقة مع PowerPoint)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان يجب تضمين الشرائح المخفية أم لا. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان يجب تضمين الشرائح المخفية أم لا. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير


*** ** * ** ***

رقم الشريحة هو فهرس يبدأ من الصفر يتيح تحديد واختيار شريحة معينة من العرض التقديمي للتحرير. إذا كان أقل من 0، سيتم اختيار الشريحة الأولى (نفس قيمة SlideNumber = 0). إذا كان أكبر من عدد جميع الشرائح في العرض التقديمي، سيتم اختيار الشريحة الأخيرة. إذا كان العرض التقديمي يحتوي على شريحة واحدة فقط، سيتم تجاهل هذا الخيار وسيتم تحرير تلك الشريحة الوحيدة. إذا تم محاولة فتح شريحة مخفية للتحرير بينما يكون خيار ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) مضبوطًا على 'false'، سيتم رمي الاستثناء.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير


*** ** * ** ***

رقم الشريحة هو فهرس يبدأ من الصفر يتيح تحديد واختيار شريحة معينة من العرض التقديمي للتحرير. إذا كان أقل من 0، سيتم اختيار الشريحة الأولى (نفس قيمة SlideNumber = 0). إذا كان أكبر من عدد جميع الشرائح في العرض التقديمي، سيتم اختيار الشريحة الأخيرة. إذا كان العرض التقديمي يحتوي على شريحة واحدة فقط، سيتم تجاهل هذا الخيار وسيتم تحرير تلك الشريحة الوحيدة. إذا تم محاولة فتح شريحة مخفية للتحرير بينما يكون خيار ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) مضبوطًا على 'false'، سيتم رمي الاستثناء.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


يحدد ما إذا كان يجب تضمين الشرائح المخفية أم لا. القيمة الافتراضية هي
false - لا تُظهر الشرائح المخفية وسيتم رمي الاستثناء أثناء
محاولة تحريرها.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


يحدد ما إذا كان يجب تضمين الشرائح المخفية أم لا. القيمة الافتراضية هي
false - لا تُظهر الشرائح المخفية وسيتم رمي الاستثناء أثناء
محاولة تحريرها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |


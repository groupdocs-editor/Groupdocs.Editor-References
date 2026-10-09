---
title: "PresentationSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Presentation المتوافقة مع PowerPoint"
type: docs
weight: 34
url: /ar/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ Presentation
(متوافقة مع PowerPoint) مستندات

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من PresentationSaveOptions بصيغة إخراج PPTX (يمكن تعديلها لاحقًا عبر |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) خاصية)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | ينشئ نسخة جديدة من PresentationSaveOptions مع المحدد |
صيغة إخراج Presentation إلزامية، بينما جميع المعلمات الأخرى هي
افتراضي
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
تشفير مستند Presentation الناتج.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لتشفير مستند Presentation الناتج. |
|
|  | [getSlideNumber()](#getSlideNumber--) | يسمح بإدراج الشريحة المعدلة في عرض تقديمي موجود بدلاً من إنشاء عرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | يسمح بإدراج الشريحة المعدلة في عرض تقديمي موجود بدلاً من إنشاء عرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | علامة منطقية تحدد ما إذا كانت الشريحة المعدلة يجب أن تستبدل الشريحة الموجودة في العرض التقديمي الأصلي في الموضع المحدد بواسطة |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) خاصية، أو يجب إدراجها بين الشريحة الموجودة والسابقة، دون استبدال محتواها.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | علامة منطقية تحدد ما إذا كانت الشريحة المعدلة يجب أن تستبدل الشريحة الموجودة في العرض التقديمي الأصلي في الموضع المحدد بواسطة |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) خاصية، أو يجب إدراجها بين الشريحة الموجودة والسابقة، دون استبدال محتواها.
|
|  | [getOutputFormat()](#getOutputFormat--) | يسمح بتحديد صيغة Presentation التي ستُستخدم لحفظ المستند |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | يسمح بتحديد صيغة Presentation التي ستُستخدم لحفظ المستند |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | يسمح بتحديد مصفوفة بأرقام الشرائح (بدءًا من 1) التي يجب حذفها من العرض التقديمي أثناء حفظه، في حال تم إدراج الشريحة المعدلة في عرض تقديمي موجود. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | يسمح بتحديد مصفوفة بأرقام الشرائح (بدءًا من 1) التي يجب حذفها من العرض التقديمي أثناء حفظه، في حال تم إدراج الشريحة المعدلة في عرض تقديمي موجود. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من PresentationSaveOptions بصيغة إخراج PPTX (يمكن تعديلها لاحقًا عبر
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) خاصية)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


ينشئ نسخة جديدة من PresentationSaveOptions مع المحدد
صيغة إخراج Presentation إلزامية، بينما جميع المعلمات الأخرى هي
افتراضي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | صيغة الإخراج إلزامية، التي يجب حفظ مستند Presentation بها |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
تشفير مستند Presentation الناتج. بشكل افتراضي يكون NULL -
لن يتم تعيين كلمة المرور. اضبطها على NULL أو سلسلة فارغة لإزالة
كلمة المرور، إذا تم تعيينها مسبقًا.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لتشفير مستند Presentation الناتج.
بشكل افتراضي تكون NULL - لن يتم تعيين كلمة المرور. اضبطها على NULL أو سلسلة فارغة لإزالة كلمة المرور إذا كانت مُعينة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


يسمح بإدراج الشريحة المعدلة في عرض تقديمي موجود بدلاً من إنشاء عرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي).
رقم الشريحة هو رقم يبدأ من 1 لشريحة في العرض التقديمي، المُحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، سيتم إنشاء عرض تقديمي جديد بشريحة واحدة مُعدَّلة. إذا كان أكبر أو أصغر من الصفر، وهناك عرض تقديمي صالح مُحمَّل في فئة Editor، فسيتم إدراج الشريحة المُعدَّلة، المخزَّة داخل كائن EditableDocument المدخل، في هذا العرض التقديمي.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


يسمح بإدراج الشريحة المعدلة في عرض تقديمي موجود بدلاً من إنشاء عرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي).
رقم الشريحة هو رقم يبدأ من 1 لشريحة في العرض التقديمي، المُحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، سيتم إنشاء عرض تقديمي جديد بشريحة واحدة مُعدَّلة. إذا كان أكبر أو أصغر من الصفر، وهناك عرض تقديمي صالح مُحمَّل في فئة Editor، فسيتم إدراج الشريحة المُعدَّلة، المخزَّة داخل كائن EditableDocument المدخل، في هذا العرض التقديمي.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


علامة منطقية تحدد ما إذا كانت الشريحة المعدلة يجب أن تستبدل الشريحة الموجودة في العرض التقديمي الأصلي في الموضع المحدد بواسطة
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) خاصية، أو يجب إدراجها بين الشريحة الموجودة والسابقة، دون استبدال محتواها.
بشكل افتراضي تكون false \\u2014 سيتم استبدال الشريحة الموجودة. يتم تجاهل هذه الخاصية إذا كانت قيمة
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) الخاصية مُضَبَطة إلى '0'.

<br />

*** ** * ** ***

بشكل افتراضي يتم استبدال الشريحة. هذا يعني أنه إذا كان للعرض التقديمي المعطى 5 شرائح، وكان SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4، فسيتم استبدال الشريحة الرابعة بالشريحة المُعدَّلة الجديدة، بينما سيظل عدد الشرائح الكلي في العرض (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية إلى  *true* ، فستُدرج الشريحة المُعدَّلة الجديدة كشريحة رابعة، وستُدَفَع جميع الشرائح اللاحقة إلى النهاية: الشريحة الرابعة \"القديمة\" تصبح خامسة، والخامسة تصبح سادسة، وسيزداد العدد الكلي للشرائح في العرض التقديمي بواحد ليصبح 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


علامة منطقية تحدد ما إذا كانت الشريحة المعدلة يجب أن تستبدل الشريحة الموجودة في العرض التقديمي الأصلي في الموضع المحدد بواسطة
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) خاصية، أو يجب إدراجها بين الشريحة الموجودة والسابقة، دون استبدال محتواها.
بشكل افتراضي تكون false \\u2014 سيتم استبدال الشريحة الموجودة. يتم تجاهل هذه الخاصية إذا كانت قيمة
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) الخاصية مُضَبَطة إلى '0'.

<br />

*** ** * ** ***

بشكل افتراضي يتم استبدال الشريحة. هذا يعني أنه إذا كان للعرض التقديمي المعطى 5 شرائح، وكان SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4، فسيتم استبدال الشريحة الرابعة بالشريحة المُعدَّلة الجديدة، بينما سيظل عدد الشرائح الكلي في العرض (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية إلى  *true* ، فستُدرج الشريحة المُعدَّلة الجديدة كشريحة رابعة، وستُدَفَع جميع الشرائح اللاحقة إلى النهاية: الشريحة الرابعة \"القديمة\" تصبح خامسة، والخامسة تصبح سادسة، وسيزداد العدد الكلي للشرائح في العرض التقديمي بواحد ليصبح 6.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


يسمح بتحديد صيغة Presentation التي ستُستخدم لحفظ المستند

<br />

*** ** * ** ***

عادةً ما يتم تعيين تنسيق الإخراج في مُنشئ هذه الفئة، لأنه إلزامي. تسمح هذه الخاصية بالحصول على تنسيق الإخراج أو تعديلّه لاحقًا، عندما يكون كائن من فئة [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) قد تم إنشاؤه بالفعل.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


يسمح بتحديد صيغة Presentation التي ستُستخدم لحفظ المستند

<br />

*** ** * ** ***

عادةً ما يتم تعيين تنسيق الإخراج في مُنشئ هذه الفئة، لأنه إلزامي. تسمح هذه الخاصية بالحصول على تنسيق الإخراج أو تعديلّه لاحقًا، عندما يكون كائن من فئة [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) قد تم إنشاؤه بالفعل.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


يسمح بتحديد مصفوفة تحتوي على أرقام شرائح تبدأ من 1 يجب حذفها من العرض التقديمي أثناء حفظه، في حالة إدراج الشريحة المُعدَّلة في عرض تقديمي موجود. عندما يتم حفظ الشريحة المُعدَّلة ليس كعرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي)، بل يتم حفظها في عرض تقديمي موجود (باستخدام #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int))، يمكن أيضًا حذف بعض الشرائح المحددة من هذا العرض عن طريق تحديد أرقامها في هذه المصفوفة. بشكل افتراضي تكون هذه المصفوفة  null  \\u2014 لن يتم حذف أي شرائح. ومع ذلك، عندما تكون هذه المصفوفة غير فارغة وغير null، وتحتوي على رقم شريحة صالح واحد على الأقل، بعد توليد مستند العرض التقديمي الناتج بمحتوى الشريحة المُعدَّلة، سيتم حذف الشرائح ذات الأرقام المحددة من العرض مباشرةً قبل كتابة محتواها إلى تدفق الإخراج أو الملف. أرقام الشرائح في هذه المصفوفة تبدأ من 1، ليست من 0. سيتم تجاهل الأرقام غير الصالحة (أقل من 1 أو أكبر من إجمالي عدد الشرائح).


**Returns:**
int[] - مصفوفة من أرقام الشرائح التي تبدأ من 1 للحذف، أو  null  إذا لم يُحذف شيء.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


يسمح بتحديد مصفوفة تحتوي على أرقام شرائح تبدأ من 1 يجب حذفها من العرض التقديمي أثناء حفظه، في حالة إدراج الشريحة المُعدَّلة في عرض تقديمي موجود. أرقام الشرائح في هذه المصفوفة تبدأ من 1. سيتم تجاهل الأرقام غير الصالحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | int[] | مصفوفة من أرقام الشرائح التي تبدأ من 1 للحذف (قد تكون  null  أو فارغة). |
|


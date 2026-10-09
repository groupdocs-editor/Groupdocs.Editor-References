---
title: "SpreadsheetSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Spreadsheet المتوافقة مع Excel"
type: docs
weight: 37
url: /ar/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ Spreadsheet
(Excel-compliant) المستندات

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | هذا المُنشئ بدون معلمات ينشئ مثيلاً جديداً من SpreadsheetSaveOptions مع تنسيق إخراج XLSX (يمكن تعديله لاحقاً عبر |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) خاصية)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | ينشئ مثيلاً جديداً من SpreadsheetSaveOptions مع الإلزامي المحدد |
تنسيق إخراج Spreadsheet، بينما جميع المعلمات الأخرى هي الافتراضية
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ |
يُستخدم لتشفير مستند Spreadsheet المُولد، إذا كان تنسيق هذا المستند
يدعم حماية كلمة المرور.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ |
يُستخدم لتشفير مستند Spreadsheet المُولد، إذا كان تنسيق هذا المستند
يدعم حماية كلمة المرور.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | يسمح بإدراج ورقة عمل مُعدلة في نسخة من جدول بيانات موجود |
بدلاً من إنشاء جدول بيانات جديد بورقة عمل واحدة (الافتراضي
السلوك).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | يسمح بإدراج ورقة عمل مُعدلة في نسخة من جدول بيانات موجود |
بدلاً من إنشاء جدول بيانات جديد بورقة عمل واحدة (الافتراضي
السلوك).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | علامة منطقية، تحدد ما إذا كانت ورقة العمل المُعدلة يجب أن تستبدل |
ورقة العمل الموجودة في جدول البيانات الأصلي في الموضع المحدد بواسطة
ال

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
خاصية، أو يجب حقنها بين ورقة العمل الموجودة و
السابق، دون استبدال محتواه.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | علامة منطقية، تحدد ما إذا كانت ورقة العمل المُعدلة يجب أن تستبدل |
ورقة العمل الموجودة في جدول البيانات الأصلي في الموضع المحدد بواسطة
ال

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
خاصية، أو يجب حقنها بين ورقة العمل الموجودة و
السابق، دون استبدال محتواه.
|
|  | [getOutputFormat()](#getOutputFormat--) | يسمح بتحديد تنسيق Spreadsheet، والذي سيُستخدم لحفظ |
وثيقة
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | يسمح بتحديد تنسيق Spreadsheet، والذي سيُستخدم لحفظ |
وثيقة
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | يسمح بتمكين حماية ورقة العمل للمستند Spreadsheet الناتج |
المستند.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | يسمح بتمكين حماية ورقة العمل للمستند Spreadsheet الناتج |
المستند.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | يسمح بتحديد مصفوفة تحتوي على أرقام أوراق العمل مرتبة بدءًا من 1 والتي يجب حذفها من الـ spreadsheet أثناء حفظه، في حال تم إدراج ورقة العمل المعدلة في الـ spreadsheet الموجود. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | يسمح بتحديد مصفوفة تحتوي على أرقام أوراق العمل مرتبة بدءًا من 1 والتي يجب حذفها من الـ spreadsheet أثناء حفظه، في حال تم إدراج ورقة العمل المعدلة في الـ spreadsheet الموجود. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


هذا المُنشئ بدون معلمات ينشئ مثيلاً جديداً من SpreadsheetSaveOptions مع تنسيق إخراج XLSX (يمكن تعديله لاحقاً عبر
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) خاصية)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


ينشئ مثيلاً جديداً من SpreadsheetSaveOptions مع الإلزامي المحدد
تنسيق إخراج Spreadsheet، بينما جميع المعلمات الأخرى هي الافتراضية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | تنسيق الإخراج الإلزامي، الذي يجب حفظ مستند Spreadsheet به |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ
يُستخدم لتشفير مستند Spreadsheet المُولد، إذا كان تنسيق هذا المستند
يدعم حماية كلمة المرور. حدد NULL أو سلسلة فارغة لإزالة
(تنظيف) كلمة المرور.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور، والتي ستُ
يُستخدم لتشفير مستند Spreadsheet المُولد، إذا كان تنسيق هذا المستند
يدعم حماية كلمة المرور. حدد NULL أو سلسلة فارغة لإزالة
(تنظيف) كلمة المرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


يسمح بإدراج ورقة عمل مُعدلة في نسخة من جدول بيانات موجود
بدلاً من إنشاء جدول بيانات جديد بورقة عمل واحدة (الافتراضي
السلوك). WorksheetNumber هو رقم ورقة عمل يبدأ من 1 في الـ
الـ spreadsheet، المحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، فإن
سيتم إنشاء spreadsheet جديد مع ورقة عمل واحدة معدلة. إذا كان
أكبر أو أصغر من الصفر، وهناك spreadsheet صالح، محمَّل في
فئة Editor، ورقة العمل المعدلة، التي تمثلها المدخل
مثيل EditableDocument، سيتم إدراجه في هذا الـ spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


يسمح بإدراج ورقة عمل مُعدلة في نسخة من جدول بيانات موجود
بدلاً من إنشاء جدول بيانات جديد بورقة عمل واحدة (الافتراضي
السلوك). WorksheetNumber هو رقم ورقة عمل يبدأ من 1 في الـ
الـ spreadsheet، المحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، فإن
سيتم إنشاء spreadsheet جديد مع ورقة عمل واحدة معدلة. إذا كان
أكبر أو أصغر من الصفر، وهناك spreadsheet صالح، محمَّل في
فئة Editor، ورقة العمل المعدلة، التي تمثلها المدخل
مثيل EditableDocument، سيتم إدراجه في هذا الـ spreadsheet.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


علامة منطقية، تحدد ما إذا كانت ورقة العمل المُعدلة يجب أن تستبدل
ورقة العمل الموجودة في جدول البيانات الأصلي في الموضع المحدد بواسطة
ال

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
خاصية، أو يجب حقنها بين ورقة العمل الموجودة و
السابق، دون استبدال محتواه. القيمة الافتراضية هي false \u2014
ستستبدل ورقة العمل الموجودة. يتم تجاهل هذه الخاصية إذا كانت القيمة
لـ

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
الخاصية مضبوطة على '0'.


*** ** * ** ***

بشكل افتراضي يتم استبدال ورقة العمل. هذا يعني أنه إذا كان الـ spreadsheet المعطى يحتوي على 5 أوراق عمل، و WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4، فإن ورقة العمل الرابعة سيتم استبدالها بورقة العمل المعدلة الجديدة، بينما سيظل إجمالي عدد أوراق العمل في الـ spreadsheet (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية على  *true* ، سيتم حقن ورقة العمل المعدلة الجديدة كورقة رابعة، وسيتم إزاحة جميع أوراق العمل اللاحقة إلى النهاية: \"old\" الورقة الرابعة تصبح الخامسة، والورقة الخامسة تصبح السادسة، وسيتم زيادة إجمالي عدد أوراق العمل في الـ spreadsheet بمقدار واحد ليصبح 6.

<br />



**Returns:**
منطقي -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


علامة منطقية، تحدد ما إذا كانت ورقة العمل المُعدلة يجب أن تستبدل
ورقة العمل الموجودة في جدول البيانات الأصلي في الموضع المحدد بواسطة
ال

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
خاصية، أو يجب حقنها بين ورقة العمل الموجودة و
السابق، دون استبدال محتواه. القيمة الافتراضية هي false \u2014
ستستبدل ورقة العمل الموجودة. يتم تجاهل هذه الخاصية إذا كانت القيمة
لـ

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
الخاصية مضبوطة على '0'.


*** ** * ** ***

بشكل افتراضي يتم استبدال ورقة العمل. هذا يعني أنه إذا كان الـ spreadsheet المعطى يحتوي على 5 أوراق عمل، و WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4، فإن ورقة العمل الرابعة سيتم استبدالها بورقة العمل المعدلة الجديدة، بينما سيظل إجمالي عدد أوراق العمل في الـ spreadsheet (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية على  *true* ، سيتم حقن ورقة العمل المعدلة الجديدة كورقة رابعة، وسيتم إزاحة جميع أوراق العمل اللاحقة إلى النهاية: \"old\" الورقة الرابعة تصبح الخامسة، والورقة الخامسة تصبح السادسة، وسيتم زيادة إجمالي عدد أوراق العمل في الـ spreadsheet بمقدار واحد ليصبح 6.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


يسمح بتحديد تنسيق Spreadsheet، والذي سيُستخدم لحفظ
وثيقة


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


يسمح بتحديد تنسيق Spreadsheet، والذي سيُستخدم لحفظ
وثيقة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


يسمح بتمكين حماية ورقة العمل للمستند Spreadsheet الناتج
المستند. القيمة الافتراضية هي NULL - لا يتم تطبيق الحماية. ليست كل الصيغ
تدعم حماية ورقة العمل.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


يسمح بتمكين حماية ورقة العمل للمستند Spreadsheet الناتج
المستند. القيمة الافتراضية هي NULL - لا يتم تطبيق الحماية. ليست كل الصيغ
تدعم حماية ورقة العمل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


يسمح بتحديد مصفوفة تحتوي على أرقام أوراق العمل مرتبة بدءًا من 1 والتي يجب حذفها من الـ spreadsheet أثناء حفظه، في حال تم إدراج ورقة العمل المعدلة في الـ spreadsheet الموجود. عندما يتم حفظ ورقة العمل المعدلة ليس كـ spreadsheet جديد يحتوي على ورقة عمل واحدة (السلوك الافتراضي)، بل يتم حفظها في الـ spreadsheet الموجود (باستخدام #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int))، يمكن أيضًا حذف بعض أوراق العمل المحددة من هذا الـ spreadsheet عن طريق تحديد أرقامها في هذه المصفوفة. بشكل افتراضي هذه المصفوفة هي  null  \u2014 لا يتم حذف أي أوراق عمل. ومع ذلك، عندما تكون هذه المصفوفة غير null وغير فارغة، وتحتوي على رقم ورقة عمل صالح واحد على الأقل، بعد إنشاء مستند الـ spreadsheet الناتج بمحتوى ورقة العمل المعدلة، سيتم حذف أوراق العمل ذات الأرقام المحددة من الـ spreadsheet مباشرة قبل كتابة محتواها إلى تدفق الإخراج أو الملف. أرقام أوراق العمل في هذه المصفوفة تبدأ من 1، ليست من 0. سيتم تجاهل الأرقام غير الصالحة (أقل من 1 أو أكبر من إجمالي عدد أوراق العمل).


**Returns:**
int[] - مصفوفة أرقام أوراق العمل التي تبدأ من 1 للحذف، أو  null  إذا لم يكن هناك شيء يجب حذفه.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


يسمح بتحديد مصفوفة تحتوي على أرقام أوراق العمل التي تبدأ من 1 والتي يجب حذفها من جدول البيانات أثناء حفظه، في حالة إدراج ورقة العمل المعدلة في جدول بيانات موجود. أرقام أوراق العمل في هذه المصفوفة تبدأ من 1. سيتم تجاهل الأرقام غير الصالحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | int[] | مصفوفة أرقام أوراق العمل التي تبدأ من 1 للحذف (قد تكون  null  أو فارغة). |
|


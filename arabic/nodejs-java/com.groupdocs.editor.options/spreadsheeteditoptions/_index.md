---
title: "SpreadsheetEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع صيغ جداول البيانات المتوافقة مع Excel المدعومة"
type: docs
weight: 35
url: /ar/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة
صيغ جداول البيانات (متوافقة مع Excel)

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في الإدخال |
مستند جدول البيانات الذي يجب تحويله إلى HTML (انظر
ملاحظات).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في الإدخال |
مستند جدول البيانات الذي يجب تحويله إلى HTML (انظر
ملاحظات).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | يسمح باستبعاد أوراق العمل المخفية في مستند جدول البيانات المدخل، بحيث |
سيتم تجاهلها تمامًا.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | يسمح باستبعاد أوراق العمل المخفية في مستند جدول البيانات المدخل، بحيث |
سيتم تجاهلها تمامًا.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | عند التفعيل، سيتم |
تمثيل الخلايا الأفقية الفارغة المتجاورة من مستند جدول البيانات المدخل في مستند HTML قابل للتحرير كدمجها في خلية واحدة مع
خاصية colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | عند التفعيل، يحتوي جدول HTML في مستند HTML الناتج على صف سفلي مخفي فارغ مع |
ارتفاع صفر وخلايا فارغة، حيث يتم تحديد العرض فقط.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في الإدخال
مستند جدول البيانات الذي يجب تحويله إلى HTML (انظر
ملاحظات).


*** ** * ** ***

تدعم معظم مستندات جداول البيانات مفهوم التبويبات، أي يمكن أن تكون متعددة التبويبات. من ناحية أخرى، لا يدعم تنسيق HTML هذا الهيكل. لذلك يمكن لـ GroupDocs.Editor تحويل إلى HTML تبويبًا واحدًا محددًا فقط من المستند المدخل، ويسمح هذا الخيار بتحديده. فهرس التبويب يعتمد على الصفر، والقيم السالبة محظورة. إذا تجاوز الفهرس المحدد عدد جميع التبويبات، سيتم رمي استثناء. إذا كان مستند جدول البيانات المدخل يحتوي على تبويب واحد فقط، سيتم تجاهل هذا الخيار. القيمة الافتراضية هي 0 (التبويب الأول).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في الإدخال
مستند جدول البيانات الذي يجب تحويله إلى HTML (انظر
ملاحظات).


*** ** * ** ***

تدعم معظم مستندات جداول البيانات مفهوم التبويبات، أي يمكن أن تكون متعددة التبويبات. من ناحية أخرى، لا يدعم تنسيق HTML هذا الهيكل. لذلك يمكن لـ GroupDocs.Editor تحويل إلى HTML تبويبًا واحدًا محددًا فقط من المستند المدخل، ويسمح هذا الخيار بتحديده. فهرس التبويب يعتمد على الصفر، والقيم السالبة محظورة. إذا تجاوز الفهرس المحدد عدد جميع التبويبات، سيتم رمي استثناء. إذا كان مستند جدول البيانات المدخل يحتوي على تبويب واحد فقط، سيتم تجاهل هذا الخيار. القيمة الافتراضية هي 0 (التبويب الأول).

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


يسمح باستبعاد أوراق العمل المخفية في مستند جدول البيانات المدخل، بحيث
سيتم تجاهلها تمامًا. القيمة الافتراضية هي false - أوراق العمل المخفية هي
متاحة وتُعالج كالعادية.


*** ** * ** ***

تدعم عدة صيغ ثنائية لجداول البيانات (مثل XLSX) مفهوم أوراق العمل المخفية (التبويبات). قد يحتوي مستند بهذه الصيغة، إذا كان لديه أكثر من ورقة عمل واحدة، على أوراق عمل مخفية إضافية. بشكل افتراضي تكون هذه الأوراق المخفية متاحة للمعالجة، ولكن مع هذا الخيار يمكن تجاهلها، كأنها غير موجودة. عند تفعيل هذا الخيار، لا يمكنك اختيار ورقة عمل مخفية باستخدام الخاصية ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


يسمح باستبعاد أوراق العمل المخفية في مستند جدول البيانات المدخل، بحيث
سيتم تجاهلها تمامًا. القيمة الافتراضية هي false - أوراق العمل المخفية هي
متاحة وتُعالج كالعادية.


*** ** * ** ***

تدعم عدة صيغ ثنائية لجداول البيانات (مثل XLSX) مفهوم أوراق العمل المخفية (التبويبات). قد يحتوي مستند بهذه الصيغة، إذا كان لديه أكثر من ورقة عمل واحدة، على أوراق عمل مخفية إضافية. بشكل افتراضي تكون هذه الأوراق المخفية متاحة للمعالجة، ولكن مع هذا الخيار يمكن تجاهلها، كأنها غير موجودة. عند تفعيل هذا الخيار، لا يمكنك اختيار ورقة عمل مخفية باستخدام الخاصية ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


عند التفعيل، سيتم
تمثيل الخلايا الأفقية الفارغة المتجاورة من مستند جدول البيانات المدخل في مستند HTML قابل للتحرير كدمجها في خلية واحدة مع
خاصية colspan. بشكل افتراضي تكون معطلة (false).


بشكل افتراضي يقوم GroupDocs.Editor بتحويل جدول من مستند جدول البيانات المدخل إلى الناتج
مستند HTML مع الحفاظ على كل خلية. ومع ذلك، قد تكون مستندات جداول البيانات متفرقة \\u2014 هي
قد تحتوي على كمية هائلة من \"المناطق الفارغة\"، حيث تكون العديد من الخلايا فارغة. هذا الخيار، عندما
يتم تفعيله، يدمج هذه الخلايا الفارغة في خلية واحدة مع خاصية colspan في عنصر TD،
وبالتالي يمكنه تقليل حجم العلامات HTML المنتجة بشكل كبير.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


عند التفعيل، يحتوي جدول HTML في مستند HTML الناتج على صف سفلي مخفي فارغ مع
ارتفاع صفر وخلايا فارغة، حيث يتم تحديد العرض فقط. هذا الصف مع الخلايا الفارغة يحتوي على
قيم عرض دقيقة لكل عمود وتحسين التحويل العكسي من HTML إلى جدول بيانات. بواسطة
الإعداد الافتراضي مفعّل (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |


---
title: "SpreadsheetEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات لجميع صيغ Spreadsheet المتوافقة مع Excel المدعومة"
type: docs
weight: 35
url: /ar/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع الصيغ المدعومة
صيغ Spreadsheet (متوافقة مع Excel)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في المُدخل |
مستند Spreadsheet الذي يجب تحويله إلى HTML (انظر
الملاحظات).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في المُدخل |
مستند Spreadsheet الذي يجب تحويله إلى HTML (انظر
الملاحظات).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المُدخل، بحيث |
سيتم تجاهلها تمامًا.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المُدخل، بحيث |
سيتم تجاهلها تمامًا.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | عند التفعيل، سيتم تحويل الخلايا الأفقية الفارغة المتجاورة من مستند Spreadsheet المُدخل |
إلى مستند HTML قابل للتحرير كخلية واحدة مدمجة مع
السمة colspan.
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


يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في المُدخل
مستند Spreadsheet الذي يجب تحويله إلى HTML (انظر
الملاحظات).


*** ** * ** ***

تدعم معظم مستندات Spreadsheet مفهوم التبويبات، أي يمكن أن تكون متعددة التبويبات. من ناحية أخرى، لا يدعم تنسيق HTML هذا الهيكل. بسبب ذلك، يمكن لـ GroupDocs.Editor تحويل إلى HTML تبويبًا واحدًا محددًا فقط من المستند المُدخل، وتتيح هذه الخيار تحديده. فهرس التبويب يعتمد على الصفر، والقيم السالبة محظورة. إذا تجاوز الفهرس المحدد عدد جميع التبويبات، سيتم رمي استثناء. إذا كان مستند Spreadsheet المُدخل يحتوي على تبويب واحد فقط، سيتجاهل هذا الخيار. القيمة الافتراضية هي 0 (التبويب الأول).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في المُدخل
مستند Spreadsheet الذي يجب تحويله إلى HTML (انظر
الملاحظات).


*** ** * ** ***

تدعم معظم مستندات Spreadsheet مفهوم التبويبات، أي يمكن أن تكون متعددة التبويبات. من ناحية أخرى، لا يدعم تنسيق HTML هذا الهيكل. بسبب ذلك، يمكن لـ GroupDocs.Editor تحويل إلى HTML تبويبًا واحدًا محددًا فقط من المستند المُدخل، وتتيح هذه الخيار تحديده. فهرس التبويب يعتمد على الصفر، والقيم السالبة محظورة. إذا تجاوز الفهرس المحدد عدد جميع التبويبات، سيتم رمي استثناء. إذا كان مستند Spreadsheet المُدخل يحتوي على تبويب واحد فقط، سيتجاهل هذا الخيار. القيمة الافتراضية هي 0 (التبويب الأول).

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المُدخل، بحيث
سيتم تجاهلها تمامًا. القيمة الافتراضية هي false - أوراق العمل المخفية هي
متاحة وتُعالج كعادية.


*** ** * ** ***

تدعم عدة صيغ Spreadsheet الثنائية (مثل XLSX) مفهوم أوراق العمل المخفية (التبويبات). قد يحتوي مستند من هذا النوع، إذا كان يحتوي على أكثر من ورقة عمل واحدة، على أوراق عمل مخفية إضافية. بشكل افتراضي، تكون هذه الأوراق المخفية متاحة للمعالجة، ولكن باستخدام هذا الخيار يمكن تجاهلها، كأنها غير موجودة. عند تفعيل هذا الخيار، لا يمكنك اختيار ورقة عمل مخفية باستخدام خاصية 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المُدخل، بحيث
سيتم تجاهلها تمامًا. القيمة الافتراضية هي false - أوراق العمل المخفية هي
متاحة وتُعالج كعادية.


*** ** * ** ***

تدعم عدة صيغ Spreadsheet الثنائية (مثل XLSX) مفهوم أوراق العمل المخفية (التبويبات). قد يحتوي مستند من هذا النوع، إذا كان يحتوي على أكثر من ورقة عمل واحدة، على أوراق عمل مخفية إضافية. بشكل افتراضي، تكون هذه الأوراق المخفية متاحة للمعالجة، ولكن باستخدام هذا الخيار يمكن تجاهلها، كأنها غير موجودة. عند تفعيل هذا الخيار، لا يمكنك اختيار ورقة عمل مخفية باستخدام خاصية 'WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


عند التفعيل، سيتم تحويل الخلايا الأفقية الفارغة المتجاورة من مستند Spreadsheet المُدخل
إلى مستند HTML قابل للتحرير كخلية واحدة مدمجة مع
السمة colspan. بشكل افتراضي معطلة (false).


بشكل افتراضي يقوم GroupDocs.Editor بتحويل جدول من مستند Spreadsheet المُدخل إلى
مستند HTML مع الحفاظ على كل خلية. ومع ذلك، قد تكون مستندات Spreadsheet متفرقة \\u2014 حيث
قد تحتوي على كمية هائلة من \"المناطق الفارغة\"، حيث تكون العديد من الخلايا فارغة. هذا الخيار، عندما
يُفعَّل، يدمج تلك الخلايا الفارغة في خلية واحدة مع سمة colspan في عنصر TD،
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
| القيمة | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


عند التفعيل، يحتوي جدول HTML في مستند HTML الناتج على صف سفلي مخفي فارغ مع
ارتفاع صفر وخلايا فارغة، حيث يتم تحديد العرض فقط. هذا الصف الذي يحتوي على خلايا فارغة يحتوي على
قيم عرض دقيقة لكل عمود وتحسن التحويل العكسي من HTML إلى جدول بيانات. بواسطة
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
| القيمة | boolean |  |


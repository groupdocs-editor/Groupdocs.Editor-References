---
title: "SpreadsheetFormats"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على جميع تنسيقات XML الثنائية وتنسيقات جداول البيانات النصية مع استبعاد جميع التنسيقات النصية القائمة على الفواصل مثل CSV وTSV وذات الفواصل المنقوطة وغيرها، التي يمكن حفظ المصنف فيها."
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات جداول البيانات الثنائية وXML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV وTSV والفواصل المنقوطة وما إلى ذلك)، التي يمكن حفظ المصنف فيها.
يتضمن الصيغ التالية:
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
تعرف على المزيد حول تنسيقات جداول البيانات [هنا](../https://wiki.fileformat.com/spreadsheet).

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Xls](#Xls) | تنسيق ملف Excel الثنائي 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | قالب Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | دفتر عمل Office Open XML خالٍ من الماكرو (XLSX). |
|
|  | [Xlsm](#Xlsm) | دفتر عمل Office Open XML يدعم الماكرو (XLSM). |
|
|  | [Xlsb](#Xlsb) | دفتر عمل Excel الثنائي (XLSB). |
|
|  | [Xltx](#Xltx) | قالب Office Open XML خالٍ من الماكرو (XLTX). |
|
|  | [Xltm](#Xltm) | قالب Office Open XML مُمكّن للماكرو (XLTM). |
|
|  | [Xlam](#Xlam) | ملحق Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — تنسيق XML لبرنامج Microsoft Office Excel 2002 و Excel 2003. |
|
|  | [Ods](#Ods) | جدول بيانات OpenDocument (ODS). |
|
|  | [Fods](#Fods) | جدول بيانات OpenDocument مسطح (FODS). |
|
|  | [Sxc](#Sxc) | جدول بيانات XML لبرنامج StarOffice أو OpenOffice.org Calc (SXC). |
|
|  | [Dif](#Dif) | تنسيق تبادل البيانات (DIF). |
|
|  | [Csv](#Csv) | قيم مفصولة بفواصل (CSV). |
|
|  | [Tsv](#Tsv) | قيم مفصولة بعلامة تبويب (TSV). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد لجميع [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | يسترجع نسخة من النوع المحدد [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) التي لها امتداد الملف المحدد. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | يحوّل سلسلة تمثل امتداد ملف إلى كائن [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


تنسيق ملف Excel الثنائي 97-2003 (XLS).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


قالب Excel 97-2003 (XLT).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


دفتر عمل Office Open XML خالٍ من الماكرو (XLSX).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


دفتر عمل Office Open XML يدعم الماكرو (XLSM).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


دفتر عمل Excel الثنائي (XLSB).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


قالب Office Open XML خالٍ من الماكرو (XLTX).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


قالب Office Open XML مُمكّن للماكرو (XLTM).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


ملحق Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — تنسيق XML لبرنامج Microsoft Office Excel 2002 و Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


جدول بيانات OpenDocument (ODS).
تعرف على المزيد حول هذه الصيغة
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


جدول بيانات OpenDocument مسطح (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


جدول بيانات XML لبرنامج StarOffice أو OpenOffice.org Calc (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


تنسيق تبادل البيانات (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


قيم مفصولة بفواصل (CSV).
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


قيم مفصولة بعلامة تبويب (TSV).
تعرف على المزيد حول هذه الصيغة
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد لجميع [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
القيمة: IEnumerable{SpreadsheetFormats} يحتوي على جميع نسخ [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


يسترجع نسخة من النوع المحدد [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) التي لها امتداد الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | امتداد الملف لتنسيق المستند. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


يحوّل سلسلة تمثل امتداد ملف إلى كائن [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الامتداد | java.lang.String | ملحق الملف للتحويل. إذا كان الملحق يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


---
title: "SpreadsheetFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على جميع تنسيقات الجداول الإلكترونية الثنائية، XML والنصية باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV، TSV، المفصولة بفواصل منقوطة، إلخ، التي يمكن حفظ المصنف فيها."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

يحتوي على جميع تنسيقات جداول البيانات الثنائية وXML والنصية (باستثناء جميع التنسيقات النصية القائمة على الفواصل مثل CSV وTSV والفواصل المنقوطة وغيرها)، التي يمكن حفظ المصنف فيها.
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
اعرف المزيد عن تنسيقات الجداول الإلكترونية [هنا](../https://wiki.fileformat.com/spreadsheet).

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Xls](#Xls) | تنسيق ملف Excel الثنائي 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | قالب Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | مصنف Office Open XML خالٍ من الماكرو (XLSX). |
|
|  | [Xlsm](#Xlsm) | مصنف Office Open XML مع تمكين الماكرو (XLSM). |
|
|  | [Xlsb](#Xlsb) | مصنف Excel الثنائي (XLSB). |
|
|  | [Xltx](#Xltx) | قالب Office Open XML خالٍ من الماكرو (XLTX). |
|
|  | [Xltm](#Xltm) | قالب Office Open XML مع تمكين الماكرو (XLTM). |
|
|  | [Xlam](#Xlam) | ملحق Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — تنسيق XML لـ Microsoft Office Excel 2002 و Excel 2003. |
|
|  | [Ods](#Ods) | جدول OpenDocument (ODS). |
|
|  | [Fods](#Fods) | جدول OpenDocument مسطح (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice أو OpenOffice.org Calc XML Spreadsheet (SXC). |
|
|  | [Dif](#Dif) | تنسيق تبادل البيانات (DIF). |
|
|  | [Csv](#Csv) | القيم المفصولة بفواصل (CSV). |
|
|  | [Tsv](#Tsv) | القيم المفصولة بعلامات جدولة (TSV). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAll()](#getAll--) | يحصل على مجموعة قابلة للتعداد من جميع [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
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
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


قالب Excel 97-2003 (XLT).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


مصنف Office Open XML خالٍ من الماكرو (XLSX).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


مصنف Office Open XML مع تمكين الماكرو (XLSM).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


مصنف Excel الثنائي (XLSB).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


قالب Office Open XML خالٍ من الماكرو (XLTX).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


قالب Office Open XML مع تمكين الماكرو (XLTM).
اعرف المزيد عن تنسيق الملف هذا
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


SpreadsheetML — تنسيق XML لـ Microsoft Office Excel 2002 و Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


جدول OpenDocument (ODS).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


جدول OpenDocument مسطح (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice أو OpenOffice.org Calc XML Spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


تنسيق تبادل البيانات (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


القيم المفصولة بفواصل (CSV).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


القيم المفصولة بعلامات جدولة (TSV).
اعرف المزيد عن تنسيق الملف هذا
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


يحصل على مجموعة قابلة للتعداد من جميع [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
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
|  | الامتداد | java.lang.String | امتداد الملف للتحويل. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


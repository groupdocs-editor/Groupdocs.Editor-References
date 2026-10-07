---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Çalışma kitabının kaydedilebileceği CSV, TSV, noktalı virgül gibi ayırıcı tabanlı metin formatları dışındaki tüm ikili XML ve metinsel Spreadsheet formatlarını kapsüller."
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metin tabanlı Elektronik Tablo formatlarını (CSV, TSV, noktalı virgül gibi ayırıcılarla kullanılan metin tabanlı ayırıcı formatları hariç) kapsar.
Aşağıdaki formatları içerir:
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
Spreadsheet formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet).

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 Binary File Format (XLS). |
|
|  | [Xlt](#Xlt) | Excel 97-2003 Template (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML Workbook Macro-Free (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML Çalışma Kitabı Makro Etkin (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel İkili Çalışma Kitabı (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML Şablonu Makrosuz (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML Şablonu Makro Etkin (XLTM). |
|
|  | [Xlam](#Xlam) | Excel Eklentisi (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Microsoft Office Excel 2002 ve Excel 2003 XML Formatı. |
|
|  | [Ods](#Ods) | OpenDocument Hesap Tablosu (ODS). |
|
|  | [Fods](#Fods) | Düz OpenDocument Hesap Tablosu (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice veya OpenOffice.org Calc XML Hesap Tablosu (SXC). |
|
|  | [Dif](#Dif) | Veri Değişim Formatı (DIF). |
|
|  | [Csv](#Csv) | Virgülle Ayrılmış Değerler (CSV). |
|
|  | [Tsv](#Tsv) | Sekme ile Ayrılmış Değerler (TSV). |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) öğelerinin sayılabilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) örneğini getirir. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Bir dosya uzantısını temsil eden dizeyi bir [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) nesnesine dönüştürür. |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 Binary File Format (XLS).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 Template (XLT).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML Workbook Macro-Free (XLSX).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML Çalışma Kitabı Makro Etkin (XLSM).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel İkili Çalışma Kitabı (XLSB).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML Şablonu Makrosuz (XLTX).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML Şablonu Makro Etkin (XLTM).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel Eklentisi (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \\u2014 Microsoft Office Excel 2002 ve Excel 2003 XML Formatı.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument Hesap Tablosu (ODS).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Düz OpenDocument Hesap Tablosu (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice veya OpenOffice.org Calc XML Hesap Tablosu (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Veri Değişim Formatı (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Virgülle Ayrılmış Değerler (CSV).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Sekme ile Ayrılmış Değerler (TSV).
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Tüm [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) öğelerinin sayılabilir bir koleksiyonunu alır.
Değer: Tüm [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) örneklerini içeren bir IEnumerable{SpreadsheetFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) örneğini getirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Bir dosya uzantısını temsil eden dizeyi bir [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


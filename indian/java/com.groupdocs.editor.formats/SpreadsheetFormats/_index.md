---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "यह सभी बाइनरी XML और टेक्स्टुअल स्प्रेडशीट फ़ॉर्मेट को समाहित करता है, जिसमें CSV, TSV, सेमीकोलन-डिलिमिटेड आदि जैसे विभाजक-आधारित टेक्स्टुअल फ़ॉर्मेट को बाहर रखा गया है, जिनमें वर्कबुक को सहेजा जा सकता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

सभी बाइनरी, XML और पाठ्य स्प्रेडशीट फ़ॉर्मेट को संलग्न करता है (CSV, TSV, सेमीकोलन-डिलिमिटेड आदि जैसे विभाजक-आधारित पाठ्य फ़ॉर्मेट को छोड़कर), जिसमें वर्कबुक को सहेजा जा सकता है।
निम्नलिखित स्वरूप शामिल हैं:
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
स्प्रेडशीट फ़ॉर्मेट के बारे में अधिक जानें [here](../https://wiki.fileformat.com/spreadsheet)।

## Fields

| Field | विवरण |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 बाइनरी फ़ाइल प्रारूप (XLS)। |
|
|  | [Xlt](#Xlt) | Excel 97-2003 टेम्प्लेट (XLT)। |
|
|  | [Xlsx](#Xlsx) | Office Open XML वर्कबुक मैक्रो-फ़्री (XLSX)। |
|
|  | [Xlsm](#Xlsm) | Office Open XML वर्कबुक मैक्रो-एनेबल्ड (XLSM)। |
|
|  | [Xlsb](#Xlsb) | Excel बाइनरी वर्कबुक (XLSB)। |
|
|  | [Xltx](#Xltx) | Office Open XML टेम्प्लेट मैक्रो-फ़्री (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML टेम्प्लेट मैक्रो-सक्षम (XLTM). |
|
|  | [Xlam](#Xlam) | Excel ऐड‑इन (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Microsoft Office Excel 2002 और Excel 2003 XML फ़ॉर्मेट. |
|
|  | [Ods](#Ods) | OpenDocument स्प्रेडशीट (ODS). |
|
|  | [Fods](#Fods) | फ़्लैट OpenDocument स्प्रेडशीट (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice या OpenOffice.org Calc XML स्प्रेडशीट (SXC). |
|
|  | [Dif](#Dif) | डेटा इंटरचेंज फ़ॉर्मेट (DIF). |
|
|  | [Csv](#Csv) | कॉमा सेपरेटेड वैल्यूज़ (CSV). |
|
|  | [Tsv](#Tsv) | टैब-सेपरेटेड वैल्यूज़ (TSV). |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) की एनेरेबल कलेक्शन प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) का एक इंस्टेंस पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 बाइनरी फ़ाइल प्रारूप (XLS)।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 टेम्प्लेट (XLT)।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML वर्कबुक मैक्रो-फ़्री (XLSX)।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML वर्कबुक मैक्रो-एनेबल्ड (XLSM)।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel बाइनरी वर्कबुक (XLSB)।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML टेम्प्लेट मैक्रो-फ़्री (XLTX).
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML टेम्प्लेट मैक्रो-सक्षम (XLTM).
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel ऐड‑इन (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Microsoft Office Excel 2002 और Excel 2003 XML फ़ॉर्मेट.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument स्प्रेडशीट (ODS).
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


फ़्लैट OpenDocument स्प्रेडशीट (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice या OpenOffice.org Calc XML स्प्रेडशीट (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


डेटा इंटरचेंज फ़ॉर्मेट (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


कॉमा सेपरेटेड वैल्यूज़ (CSV).
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


टैब-सेपरेटेड वैल्यूज़ (TSV).
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


सभी [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) की एनेरेबल कलेक्शन प्राप्त करता है।
मान: सभी [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) के इंस्टेंस को शामिल करने वाला IEnumerable{SpreadsheetFormats}।


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) का एक इंस्टेंस पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


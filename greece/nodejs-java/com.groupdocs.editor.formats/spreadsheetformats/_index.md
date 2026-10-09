---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει όλες τις δυαδικές XML και κειμενικές μορφές Φύλλων Εργασίας, εξαιρώντας όλες τις κειμενικές μορφές βασισμένες σε διαχωριστικά με διαχωριστή όπως CSV, TSV, διαχωρισμένο με ερωτηματικό κ.λπ., στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις δυαδικές, XML και κειμενικές μορφές Φύλλου Εργασίας (εξαιρώντας όλες τις κειμενικές μορφές βασισμένες σε διαχωριστικά με διαχωριστή όπως CSV, TSV, μορφές διαχωρισμένες με άνω-κάτω τελεία κ.λπ.), στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας.
Περιλαμβάνει τις ακόλουθες μορφές:
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
Μάθετε περισσότερα για τις μορφές Φύλλων Εργασίας [εδώ](../https://wiki.fileformat.com/spreadsheet).

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 Δυαδική μορφή αρχείου (XLS). |
|
|  | [Xlt](#Xlt) | Excel 97-2003 Πρότυπο (XLT). |
|
|  | [Xlsx](#Xlsx) | Office Open XML Workbook χωρίς μακροεντολές (XLSX). |
|
|  | [Xlsm](#Xlsm) | Office Open XML Workbook με ενεργοποιημένες μακροεντολές (XLSM). |
|
|  | [Xlsb](#Xlsb) | Excel Δυαδικό βιβλίο εργασίας (XLSB). |
|
|  | [Xltx](#Xltx) | Office Open XML Template χωρίς μακροεντολές (XLTX). |
|
|  | [Xltm](#Xltm) | Office Open XML Template με ενεργοποιημένες μακροεντολές (XLTM). |
|
|  | [Xlam](#Xlam) | Excel Πρόσθετο (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \\u2014 Microsoft Office Excel 2002 και Excel 2003 μορφή XML. |
|
|  | [Ods](#Ods) | OpenDocument Spreadsheet (ODS). |
|
|  | [Fods](#Fods) | Flat OpenDocument Spreadsheet (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice ή OpenOffice.org Calc XML Spreadsheet (SXC). |
|
|  | [Dif](#Dif) | Μορφή Ανταλλαγής Δεδομένων (DIF). |
|
|  | [Csv](#Csv) | Τιμές Διαχωρισμένες με Κόμμα (CSV). |
|
|  | [Tsv](#Tsv) | Τιμές Διαχωρισμένες με Καρτέλα (TSV). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια επαναλήψιμη συλλογή όλων των [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 Δυαδική μορφή αρχείου (XLS).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 Πρότυπο (XLT).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML Workbook χωρίς μακροεντολές (XLSX).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML Workbook με ενεργοποιημένες μακροεντολές (XLSM).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel Δυαδικό βιβλίο εργασίας (XLSB).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML Template χωρίς μακροεντολές (XLTX).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML Template με ενεργοποιημένες μακροεντολές (XLTM).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel Πρόσθετο (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \\u2014 Microsoft Office Excel 2002 και Excel 2003 μορφή XML.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument Spreadsheet (ODS).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument Spreadsheet (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice ή OpenOffice.org Calc XML Spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Μορφή Ανταλλαγής Δεδομένων (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Τιμές Διαχωρισμένες με Κόμμα (CSV).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Τιμές Διαχωρισμένες με Καρτέλα (TSV).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Λαμβάνει μια επαναλήψιμη συλλογή όλων των [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Τιμή: Μια IEnumerable{SpreadsheetFormats} που περιέχει όλες τις εμφανίσεις του [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου για μετατροπή. Εάν η επέκταση περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


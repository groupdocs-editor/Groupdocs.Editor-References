---
title: "SpreadsheetFormats"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιλαμβάνει όλες τις δυαδικές XML και κειμενικές μορφές Spreadsheet, εξαιρώντας όλες τις κειμενικές μορφές βασισμένες σε διαχωριστικά με διαχωριστές όπως CSV, TSV, διαχωρισμένα με ερωτηματικό κ.λπ., στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας."
type: docs
weight: 15
url: /el/java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις δυαδικές, XML και κειμενικές μορφές Spreadsheet (εξαιρώντας όλες τις κειμενικές μορφές βασισμένες σε διαχωριστικά με διαχωριστή όπως CSV, TSV, μορφές διαχωρισμένες με ερωτηματικό κ.λπ.), στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας.
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
Μάθετε περισσότερα για τις μορφές Spreadsheet [εδώ](../https://wiki.fileformat.com/spreadsheet).

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Xls](#Xls) | Μορφή αρχείου Excel 97-2003 Binary (XLS). |
|
|  | [Xlt](#Xlt) | Πρότυπο Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Workbook Office Open XML χωρίς μακροεντολές (XLSX). |
|
|  | [Xlsm](#Xlsm) | Workbook Office Open XML με ενεργοποιημένες μακροεντολές (XLSM). |
|
|  | [Xlsb](#Xlsb) | Workbook Excel Binary (XLSB). |
|
|  | [Xltx](#Xltx) | Πρότυπο Office Open XML χωρίς μακροεντολές (XLTX). |
|
|  | [Xltm](#Xltm) | Πρότυπο Office Open XML με ενεργοποιημένες μακροεντολές (XLTM). |
|
|  | [Xlam](#Xlam) | Πρόσθετο Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — Μορφή XML του Microsoft Office Excel 2002 και Excel 2003. |
|
|  | [Ods](#Ods) | Φύλλο εργασίας OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Επίπεδο φύλλο εργασίας OpenDocument (FODS). |
|
|  | [Sxc](#Sxc) | Φύλλο εργασίας XML του StarOffice ή OpenOffice.org Calc (SXC). |
|
|  | [Dif](#Dif) | Μορφή ανταλλαγής δεδομένων (DIF). |
|
|  | [Csv](#Csv) | Τιμές διαχωρισμένες με κόμμα (CSV). |
|
|  | [Tsv](#Tsv) | Τιμές διαχωρισμένες με καρτέλα (TSV). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια επαναληπτική συλλογή όλων των [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Μορφή αρχείου Excel 97-2003 Binary (XLS).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Πρότυπο Excel 97-2003 (XLT).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Workbook Office Open XML χωρίς μακροεντολές (XLSX).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Workbook Office Open XML με ενεργοποιημένες μακροεντολές (XLSM).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Workbook Excel Binary (XLSB).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Πρότυπο Office Open XML χωρίς μακροεντολές (XLTX).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Πρότυπο Office Open XML με ενεργοποιημένες μακροεντολές (XLTM).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Πρόσθετο Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — Μορφή XML του Microsoft Office Excel 2002 και Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Φύλλο εργασίας OpenDocument (ODS).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Επίπεδο φύλλο εργασίας OpenDocument (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


Φύλλο εργασίας XML του StarOffice ή OpenOffice.org Calc (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Μορφή ανταλλαγής δεδομένων (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Τιμές διαχωρισμένες με κόμμα (CSV).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Τιμές διαχωρισμένες με καρτέλα (TSV).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Λαμβάνει μια επαναληπτική συλλογή όλων των [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Τιμή: Μια IEnumerable{SpreadsheetFormats} που περιέχει όλα τα στιγμιότυπα του [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


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
|  | extension | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
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
|  | extension | java.lang.String | Η κατάληξη αρχείου για μετατροπή. Εάν η κατάληξη περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.


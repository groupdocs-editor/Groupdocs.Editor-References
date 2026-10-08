---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Συμπεριλαμβάνει όλους τους δυαδικούς XML και κειμενικούς μορφότυπους Spreadsheet, εξαιρώντας όλους τους κειμενικούς μορφότυπους βασισμένους σε διαχωριστικά με διαχωριστικό όπως CSV, TSV, διαχωρισμένο με άνω-κάτω τελεία κ.λπ., στους οποίους μπορεί να αποθηκευτεί το βιβλίο εργασίας. Περιλαμβάνει τους ακόλουθους μορφότυπους Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Μάθετε περισσότερα για τους μορφότυπους Spreadsheet εδώhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /el/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Συμπεριλαμβάνει όλους τους δυαδικούς, XML και κειμενικούς μορφότυπους Spreadsheet (εξαιρώντας όλους τους κειμενικούς μορφότυπους βασισμένους σε διαχωριστικά με διαχωριστικό όπως CSV, TSV, διαχωρισμένο με άνω-κάτω τελεία κ.λπ.), στους οποίους μπορεί να αποθηκευτεί το βιβλίο εργασίας. Περιλαμβάνει τους ακόλουθους μορφότυπους: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Μάθετε περισσότερα για τους μορφότυπους Spreadsheet [εδώ](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Λαμβάνει το όνομα της οικογένειας μορφής. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Λαμβάνει μια επαναληπτική συλλογή όλων των [`SpreadsheetFormats`](../spreadsheetformats). |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [`SpreadsheetFormats`](../spreadsheetformats) που έχει την καθορισμένη επέκταση αρχείου. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [`SpreadsheetFormats`](../spreadsheetformats). |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Τιμές Διαχωρισμένες με Κόμμα (CSV). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Μορφή Ανταλλαγής Δεδομένων (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Απλό OpenDocument Spreadsheet (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Μορφή XML του Microsoft Office Excel 2002 και Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice ή OpenOffice.org Calc XML Spreadsheet (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Τιμές Διαχωρισμένες με Καρτέλα (TSV). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Πρόσθετο Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Δυαδική Μορφή Αρχείου Excel 97-2003 (XLS). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Δυαδικό Φύλλο Εργασίας Excel (XLSB). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Φύλλο Εργασίας Office Open XML με Μακροεντολές (XLSM). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Φύλλο Εργασίας Office Open XML χωρίς Μακροεντολές (XLSX). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Πρότυπο Excel 97-2003 (XLT). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Πρότυπο Office Open XML με Μακροεντολές (XLTM). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Πρότυπο Office Open XML χωρίς Μακροεντολές (XLTX). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/spreadsheet/xltx). |

### Δείτε επίσης

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->

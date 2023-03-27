---
title: SpreadsheetFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές δυαδικών XML και κειμενικών υπολογιστικών φύλλων εξαιρουμένων όλων των μορφών που βασίζονται σε οριοθέτες κειμένου με διαχωριστικό όπως CSV TSV οριοθετημένο με ερωτηματικό κ.λπ. στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας. Περιλαμβάνει τις ακόλουθες μορφές__x0Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Μάθετε περισσότερα σχετικά με τις μορφές υπολογιστικών φύλλωνεδώhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /el/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Ενσωματώνει όλες τις μορφές δυαδικών, XML και κειμενικών υπολογιστικών φύλλων (εξαιρουμένων όλων των μορφών που βασίζονται σε οριοθέτες κειμένου με διαχωριστικό όπως CSV, TSV, οριοθετημένο με ερωτηματικό κ.λπ.), στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας. Περιλαμβάνει τις ακόλουθες μορφές:__x0:[`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Μάθετε περισσότερα σχετικά με τις μορφές υπολογιστικών φύλλων[εδώ](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Επιστρέφει μια επέκταση (χωρίς χαρακτήρα κύριας κουκκίδας) αυτής της μορφής υπολογιστικού φύλλου σε πεζά |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Επιστρέφει έναν κωδικό MIME για αυτήν τη μορφή |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Επιστρέφει ένα επίσημο πλήρες όνομα αυτής της μορφής υπολογιστικού φύλλου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Επιστρέφει την παρουσία του[`SpreadsheetFormats`](../spreadsheetformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, το οποίο πιθανώς είναι σε πλαίσιο SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη μορφή υπολογιστικών φύλλων instance |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Ελέγχει δύο δεδομένες περιπτώσεις SpreadsheetFormats στο equality |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Ελέγχει δύο δεδομένες περιπτώσεις SpreadsheetFormats στο inequality |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Τα έγγραφα τιμών διαχωρισμένων με κόμματα (CSV) αντιπροσωπεύουν απλό κείμενο που περιέχει εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Κάθε γραμμή σε ένα αρχείο CSV είναι μια νέα εγγραφή από το σύνολο εγγραφών που περιέχεται στο αρχείο. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Μορφή ανταλλαγής δεδομένων (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Επίπεδο υπολογιστικό φύλλο OpenDocument (FODS) — αποθηκευμένο ως ένα μεμονωμένο μη συμπιεσμένο έγγραφο XML |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Το OpenDocument Spreadsheet (ODS) σημαίνει Μορφή εγγράφου OpenDocument Spreadsheet που είναι επεξεργάσιμη από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα στο αρχείο ODF σε σειρές και στήλες. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | Υπολογιστικό φύλλοML — Microsoft Office Excel 2002 και Excel 2003 XML Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice ή OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Η μορφή αρχείου Τιμές διαχωρισμένες με καρτέλες (TSV) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. Η μορφή αρχείου, παρόμοια με το CSV, χρησιμοποιείται για την οργάνωση δεδομένων με δομημένο τρόπο, προκειμένου να γίνεται εισαγωγή και εξαγωγή μεταξύ διαφορετικών εφαρμογών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Πρόσθετο Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Το Excel 97-2003 Binary File Format (XLS) αντιπροσωπεύει αρχεία που μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων, όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Το Excel Binary Workbook (XLSB) καθορίζει τη μορφή δυαδικού αρχείου Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Το Office Open XML Workbook Macro-Enabled (XLSM) είναι ένας τύπος αρχείων υπολογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Το Το Office Open XML Workbook Free Macro-Free (XLSX) αντιπροσωπεύει έγγραφα που παρουσιάστηκαν από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Το πρότυπο Excel 97-2003 (XLT) αντιπροσωπεύει αρχεία προτύπων που έχουν δημιουργηθεί με το Microsoft Excel, το οποίο είναι μια εφαρμογή υπολογιστικών φύλλων που διατίθεται ως μέρος της σουίτας του Microsoft Office. Το Microsoft Office 97-2003 υποστήριξε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμα αυτών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Το Office Open XML Template Macro-Enabled (XLTM) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπων με δυνατότητα Macro. Τα αρχεία XLTM είναι παρόμοια με τα XLTX σε δομή, εκτός από το ότι το τελευταίο δεν υποστηρίζει τη δημιουργία αρχείων προτύπων με μακροεντολές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Το αρχείο Office Open XML Template Free Macro-Free (XLTX) αντιπροσωπεύει το πρότυπο Microsoft Excel που βασίζεται στις προδιαγραφές μορφής αρχείου του Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις με αυτές που καθορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Επιστρέφει μια εσωτερική κλάση, που παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές υπολογιστικών φύλλων |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Εφαρμόζει IEnumerable γενική διεπαφή, που επιτρέπει μια δυνατότητα «foreach» για το SpreadsheetFormats type |

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->

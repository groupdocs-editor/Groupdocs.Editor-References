---
title: "WordProcessingFormats"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιλαμβάνει όλες τις μορφές WordProcessing."
type: docs
weight: 17
url: /el/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις μορφές WordProcessing. Περιλαμβάνει τους ακόλουθους τύπους αρχείων:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Μάθετε περισσότερα για τις μορφές επεξεργασίας κειμένου [εδώ](../https://wiki.fileformat.com/word-processing).

Οι κωδικοί MIME λαμβάνονται από τις δοθείσες πηγές:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 Binary File Format (DOC) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. |
|
|  | [Dot](#Dot) | MS Word 97-2007 Template (DOT) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο με τη δυνατότητα εκτέλεσης μακροεντολών. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) αντιπροσωπεύει αρχεία προτύπων που δημιουργούνται με το Microsoft Word 2007 ή νεότερο. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. |
|
|  | [Odt](#Odt) | Open Document Format Text Document (ODT) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text. |
|
|  | [Ott](#Ott) | Open Document Format Text Document Template (OTT) αντιπροσωπεύει έγγραφα προτύπων που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο OpenDocument του OASIS. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Format — WordProcessingML ή WordML (.XML). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια επαναληπτική συλλογή όλων των [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 Binary File Format (DOC) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML Macro-Free Document (DOCX) είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 Template (DOT) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML Macro-Enabled Document (DOCM) είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο με τη δυνατότητα εκτέλεσης μακροεντολών.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML Macro-Free Template (DOTX) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML Macro-Enabled Template (DOTM) αντιπροσωπεύει αρχεία προτύπων που δημιουργούνται με το Microsoft Word 2007 ή νεότερο.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format Text Document (ODT) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Text Document Template (OTT) αντιπροσωπεύει έγγραφα προτύπων που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο OpenDocument του OASIS.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Format — WordProcessingML ή WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Λαμβάνει μια επαναληπτική συλλογή όλων των [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Τιμή: Ένα  IEnumerable{WordProcessingFormats}  που περιέχει όλες τις παρουσίες του [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Ανακτά μια παρουσία του καθορισμένου τύπου [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | java.lang.String | Η κατάληξη αρχείου για μετατροπή. Εάν η κατάληξη περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.


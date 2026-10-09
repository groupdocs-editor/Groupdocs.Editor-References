---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση του εγγράφου σε όλες τις υποστηριζόμενες μορφές e-Book, ePub, MOBI και AZW3."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση του εγγράφου σε όλες τις υποστηριζόμενες μορφές e-Book: ePub, MOBI και AZW3.

<br />

*** ** * ** ***

Υποστηριζόμενες μορφές e-Book:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Ηλεκτρονική Δημοσίευση)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Μορφή Kindle 8t)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του EbookSaveOptions με μορφή εξόδου ePub (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Δημιουργεί μια νέα παρουσία του [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) με το καθορισμένο υποχρεωτικό μορφότυπο εξόδου e-Book, ενώ όλες οι άλλες παράμετροι είναι προεπιλεγμένες |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Καθορίζει το μέγιστο επίπεδο επικεφαλίδων στο οποίο θα διαχωριστεί το αρχείο e-Book. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Καθορίζει το μέγιστο επίπεδο επικεφαλίδων στο οποίο θα διαχωριστεί το αρχείο e-Book. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Καθορίζει εάν θα εξαχθούν οι ενσωματωμένες και προσαρμοσμένες ιδιότητες του εγγράφου στο τελικό αρχείο. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Καθορίζει εάν θα εξαχθούν οι ενσωματωμένες και προσαρμοσμένες ιδιότητες του εγγράφου στο τελικό αρχείο. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Καθορίζει τη μορφή του τελικού αρχείου e-Book: IDPF ePub, MOBI ή AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Καθορίζει τη μορφή του τελικού αρχείου e-Book: IDPF ePub, MOBI ή AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του EbookSaveOptions με μορφή εξόδου ePub (μπορεί να τροποποιηθεί στη συνέχεια μέσω
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Δημιουργεί μια νέα παρουσία του [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) με το καθορισμένο υποχρεωτικό μορφότυπο εξόδου e-Book, ενώ όλες οι άλλες παράμετροι είναι προεπιλεγμένες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | υποχρεωτική μορφή εξόδου, στην οποία πρέπει να αποθηκευτεί το e-Book |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Καθορίζει το μέγιστο επίπεδο επικεφαλίδων στο οποίο θα διαχωριστεί το αρχείο e-Book. Η προεπιλεγμένη τιμή είναι
2
.
Ορίζοντάς το σε
0
θα απενεργοποιήσει το διαχωρισμό, έτσι όλο το περιεχόμενο του e-Book θα ενσωματωθεί σε ένα ενιαίο πακέτο μέσα στο τελικό αρχείο.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε τιμή από 1 έως 9, το έγγραφο θα διαχωριστεί σε παραγράφους μορφοποιημένες με χρήση

**Heading 1**
,
**Heading 2**
,
**Heading 3**
κτλ. στυλ μέχρι το καθορισμένο επίπεδο επικεφαλίδας.

Από προεπιλογή, μόνο
**Heading 1**
και
**Heading 2**
οι παράγραφοι προκαλούν το διαχωρισμό του εγγράφου.
Ο καθορισμός αυτής της ιδιότητας στο μηδέν (ή σε τιμή μικρότερη του μηδενός) θα εμποδίσει εντελώς το διαχωρισμό του εγγράφου σε παραγράφους τίτλου.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Καθορίζει το μέγιστο επίπεδο επικεφαλίδων στο οποίο θα διαχωριστεί το αρχείο e-Book. Η προεπιλεγμένη τιμή είναι
2
.
Ορίζοντάς το σε
0
θα απενεργοποιήσει το διαχωρισμό, έτσι όλο το περιεχόμενο του e-Book θα ενσωματωθεί σε ένα ενιαίο πακέτο μέσα στο τελικό αρχείο.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε τιμή από 1 έως 9, το έγγραφο θα διαχωριστεί σε παραγράφους μορφοποιημένες με χρήση

**Heading 1**
,
**Heading 2**
,
**Heading 3**
κτλ. στυλ μέχρι το καθορισμένο επίπεδο επικεφαλίδας.

Από προεπιλογή, μόνο
**Heading 1**
και
**Heading 2**
οι παράγραφοι προκαλούν το διαχωρισμό του εγγράφου.
Ο καθορισμός αυτής της ιδιότητας στο μηδέν (ή σε τιμή μικρότερη του μηδενός) θα εμποδίσει εντελώς το διαχωρισμό του εγγράφου σε παραγράφους τίτλου.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Καθορίζει εάν θα εξαχθούν οι ενσωματωμένες και προσαρμοσμένες ιδιότητες του εγγράφου στο τελικό αρχείο.
Η προεπιλεγμένη τιμή είναι
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Καθορίζει εάν θα εξαχθούν οι ενσωματωμένες και προσαρμοσμένες ιδιότητες του εγγράφου στο τελικό αρχείο.
Η προεπιλεγμένη τιμή είναι
false
.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Καθορίζει τη μορφή του τελικού αρχείου e-Book: IDPF ePub, MOBI ή AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Καθορίζει τη μορφή του τελικού αρχείου e-Book: IDPF ePub, MOBI ή AZW3.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |


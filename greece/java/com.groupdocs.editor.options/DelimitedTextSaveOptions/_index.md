---
title: "DelimitedTextSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιέχει επιλογές για τη δημιουργία και αποθήκευση εγγράφων Spreadsheet κειμένου, όπως CSV, Tab‑based κ.λπ., που χρησιμοποιούν ένα διαχωριστικό."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Περιέχει επιλογές για τη δημιουργία και αποθήκευση εγγράφων Spreadsheet βασισμένων σε κείμενο
(CSV, Tab‑based κ.λπ.), που χρησιμοποιούν έναν διαχωριστικό (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί ένα νέο αντικείμενο του DelimitedTextSaveOptions με προεπιλεγμένο διαχωριστικό το ; (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
Διαχωριστικό
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) ιδιότητα)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Δημιουργεί μια παρουσία της κλάσης επιλογών για κείμενο με διαχωριστικά με υποχρεωτικό |
διαχωριστικό (delimiter)
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κειμενικά |
Έγγραφα Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κειμενικά |
Έγγραφα Spreadsheet
|
|  | [getEncoding()](#getEncoding--) | Επιτρέπει τον ορισμό κωδικοποίησης για το έγγραφο Spreadsheet βασισμένο σε κείμενο. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Επιτρέπει τον ορισμό κωδικοποίησης για το έγγραφο Spreadsheet βασισμένο σε κείμενο. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Δείχνει εάν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως |
όπως κάνει το MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Δείχνει εάν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως |
όπως κάνει το MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Δείχνει εάν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Δείχνει εάν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί ένα νέο αντικείμενο του DelimitedTextSaveOptions με προεπιλεγμένο διαχωριστικό το ; (μπορεί να τροποποιηθεί στη συνέχεια μέσω
Διαχωριστικό
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) ιδιότητα)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Δημιουργεί μια παρουσία της κλάσης επιλογών για κείμενο με διαχωριστικά με υποχρεωτικό
διαχωριστικό (delimiter)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | διαχωριστικό | java.lang.String | Διαχωριστικό τύπου String (delimiter) για έγγραφα Spreadsheet βασισμένα σε κείμενο |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κειμενικά
Έγγραφα Spreadsheet


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κειμενικά
Έγγραφα Spreadsheet


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Επιτρέπει τον ορισμό κωδικοποίησης για το έγγραφο Spreadsheet βασισμένο σε κείμενο. Από
προεπιλογή (και αν δεν καθοριστεί) είναι UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Επιτρέπει τον ορισμό κωδικοποίησης για το έγγραφο Spreadsheet βασισμένο σε κείμενο. Από
προεπιλογή (και αν δεν καθοριστεί) είναι UTF8.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Δείχνει εάν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως
όπως κάνει το MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Δείχνει εάν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως
όπως κάνει το MS Excel


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Δείχνει εάν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. Προεπιλογή
η τιμή είναι false, που σημαίνει ότι το περιεχόμενο για την κενή γραμμή θα είναι κενό.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Δείχνει εάν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. Προεπιλογή
η τιμή είναι false, που σημαίνει ότι το περιεχόμενο για την κενή γραμμή θα είναι κενό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


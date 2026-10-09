---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιέχει επιλογές για τη δημιουργία και αποθήκευση εγγράφων λογιστικού φύλλου κειμένου (CSV, Tab‑based κ.λπ.) που χρησιμοποιούν διαχωριστικό."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Περιέχει επιλογές για τη δημιουργία και αποθήκευση εγγράφων λογιστικού φύλλου κειμένου
(CSV, Tab‑based κ.λπ.), που χρησιμοποιούν διαχωριστικό (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του DelimitedTextSaveOptions με προεπιλεγμένο διαχωριστικό ερωτηματικό (;) (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
Διαχωριστικό
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Δημιουργεί μια παρουσία της κλάσης επιλογών για διαχωρισμένο κείμενο με υποχρεωτικό |
διαχωριστικό (delimiter)
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κείμενο-βασισμένο |
Έγγραφα λογιστικού φύλλου
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κείμενο-βασισμένο |
Έγγραφα λογιστικού φύλλου
|
|  | [getEncoding()](#getEncoding--) | Επιτρέπει τον ορισμό μιας κωδικοποίησης για το κείμενο-βασισμένο έγγραφο λογιστικού φύλλου. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Επιτρέπει τον ορισμό μιας κωδικοποίησης για το κείμενο-βασισμένο έγγραφο λογιστικού φύλλου. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Δείχνει αν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως |
αυτό που κάνει το MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Δείχνει αν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως |
αυτό που κάνει το MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Δείχνει αν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Δείχνει αν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του DelimitedTextSaveOptions με προεπιλεγμένο διαχωριστικό ερωτηματικό (;) (μπορεί να τροποποιηθεί στη συνέχεια μέσω
Διαχωριστικό
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Δημιουργεί μια παρουσία της κλάσης επιλογών για διαχωρισμένο κείμενο με υποχρεωτικό
διαχωριστικό (delimiter)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | διαχωριστικό | java.lang.String | Διαχωριστικό συμβολοσειράς (delimiter) για κείμενο-βασισμένα έγγραφα λογιστικού φύλλου |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κείμενο-βασισμένο
Έγγραφα λογιστικού φύλλου


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κείμενο-βασισμένο
Έγγραφα λογιστικού φύλλου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Επιτρέπει τον ορισμό μιας κωδικοποίησης για το κείμενο-βασισμένο έγγραφο λογιστικού φύλλου. Από
η προεπιλογή (και αν δεν καθοριστεί) είναι UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Επιτρέπει τον ορισμό μιας κωδικοποίησης για το κείμενο-βασισμένο έγγραφο λογιστικού φύλλου. Από
η προεπιλογή (και αν δεν καθοριστεί) είναι UTF8.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Δείχνει αν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως
αυτό που κάνει το MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Δείχνει αν οι αρχικές κενές γραμμές και στήλες πρέπει να περικοπούν όπως
αυτό που κάνει το MS Excel


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Δείχνει αν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. Προεπιλογή
η τιμή είναι false που σημαίνει ότι το περιεχόμενο για κενή γραμμή θα είναι κενό.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Δείχνει αν τα διαχωριστικά πρέπει να εμφανίζονται για κενή γραμμή. Προεπιλογή
η τιμή είναι false που σημαίνει ότι το περιεχόμενο για κενή γραμμή θα είναι κενό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


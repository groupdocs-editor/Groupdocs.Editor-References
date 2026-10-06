---
title: "DelimitedTextEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιλογές για τη φόρτωση εγγράφων Spreadsheet κειμένου CSV Tab-based κ.λπ. που χρησιμοποιούν διαχωριστικό"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Επιλογές για τη φόρτωση εγγράφων Spreadsheet κειμένου (CSV, Tab-based κ.λπ.),
που χρησιμοποιούν διαχωριστικό (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Δημιουργεί μια παρουσία της κλάσης επιλογών για κείμενο με διαχωριστικά με υποχρεωτικό |
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
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά |
το έγγραφο μετατρέπεται σε δεδομένα ημερομηνίας.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά |
το έγγραφο μετατρέπεται σε δεδομένα ημερομηνίας.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά |
το έγγραφο μετατρέπεται σε αριθμητικά δεδομένα.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά |
το έγγραφο μετατρέπεται σε αριθμητικά δεδομένα.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Ορίζει εάν τα διαδοχικά διαχωριστικά πρέπει να αντιμετωπίζονται ως ένα. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Ορίζει εάν τα διαδοχικά διαχωριστικά πρέπει να αντιμετωπίζονται ως ένα. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου, |
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου, |
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Δημιουργεί μια παρουσία της κλάσης επιλογών για κείμενο με διαχωριστικά με υποχρεωτικό
διαχωριστικό (delimiter)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | διαχωριστικό | java.lang.String | Υποχρεωτικό διαχωριστικό (delimiter), που δεν μπορεί να είναι NULL ή κενό |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Επιτρέπει τον καθορισμό ενός διαχωριστικού συμβολοσειράς (delimiter) για κειμενικά
Έγγραφα Spreadsheet


**Returns:**
java.lang.String
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

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά
Το έγγραφο μετατρέπεται σε δεδομένα ημερομηνίας. Η προεπιλογή είναι ψευδής.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά
Το έγγραφο μετατρέπεται σε δεδομένα ημερομηνίας. Η προεπιλογή είναι ψευδής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά
Το έγγραφο μετατρέπεται σε αριθμητικά δεδομένα. Η προεπιλογή είναι ψευδής.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η συμβολοσειρά σε κειμενικά
Το έγγραφο μετατρέπεται σε αριθμητικά δεδομένα. Η προεπιλογή είναι ψευδής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Ορίζει αν τα διαδοχικά διαχωριστικά πρέπει να αντιμετωπίζονται ως ένα. Από
Η προεπιλογή είναι ψευδής.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Ορίζει αν τα διαδοχικά διαχωριστικά πρέπει να αντιμετωπίζονται ως ένα. Από
Η προεπιλογή είναι ψευδής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου,
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης. Χρήσιμο όταν επεξεργάζεστε τεράστια έγγραφα και
αντιμετωπίζοντας OutOfMemoryException. Η προεπιλογή είναι ψευδής (η βελτιστοποίηση μνήμης είναι
απενεργοποιημένο για καλύτερη απόδοση).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου,
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης. Χρήσιμο όταν επεξεργάζεστε τεράστια έγγραφα και
αντιμετωπίζοντας OutOfMemoryException. Η προεπιλογή είναι ψευδής (η βελτιστοποίηση μνήμης είναι
απενεργοποιημένο για καλύτερη απόδοση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


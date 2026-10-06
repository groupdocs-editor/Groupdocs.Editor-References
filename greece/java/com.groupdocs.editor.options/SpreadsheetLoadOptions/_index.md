---
title: "SpreadsheetLoadOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιέχει επιλογές για τη φόρτωση δυαδικών εγγράφων Spreadsheet Cells συμβατών με Excel, όπως XLSX, ODS κ.ά."
type: docs
weight: 36
url: /el/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Περιέχει επιλογές για τη φόρτωση δυαδικού Spreadsheet (Cells, συμβατό με Excel)
έγγραφα όπως XLS(X), ODS κ.ά. στην κλάση Editor

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Προεπιλεγμένος κατασκευαστής χωρίς παραμέτρους - όλες οι παράμετροι έχουν προεπιλεγμένες τιμές |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
το άνοιγμα του εγγράφου Spreadsheet, εάν είναι κωδικοποιημένο.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
το άνοιγμα του εγγράφου Spreadsheet, εάν είναι κωδικοποιημένο.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου, |
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εισερχόμενου εγγράφου, |
που μπορεί να μειώσει την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη
χειροκίνητη μείωση χρήσης μνήμης.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Προεπιλεγμένος κατασκευαστής χωρίς παραμέτρους - όλες οι παράμετροι έχουν προεπιλεγμένες τιμές


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
Άνοιγμα του εγγράφου Spreadsheet, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για να μην χρησιμοποιηθεί ο κωδικός πρόσβασης (προεπιλεγμένη τιμή).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
Άνοιγμα του εγγράφου Spreadsheet, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για να μην χρησιμοποιηθεί ο κωδικός πρόσβασης (προεπιλεγμένη τιμή).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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


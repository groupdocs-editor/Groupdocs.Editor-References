---
title: "TextSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων απλού κειμένου TXT"
type: docs
weight: 41
url: /el/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση απλού κειμένου (TXT)
έγγραφα

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
αποθήκευση
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
αποθήκευση
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Καθορίζει αν θα προστεθούν διπλής κατεύθυνσης σημεία πριν από κάθε εκτέλεση BiDi όταν |
εξάγεται σε μορφή απλού κειμένου.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Καθορίζει αν θα προστεθούν διπλής κατεύθυνσης σημεία πριν από κάθε εκτέλεση BiDi όταν |
εξάγεται σε μορφή απλού κειμένου
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Καθορίζει αν το πρόγραμμα πρέπει να προσπαθήσει να διατηρήσει τη διάταξη των πινάκων |
κατά την αποθήκευση σε μορφή απλού κειμένου.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Καθορίζει αν το πρόγραμμα πρέπει να προσπαθήσει να διατηρήσει τη διάταξη των πινάκων |
κατά την αποθήκευση σε μορφή απλού κειμένου.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
αποθήκευση


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
αποθήκευση


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Καθορίζει αν θα προστεθούν διπλής κατεύθυνσης σημεία πριν από κάθε εκτέλεση BiDi όταν
εξάγεται σε μορφή απλού κειμένου. Η προεπιλογή είναι 'false' \\u2014 να μην προστεθούν σημεία BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Καθορίζει αν θα προστεθούν διπλής κατεύθυνσης σημεία πριν από κάθε εκτέλεση BiDi όταν
εξάγεται σε μορφή απλού κειμένου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Καθορίζει αν το πρόγραμμα πρέπει να προσπαθήσει να διατηρήσει τη διάταξη των πινάκων
κατά την αποθήκευση σε μορφή απλού κειμένου. Η προεπιλεγμένη τιμή είναι false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Καθορίζει αν το πρόγραμμα πρέπει να προσπαθήσει να διατηρήσει τη διάταξη των πινάκων
κατά την αποθήκευση σε μορφή απλού κειμένου. Η προεπιλεγμένη τιμή είναι false.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


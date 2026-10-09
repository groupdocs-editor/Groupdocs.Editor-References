---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων μορφών Spreadsheet συμβατών με Excel"
type: docs
weight: 35
url: /el/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων
Μορφές Spreadsheet (συμβατές με Excel)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Επιτρέπει τον καθορισμό του δείκτη 0‑βάσης του φύλλου εργασίας (καρτέλας) της εισόδου |
Έγγραφο Spreadsheet, το οποίο πρέπει να μετατραπεί σε HTML (δείτε
σχόλια).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Επιτρέπει τον καθορισμό του δείκτη 0‑βάσης του φύλλου εργασίας (καρτέλας) της εισόδου |
Έγγραφο Spreadsheet, το οποίο πρέπει να μετατραπεί σε HTML (δείτε
σχόλια).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Επιτρέπει την εξαίρεση κρυφών φύλλων εργασίας στο εισερχόμενο έγγραφο Spreadsheet, έτσι |
θα αγνοηθούν εντελώς.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Επιτρέπει την εξαίρεση κρυφών φύλλων εργασίας στο εισερχόμενο έγγραφο Spreadsheet, έτσι |
θα αγνοηθούν εντελώς.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Όταν είναι ενεργοποιημένο, τα κενά οριζόντια γειτονικά κελιά από το εισερχόμενο έγγραφο Spreadsheet θα είναι |
αναπαριστάμενα σε επεξεργάσιμο έγγραφο HTML ως συγχωνευμένα σε ένα μόνο κελί με το αντίστοιχο
χαρακτηριστικό colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Όταν είναι ενεργοποιημένο, ο πίνακας HTML στο παραγόμενο έγγραφο HTML περιέχει μια κενή κρυφή γραμμή στο κάτω μέρος με |
μηδενικό ύψος και κενά κελιά, όπου έχει οριστεί μόνο το πλάτος.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Επιτρέπει τον καθορισμό του δείκτη 0‑βάσης του φύλλου εργασίας (καρτέλας) της εισόδου
Έγγραφο Spreadsheet, το οποίο πρέπει να μετατραπεί σε HTML (δείτε
σχόλια).


*** ** * ** ***

Τα περισσότερα έγγραφα Spreadsheet υποστηρίζουν την έννοια των καρτελών, δηλαδή μπορούν να είναι πολλαπλών καρτελών. Από την άλλη πλευρά, η μορφή HTML δεν υποστηρίζει τέτοια δομή. Για το λόγο αυτό το GroupDocs.Editor μπορεί να μετατρέψει σε HTML μόνο μία συγκεκριμένη καρτέλα του εισερχόμενου εγγράφου, και αυτή η επιλογή επιτρέπει τον καθορισμό της. Ο δείκτης καρτέλας είναι 0‑βάσης, οι αρνητικές τιμές απαγορεύονται. Εάν ο καθορισμένος δείκτης υπερβαίνει τον αριθμό όλων των καρτελών, θα προκληθεί εξαίρεση. Εάν το εισερχόμενο έγγραφο Spreadsheet περιέχει μόνο μία καρτέλα, αυτή η επιλογή θα αγνοηθεί. Η προεπιλεγμένη τιμή είναι 0 (πρώτη καρτέλα).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Επιτρέπει τον καθορισμό του δείκτη 0‑βάσης του φύλλου εργασίας (καρτέλας) της εισόδου
Έγγραφο Spreadsheet, το οποίο πρέπει να μετατραπεί σε HTML (δείτε
σχόλια).


*** ** * ** ***

Τα περισσότερα έγγραφα Spreadsheet υποστηρίζουν την έννοια των καρτελών, δηλαδή μπορούν να είναι πολλαπλών καρτελών. Από την άλλη πλευρά, η μορφή HTML δεν υποστηρίζει τέτοια δομή. Για το λόγο αυτό το GroupDocs.Editor μπορεί να μετατρέψει σε HTML μόνο μία συγκεκριμένη καρτέλα του εισερχόμενου εγγράφου, και αυτή η επιλογή επιτρέπει τον καθορισμό της. Ο δείκτης καρτέλας είναι 0‑βάσης, οι αρνητικές τιμές απαγορεύονται. Εάν ο καθορισμένος δείκτης υπερβαίνει τον αριθμό όλων των καρτελών, θα προκληθεί εξαίρεση. Εάν το εισερχόμενο έγγραφο Spreadsheet περιέχει μόνο μία καρτέλα, αυτή η επιλογή θα αγνοηθεί. Η προεπιλεγμένη τιμή είναι 0 (πρώτη καρτέλα).

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Επιτρέπει την εξαίρεση κρυφών φύλλων εργασίας στο εισερχόμενο έγγραφο Spreadsheet, έτσι
θα αγνοηθούν εντελώς. Η προεπιλογή είναι false - τα κρυφά φύλλα εργασίας είναι
διαθέσιμα και επεξεργάζονται κανονικά.


*** ** * ** ***

Διάφορα δυαδικά φορμά Spreadsheet (όπως το XLSX) υποστηρίζουν την έννοια των κρυφών φύλλων εργασίας (καρτελών). Έγγραφο τέτοιου φορμά, εάν έχει περισσότερα από ένα φύλλα εργασίας, μπορεί να περιέχει επιπλέον κρυφά φύλλα. Από προεπιλογή, αυτά τα κρυφά φύλλα είναι διαθέσιμα για επεξεργασία, αλλά με αυτήν την επιλογή είναι δυνατόν να αγνοηθούν, σαν να λείπουν και δεν υπάρχουν. Όταν αυτή η επιλογή είναι ενεργοποιημένη, δεν μπορείτε να επιλέξετε κρυφό φύλλο εργασίας με την ιδιότητα ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Επιτρέπει την εξαίρεση κρυφών φύλλων εργασίας στο εισερχόμενο έγγραφο Spreadsheet, έτσι
θα αγνοηθούν εντελώς. Η προεπιλογή είναι false - τα κρυφά φύλλα εργασίας είναι
διαθέσιμα και επεξεργάζονται κανονικά.


*** ** * ** ***

Διάφορα δυαδικά φορμά Spreadsheet (όπως το XLSX) υποστηρίζουν την έννοια των κρυφών φύλλων εργασίας (καρτελών). Έγγραφο τέτοιου φορμά, εάν έχει περισσότερα από ένα φύλλα εργασίας, μπορεί να περιέχει επιπλέον κρυφά φύλλα. Από προεπιλογή, αυτά τα κρυφά φύλλα είναι διαθέσιμα για επεξεργασία, αλλά με αυτήν την επιλογή είναι δυνατόν να αγνοηθούν, σαν να λείπουν και δεν υπάρχουν. Όταν αυτή η επιλογή είναι ενεργοποιημένη, δεν μπορείτε να επιλέξετε κρυφό φύλλο εργασίας με την ιδιότητα ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Όταν είναι ενεργοποιημένο, τα κενά οριζόντια γειτονικά κελιά από το εισερχόμενο έγγραφο Spreadsheet θα είναι
αναπαριστάμενα σε επεξεργάσιμο έγγραφο HTML ως συγχωνευμένα σε ένα μόνο κελί με το αντίστοιχο
χαρακτηριστικό colspan. Από προεπιλογή είναι απενεργοποιημένο (false).


Από προεπιλογή το GroupDocs.Editor μετατρέπει έναν πίνακα από το εισερχόμενο έγγραφο Spreadsheet στην έξοδο
εγγράφου HTML διατηρώντας κάθε κελί. Ωστόσο, τα έγγραφα Spreadsheet μπορεί να είναι αραιά \\u2014 είναι
μπορεί να περιέχουν τεράστιο αριθμό "empty areas", όπου πολλά κελιά είναι κενά. Αυτή η επιλογή, όταν
είναι ενεργοποιημένη, συγχωνεύει τέτοια κενά κελιά σε ένα με χαρακτηριστικό colspan στο στοιχείο TD,
και έτσι μπορεί να μειώσει σημαντικά το μέγεθος του παραγόμενου κώδικα HTML.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Όταν είναι ενεργοποιημένο, ο πίνακας HTML στο παραγόμενο έγγραφο HTML περιέχει μια κενή κρυφή γραμμή στο κάτω μέρος με
μηδενικό ύψος και κενά κελιά, όπου έχει οριστεί μόνο το πλάτος. Αυτή η γραμμή με κενά κελιά περιέχει
ακριβείς τιμές πλάτους για κάθε στήλη και βελτιώνει την αντίστροφη μετατροπή από HTML σε Φύλλο Εργασίας. Με
η προεπιλογή είναι ενεργοποιημένη (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


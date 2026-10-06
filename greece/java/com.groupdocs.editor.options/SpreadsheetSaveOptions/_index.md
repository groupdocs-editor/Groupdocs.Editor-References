---
title: "SpreadsheetSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων Spreadsheet συμβατών με Excel"
type: docs
weight: 37
url: /el/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση του Spreadsheet
(συμβατών με Excel) έγγραφα

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του SpreadsheetSaveOptions με μορφή εξόδου XLSX (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) ιδιότητα)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Δημιουργεί μια νέα παρουσία του SpreadsheetSaveOptions με το υποχρεωτικό καθορισμένο |
Μορφή εξόδου Spreadsheet, ενώ όλες οι άλλες παράμετροι είναι προεπιλεγμένες
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι |
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου Spreadsheet, εάν αυτή η μορφή εγγράφου
υποστηρίζει προστασία με κωδικό.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι |
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου Spreadsheet, εάν αυτή η μορφή εγγράφου
υποστηρίζει προστασία με κωδικό.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Επιτρέπει την εισαγωγή επεξεργασμένου φύλλου εργασίας σε αντίγραφο υπάρχοντος spreadsheet |
αντί για τη δημιουργία νέου spreadsheet με ένα μόνο φύλλο (προεπιλογή
συμπεριφορά).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Επιτρέπει την εισαγωγή επεξεργασμένου φύλλου εργασίας σε αντίγραφο υπάρχοντος spreadsheet |
αντί για τη δημιουργία νέου spreadsheet με ένα μόνο φύλλο (προεπιλογή
συμπεριφορά).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Λογική σημαία, η οποία καθορίζει εάν το επεξεργασμένο φύλλο εργασίας πρέπει να αντικαταστήσει το |
υπάρχον φύλλο εργασίας στο αρχικό spreadsheet στη θέση που καθορίζεται από
το

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
ιδιότητα, ή θα πρέπει να ενσωματωθεί μεταξύ του υπάρχοντος φύλλου εργασίας και
του προηγούμενου, χωρίς να αντικαταστήσει το περιεχόμενό του.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Λογική σημαία, η οποία καθορίζει εάν το επεξεργασμένο φύλλο εργασίας πρέπει να αντικαταστήσει το |
υπάρχον φύλλο εργασίας στο αρχικό spreadsheet στη θέση που καθορίζεται από
το

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
ιδιότητα, ή θα πρέπει να ενσωματωθεί μεταξύ του υπάρχοντος φύλλου εργασίας και
του προηγούμενου, χωρίς να αντικαταστήσει το περιεχόμενό του.
|
|  | [getOutputFormat()](#getOutputFormat--) | Επιτρέπει τον καθορισμό μορφής Spreadsheet, η οποία θα χρησιμοποιηθεί για την αποθήκευση του |
έγγραφο
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Επιτρέπει τον καθορισμό μορφής Spreadsheet, η οποία θα χρησιμοποιηθεί για την αποθήκευση του |
έγγραφο
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Επιτρέπει την ενεργοποίηση προστασίας φύλλου εργασίας για το εξαγόμενο Spreadsheet |
εγγράφου.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Επιτρέπει την ενεργοποίηση προστασίας φύλλου εργασίας για το εξαγόμενο Spreadsheet |
εγγράφου.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς φύλλων εργασίας που ξεκινούν από 1, οι οποίοι πρέπει να διαγραφούν από το spreadsheet κατά την αποθήκευση, σε περίπτωση που το επεξεργασμένο φύλλο εργασίας εισαχθεί σε υπάρχον spreadsheet. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς φύλλων εργασίας που ξεκινούν από 1, οι οποίοι πρέπει να διαγραφούν από το spreadsheet κατά την αποθήκευση, σε περίπτωση που το επεξεργασμένο φύλλο εργασίας εισαχθεί σε υπάρχον spreadsheet. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του SpreadsheetSaveOptions με μορφή εξόδου XLSX (μπορεί να τροποποιηθεί στη συνέχεια μέσω
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) ιδιότητα)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Δημιουργεί μια νέα παρουσία του SpreadsheetSaveOptions με το υποχρεωτικό καθορισμένο
Μορφή εξόδου Spreadsheet, ενώ όλες οι άλλες παράμετροι είναι προεπιλεγμένες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Υποχρεωτική μορφή εξόδου, στην οποία θα πρέπει να αποθηκευτεί το έγγραφο Spreadsheet |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου Spreadsheet, εάν αυτή η μορφή εγγράφου
υποστηρίζει προστασία με κωδικό πρόσβασης. Καθορίστε NULL ή κενή συμβολοσειρά για αφαίρεση
(καθαρισμός) του κωδικού πρόσβασης.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου Spreadsheet, εάν αυτή η μορφή εγγράφου
υποστηρίζει προστασία με κωδικό πρόσβασης. Καθορίστε NULL ή κενή συμβολοσειρά για αφαίρεση
(καθαρισμός) του κωδικού πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Επιτρέπει την εισαγωγή επεξεργασμένου φύλλου εργασίας σε αντίγραφο υπάρχοντος spreadsheet
αντί για τη δημιουργία νέου spreadsheet με ένα μόνο φύλλο (προεπιλογή
συμπεριφορά). WorksheetNumber είναι ένας αριθμός 1‑βάσης ενός φύλλου εργασίας στο
υπολογιστικό φύλλο, φορτωμένο στην κλάση Editor. Εάν είναι 0 (προεπιλεγμένη τιμή), το
το νέο υπολογιστικό φύλλο θα δημιουργηθεί με ένα μόνο επεξεργασμένο φύλλο εργασίας. Εάν είναι
μεγαλύτερο ή μικρότερο από το μηδέν, και υπάρχει έγκυρο υπολογιστικό φύλλο, φορτωμένο στο
την κλάση Editor, το επεξεργασμένο φύλλο εργασίας, το οποίο αντιπροσωπεύεται από την είσοδο
την παρουσία EditableDocument, θα εισαχθεί σε αυτό το υπολογιστικό φύλλο.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Επιτρέπει την εισαγωγή επεξεργασμένου φύλλου εργασίας σε αντίγραφο υπάρχοντος spreadsheet
αντί για τη δημιουργία νέου spreadsheet με ένα μόνο φύλλο (προεπιλογή
συμπεριφορά). WorksheetNumber είναι ένας αριθμός 1‑βάσης ενός φύλλου εργασίας στο
υπολογιστικό φύλλο, φορτωμένο στην κλάση Editor. Εάν είναι 0 (προεπιλεγμένη τιμή), το
το νέο υπολογιστικό φύλλο θα δημιουργηθεί με ένα μόνο επεξεργασμένο φύλλο εργασίας. Εάν είναι
μεγαλύτερο ή μικρότερο από το μηδέν, και υπάρχει έγκυρο υπολογιστικό φύλλο, φορτωμένο στο
την κλάση Editor, το επεξεργασμένο φύλλο εργασίας, το οποίο αντιπροσωπεύεται από την είσοδο
την παρουσία EditableDocument, θα εισαχθεί σε αυτό το υπολογιστικό φύλλο.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Λογική σημαία, η οποία καθορίζει εάν το επεξεργασμένο φύλλο εργασίας πρέπει να αντικαταστήσει το
υπάρχον φύλλο εργασίας στο αρχικό spreadsheet στη θέση που καθορίζεται από
το

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
ιδιότητα, ή θα πρέπει να ενσωματωθεί μεταξύ του υπάρχοντος φύλλου εργασίας και
προηγούμενο, χωρίς αντικατάσταση του περιεχομένου του. Από προεπιλογή είναι false \\u2014
το υπάρχον φύλλο εργασίας θα αντικατασταθεί. Αυτή η ιδιότητα αγνοείται, εάν η τιμή
του

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
της ιδιότητας ορίζεται σε '0'.


*** ** * ** ***

Από προεπιλογή το φύλλο εργασίας αντικαθίσταται. Αυτό σημαίνει ότι εάν το δεδομένο υπολογιστικό φύλλο έχει 5 φύλλα εργασίας, και WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, τότε το 4ο φύλλο εργασίας θα αντικατασταθεί με το νέο επεξεργασμένο φύλλο εργασίας, ενώ ο συνολικός αριθμός φύλλων εργασίας στο υπολογιστικό φύλλο (5) θα παραμείνει αμετάβλητος. Ωστόσο, εάν η τιμή αυτής της ιδιότητας οριστεί σε  *true* , το νέο επεξεργασμένο φύλλο εργασίας θα ενσωματωθεί ως 4ο φύλλο εργασίας, και όλα τα επόμενα φύλλα εργασίας θα μετακινηθούν στο τέλος: \"old\" το 4ο φύλλο εργασίας γίνεται 5ο, και το 5ο γίνεται 6ο, και ο συνολικός αριθμός φύλλων εργασίας στο υπολογιστικό φύλλο θα αυξηθεί κατά ένα και θα είναι ίσος με 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Λογική σημαία, η οποία καθορίζει εάν το επεξεργασμένο φύλλο εργασίας πρέπει να αντικαταστήσει το
υπάρχον φύλλο εργασίας στο αρχικό spreadsheet στη θέση που καθορίζεται από
το

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
ιδιότητα, ή θα πρέπει να ενσωματωθεί μεταξύ του υπάρχοντος φύλλου εργασίας και
προηγούμενο, χωρίς αντικατάσταση του περιεχομένου του. Από προεπιλογή είναι false \\u2014
το υπάρχον φύλλο εργασίας θα αντικατασταθεί. Αυτή η ιδιότητα αγνοείται, εάν η τιμή
του

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
της ιδιότητας ορίζεται σε '0'.


*** ** * ** ***

Από προεπιλογή το φύλλο εργασίας αντικαθίσταται. Αυτό σημαίνει ότι εάν το δεδομένο υπολογιστικό φύλλο έχει 5 φύλλα εργασίας, και WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, τότε το 4ο φύλλο εργασίας θα αντικατασταθεί με το νέο επεξεργασμένο φύλλο εργασίας, ενώ ο συνολικός αριθμός φύλλων εργασίας στο υπολογιστικό φύλλο (5) θα παραμείνει αμετάβλητος. Ωστόσο, εάν η τιμή αυτής της ιδιότητας οριστεί σε  *true* , το νέο επεξεργασμένο φύλλο εργασίας θα ενσωματωθεί ως 4ο φύλλο εργασίας, και όλα τα επόμενα φύλλα εργασίας θα μετακινηθούν στο τέλος: \"old\" το 4ο φύλλο εργασίας γίνεται 5ο, και το 5ο γίνεται 6ο, και ο συνολικός αριθμός φύλλων εργασίας στο υπολογιστικό φύλλο θα αυξηθεί κατά ένα και θα είναι ίσος με 6.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Επιτρέπει τον καθορισμό μορφής Spreadsheet, η οποία θα χρησιμοποιηθεί για την αποθήκευση του
έγγραφο


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Επιτρέπει τον καθορισμό μορφής Spreadsheet, η οποία θα χρησιμοποιηθεί για την αποθήκευση του
έγγραφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Επιτρέπει την ενεργοποίηση προστασίας φύλλου εργασίας για το εξαγόμενο Spreadsheet
έγγραφο. Από προεπιλογή είναι NULL - η προστασία δεν εφαρμόζεται. Δεν υποστηρίζονται όλα τα μορφότυπα
υποστηρίζουν προστασία φύλλου εργασίας.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Επιτρέπει την ενεργοποίηση προστασίας φύλλου εργασίας για το εξαγόμενο Spreadsheet
έγγραφο. Από προεπιλογή είναι NULL - η προστασία δεν εφαρμόζεται. Δεν υποστηρίζονται όλα τα μορφότυπα
υποστηρίζουν προστασία φύλλου εργασίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς 1‑βάσης φύλλων εργασίας που πρέπει να διαγραφούν από το υπολογιστικό φύλλο κατά την αποθήκευσή του, σε περίπτωση που το επεξεργασμένο φύλλο εργασίας εισαχθεί σε υπάρχον υπολογιστικό φύλλο. Όταν το επεξεργασμένο φύλλο εργασίας αποθηκευτεί όχι ως νέο υπολογιστικό φύλλο με ένα μόνο φύλλο (προεπιλεγμένη συμπεριφορά), αλλά αντίθετα αποθηκευτεί σε υπάρχον υπολογιστικό φύλλο (χρησιμοποιώντας #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), είναι επίσης δυνατό να διαγραφούν ορισμένα συγκεκριμένα φύλλα εργασίας από αυτό το υπολογιστικό φύλλο καθορίζοντας τους αριθμούς τους σε αυτόν τον πίνακα. Από προεπιλογή αυτός ο πίνακας είναι  null  \\u2014 δεν θα διαγραφούν φύλλα εργασίας. Ωστόσο, όταν αυτός ο πίνακας δεν είναι null και δεν είναι κενός, και περιέχει τουλάχιστον έναν έγκυρο αριθμό φύλλου εργασίας, μετά τη δημιουργία του εξαγόμενου εγγράφου υπολογιστικού φύλλου με το περιεχόμενο του επεξεργασμένου φύλλου, τα φύλλα εργασίας με τους καθορισμένους αριθμούς θα διαγραφούν από το υπολογιστικό φύλλο ακριβώς πριν από τη γραφή του περιεχομένου του στην έξοδο ροής ή αρχείο. Οι αριθμοί φύλλων εργασίας σε αυτόν τον πίνακα είναι 1‑βάσης, όχι 0‑βάσης. Οι μη έγκυροι αριθμοί (μικρότεροι από 1 ή μεγαλύτεροι από το συνολικό αριθμό φύλλων εργασίας) θα αγνοηθούν.


**Returns:**
int[] - Πίνακας αριθμών φύλλων εργασίας 1‑βάσης για διαγραφή, ή  null  εάν δεν πρέπει να διαγραφεί τίποτα.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Επιτρέπει τον καθορισμό ενός πίνακα με αριθμούς 1‑βάσης φύλλων εργασίας που πρέπει να διαγραφούν από το υπολογιστικό φύλλο κατά την αποθήκευσή του, σε περίπτωση που το επεξεργασμένο φύλλο εργασίας εισαχθεί σε υπάρχον υπολογιστικό φύλλο. Οι αριθμοί φύλλων εργασίας σε αυτόν τον πίνακα είναι 1‑βάσης. Οι μη έγκυροι αριθμοί θα αγνοηθούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Πίνακας αριθμών φύλλων εργασίας 1‑βάσης για διαγραφή (μπορεί να είναι  null  ή κενός). |
|


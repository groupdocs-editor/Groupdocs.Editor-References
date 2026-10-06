---
title: "MarkdownSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων Markdown"
type: docs
weight: 24
url: /el/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων Markdown

<br />

*** ** * ** ***

Η κλάση MarkdownSaveOptions πρέπει να εφαρμοστεί από τον χρήστη όταν υπάρχει μια παρουσία της κλάσης EditableDocument, η οποία περιέχει το περιεχόμενο ενός επεξεργασμένου εγγράφου, και απαιτείται η αποθήκευση αυτού του περιεχομένου στο νέο έγγραφο μορφής Markdown.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Το Allow καθορίζει πώς να ευθυγραμμιστούν τα περιεχόμενα σε πίνακες κατά την εξαγωγή σε μορφή Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Το Allow καθορίζει πώς να ευθυγραμμιστούν τα περιεχόμενα σε πίνακες κατά την εξαγωγή σε μορφή Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Καθορίζει το φυσικό φάκελο όπου αποθηκεύονται οι εικόνες κατά την εξαγωγή ενός εγγράφου σε |
τη μορφή Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Καθορίζει το φυσικό φάκελο όπου αποθηκεύονται οι εικόνες κατά την εξαγωγή ενός εγγράφου σε |
τη μορφή Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Καθορίζει εάν οι εικόνες αποθηκεύονται σε μορφή Base64 στο αρχείο εξόδου. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Καθορίζει εάν οι εικόνες αποθηκεύονται σε μορφή Base64 στο αρχείο εξόδου. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ορισμός αυτής της επιλογής σε
)
μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης κατά τη δημιουργία μεγάλων εγγράφων με κόστος πιο αργού χρόνου αποθήκευσης.
Η προεπιλογή είναι
false
(η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για το σκοπό καλύτερης απόδοσης).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ορισμός αυτής της επιλογής σε
)
μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης κατά τη δημιουργία μεγάλων εγγράφων με κόστος πιο αργού χρόνου αποθήκευσης.
Η προεπιλογή είναι
false
(η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για το σκοπό καλύτερης απόδοσης).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Το Allow καθορίζει πώς να ευθυγραμμιστούν τα περιεχόμενα σε πίνακες κατά την εξαγωγή σε μορφή Markdown.
Η προεπιλεγμένη τιμή είναι [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Τιμή: Η ευθυγράμμιση του περιεχομένου του πίνακα


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Το Allow καθορίζει πώς να ευθυγραμμιστούν τα περιεχόμενα σε πίνακες κατά την εξαγωγή σε μορφή Markdown.
Η προεπιλεγμένη τιμή είναι [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Τιμή: Η ευθυγράμμιση του περιεχομένου του πίνακα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Καθορίζει το φυσικό φάκελο όπου αποθηκεύονται οι εικόνες κατά την εξαγωγή ενός εγγράφου σε
τη μορφή Markdown. Η προεπιλογή είναι null.

<br />

*** ** * ** ***

Εάν δεν καθοριστεί ούτε το ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ούτε το ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) από τον χρήστη, τότε το GroupDocs.Editor θα προσπαθήσει να προσδιορίσει το ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) από μόνο του και θα το εφαρμόσει εάν πετύχει

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Καθορίζει το φυσικό φάκελο όπου αποθηκεύονται οι εικόνες κατά την εξαγωγή ενός εγγράφου σε
τη μορφή Markdown. Η προεπιλογή είναι null.

<br />

*** ** * ** ***

Εάν δεν καθοριστεί ούτε το ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ούτε το ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) από τον χρήστη, τότε το GroupDocs.Editor θα προσπαθήσει να προσδιορίσει το ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) από μόνο του και θα το εφαρμόσει εάν πετύχει

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Καθορίζει εάν οι εικόνες αποθηκεύονται σε μορφή Base64 στο αρχείο εξόδου. Η προεπιλογή είναι
false
.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε  true , τα δεδομένα εικόνων εξάγονται απευθείας στα στοιχεία εικόνας ![](../) και δεν δημιουργούνται ξεχωριστά αρχεία. Αυτή η ιδιότητα, εάν οριστεί σε  true , έχει υψηλότερη προτεραιότητα από την ιδιότητα MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Καθορίζει εάν οι εικόνες αποθηκεύονται σε μορφή Base64 στο αρχείο εξόδου. Η προεπιλογή είναι
false
.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε  true , τα δεδομένα εικόνων εξάγονται απευθείας στα στοιχεία εικόνας ![](../) και δεν δημιουργούνται ξεχωριστά αρχεία. Αυτή η ιδιότητα, εάν οριστεί σε  true , έχει υψηλότερη προτεραιότητα από την ιδιότητα MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


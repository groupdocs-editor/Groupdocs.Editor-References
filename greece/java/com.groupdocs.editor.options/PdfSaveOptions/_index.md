---
title: "PdfSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων PDF Portable Document Format"
type: docs
weight: 31
url: /el/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση PDF (Portable
Document Format) έγγραφα

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Κωδικός πρόσβασης, ο οποίος θα εφαρμοστεί στο παραγόμενο έγγραφο PDF ως κωδικός χρήστη, απαιτείται για το άνοιγμα. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Κωδικός πρόσβασης, ο οποίος θα εφαρμοστεί στο παραγόμενο έγγραφο PDF ως κωδικός χρήστη, απαιτείται για το άνοιγμα. |
|
|  | [getCompliance()](#getCompliance--) | Καθορίζει το επίπεδο συμμόρφωσης με τα πρότυπα PDF για τα έγγραφα εξόδου. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Καθορίζει το επίπεδο συμμόρφωσης με τα πρότυπα PDF για τα έγγραφα εξόδου. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο PDF, που χρησιμοποιούνται στο αρχικό έγγραφο. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο PDF, που χρησιμοποιούνται στο αρχικό έγγραφο. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Κωδικός πρόσβασης, ο οποίος θα εφαρμοστεί στο παραγόμενο έγγραφο PDF ως κωδικός χρήστη, απαιτείται για το άνοιγμα.
Εάν είναι NULL ή κενό, δεν θα εφαρμοστεί κωδικός στο έγγραφο. Διαφορετικά, το έγγραφο θα κρυπτογραφηθεί με RC4 (μήκος κλειδιού 128 bit).
Από προεπιλογή είναι NULL \u2014 δεν εφαρμόζεται κωδικός.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Κωδικός πρόσβασης, ο οποίος θα εφαρμοστεί στο παραγόμενο έγγραφο PDF ως κωδικός χρήστη, απαιτείται για το άνοιγμα.
Εάν είναι NULL ή κενό, δεν θα εφαρμοστεί κωδικός στο έγγραφο. Διαφορετικά, το έγγραφο θα κρυπτογραφηθεί με RC4 (μήκος κλειδιού 128 bit).
Από προεπιλογή είναι NULL \u2014 δεν εφαρμόζεται κωδικός.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Καθορίζει το επίπεδο συμμόρφωσης με τα πρότυπα PDF για τα έγγραφα εξόδου. Η προεπιλογή είναι PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Καθορίζει το επίπεδο συμμόρφωσης με τα πρότυπα PDF για τα έγγραφα εξόδου. Η προεπιλογή είναι PdfCompliance.Pdf17.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο PDF, που χρησιμοποιούνται στο αρχικό έγγραφο. Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο PDF, που χρησιμοποιούνται στο αρχικό έγγραφο. Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ο ορισμός αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης κατά τη δημιουργία μεγάλων εγγράφων, με κόστος τον πιο αργό χρόνο αποθήκευσης.
Η προεπιλογή είναι false (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για καλύτερη απόδοση).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ο ορισμός αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης κατά τη δημιουργία μεγάλων εγγράφων, με κόστος τον πιο αργό χρόνο αποθήκευσης.
Η προεπιλογή είναι false (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για καλύτερη απόδοση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


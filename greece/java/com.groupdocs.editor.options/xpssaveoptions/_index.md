---
title: "XpsSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων XPS XML Paper Specifications"
type: docs
weight: 54
url: /el/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων XPS (XML Paper Specifications).

<br />

*** ** * ** ***

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις προδιαγραφές XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή αρχείου PDF, αλλά χρησιμοποιεί XML στη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο XPS, οι οποίοι χρησιμοποιούνται στο αρχικό έγγραφο. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφου από HTML, κάτι που μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο τελικό έγγραφο XPS, οι οποίοι χρησιμοποιούνται στο αρχικό έγγραφο.
Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed).


**Returns:**
byte
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


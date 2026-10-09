---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων συμβατών με WordProcessing μετά την επεξεργασία τους"
type: docs
weight: 48
url: /el/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και την αποθήκευση
Έγγραφα συμβατά με το WordProcessing μετά την επεξεργασία τους


*** ** * ** ***

Το WordProcessingSaveOptions εφαρμόζεται σε περιπτώσεις όπου υπάρχει μια παρουσία της κλάσης EditableDocument, η οποία περιέχει το περιεχόμενο ενός επεξεργασμένου εγγράφου, και απαιτείται η αποθήκευση αυτού του περιεχομένου σε νέο έγγραφο μορφής WordProcessing.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του WordProcessingSaveOptions με μορφή εξόδου DOCX (μπορεί να τροποποιηθεί στη συνέχεια μέσω |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) ιδιότητα)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Δημιουργεί μια νέα παρουσία του WordProcessingSaveOptions με καθορισμένο |
υποχρεωτική μορφή εξόδου WordProcessing, ενώ όλες οι άλλες παράμετροι είναι
προεπιλογή
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του |
έγγραφο.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του |
έγγραφο.
|
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι |
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι |
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing.
|
|  | [getOutputFormat()](#getOutputFormat--) | Επιτρέπει τον καθορισμό μιας μορφής WordProcessing, η οποία θα χρησιμοποιηθεί για την αποθήκευση |
του εγγράφου
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Επιτρέπει τον καθορισμό μιας μορφής WordProcessing, η οποία θα χρησιμοποιηθεί για την αποθήκευση |
του εγγράφου
|
|  | [getLocale()](#getLocale--) | Επιτρέπει τον ορισμό παράκαμψης της προεπιλεγμένης τοπικής ρύθμισης (γλώσσας) για το WordProcessing |
έγγραφο, το οποίο θα εφαρμοστεί κατά τη δημιουργία του.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Επιτρέπει τον ορισμό παράκαμψης της προεπιλεγμένης τοπικής ρύθμισης (γλώσσας) για το WordProcessing |
έγγραφο, το οποίο θα εφαρμοστεί κατά τη δημιουργία του.
|
|  | [getLocaleBi()](#getLocaleBi--) | Επιτρέπει τον ορισμό παράκαμψης της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing |
για το κείμενο RTL (από δεξιά προς αριστερά), το οποίο θα εφαρμοστεί κατά τη
δημιουργία.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Επιτρέπει τον ορισμό παράκαμψης της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing |
για το κείμενο RTL (από δεξιά προς αριστερά), το οποίο θα εφαρμοστεί κατά τη
δημιουργία.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing |
για το κείμενο Ανατολικής Ασίας, το οποίο θα εφαρμοστεί κατά τη δημιουργία του.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing |
για το κείμενο Ανατολικής Ασίας, το οποίο θα εφαρμοστεί κατά τη δημιουργία του.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από |
HTML, το οποίο μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από |
HTML, το οποίο μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
|
|  | [getProtection()](#getProtection--) | Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφου για το |
έγγραφο WordProcessing οποιασδήποτε μορφής, το οποίο υποστηρίζει
προστασία.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφου για το |
έγγραφο WordProcessing οποιασδήποτε μορφής, το οποίο υποστηρίζει
προστασία.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο εξαγόμενο WordProcessing |
έγγραφο.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο εξαγόμενο WordProcessing |
έγγραφο.
|
|  | [deepClone()](#deepClone--) | Δημιουργεί και επιστρέφει ένα πλήρες αντίγραφο αυτού του στιγμιότυπου του |
WordProcessingSaveOptions κλάση
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Αυτός ο κατασκευαστής χωρίς παραμέτρους δημιουργεί μια νέα παρουσία του WordProcessingSaveOptions με μορφή εξόδου DOCX (μπορεί να τροποποιηθεί στη συνέχεια μέσω
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) ιδιότητα)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Δημιουργεί μια νέα παρουσία του WordProcessingSaveOptions με καθορισμένο
υποχρεωτική μορφή εξόδου WordProcessing, ενώ όλες οι άλλες παράμετροι είναι
προεπιλογή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Υποχρεωτική μορφή εξόδου, στην οποία το έγγραφο WordProcessing πρέπει να αποθηκευτεί |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του
έγγραφο. Εάν το αρχικό έγγραφο ανοίχθηκε και επεξεργάστηκε σε σελιδοποίηση
λειτουργία, αυτή η επιλογή επίσης πρέπει να ενεργοποιηθεί. Από προεπιλογή είναι απενεργοποιημένη.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης που θα χρησιμοποιηθεί για την αποθήκευση του
έγγραφο. Εάν το αρχικό έγγραφο ανοίχθηκε και επεξεργάστηκε σε σελιδοποίηση
λειτουργία, αυτή η επιλογή επίσης πρέπει να ενεργοποιηθεί. Από προεπιλογή είναι απενεργοποιημένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing. Καθορίστε NULL ή
κενή συμβολοσειρά για την αφαίρεση (καθαρισμό) του κωδικού πρόσβασης.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση, την απόκτηση ή την αφαίρεση κωδικού πρόσβασης, ο οποίος θα είναι
χρησιμοποιείται για την κωδικοποίηση του παραγόμενου εγγράφου WordProcessing. Καθορίστε NULL ή
κενή συμβολοσειρά για την αφαίρεση (καθαρισμό) του κωδικού πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Επιτρέπει τον καθορισμό μιας μορφής WordProcessing, η οποία θα χρησιμοποιηθεί για την αποθήκευση
του εγγράφου


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Επιτρέπει τον καθορισμό μιας μορφής WordProcessing, η οποία θα χρησιμοποιηθεί για την αποθήκευση
του εγγράφου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Επιτρέπει τον ορισμό παράκαμψης της προεπιλεγμένης τοπικής ρύθμισης (γλώσσας) για το WordProcessing
έγγραφο, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν δεν είναι
καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή
επιλέξει) τη γλώσσα του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις ή άλλες
παράγοντες.


*** ** * ** ***

Αυτή η επιλογή εφαρμόζει εξαναγκαστικά τη συγκεκριμένη γλώσσα σε όλο το κείμενο του εγγράφου. Μην τη χρησιμοποιείτε εάν το έγγραφο περιέχει διαφορετικά τμήματα κειμένου που είναι γραμμένα σε διαφορετικές γλώσσες.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Επιτρέπει τον ορισμό παράκαμψης της προεπιλεγμένης τοπικής ρύθμισης (γλώσσας) για το WordProcessing
έγγραφο, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν δεν είναι
καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει (ή
επιλέξει) τη γλώσσα του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις ή άλλες
παράγοντες.

*** ** * ** ***


Αυτή η επιλογή εφαρμόζει εξαναγκαστικά τη συγκεκριμένη γλώσσα σε όλο το κείμενο σε
το έγγραφο. Μην τη χρησιμοποιείτε, εάν το έγγραφο περιέχει διαφορετικά τμήματα
κείμενο, που είναι γραμμένο σε διαφορετικές γλώσσες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Επιτρέπει τον ορισμό παράκαμψης της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing
για το κείμενο RTL (από δεξιά προς αριστερά), το οποίο θα εφαρμοστεί κατά τη
δημιουργία. Όταν δεν είναι καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο
πρόγραμμα) θα εντοπίσει (ή επιλέξει) τη γλώσσα RTL του εγγράφου σύμφωνα με τις
δικές του ρυθμίσεις ή άλλους παράγοντες.

*** ** * ** ***


Αυτή η επιλογή εφαρμόζει εξαναγκαστικά τη συγκεκριμένη γλώσσα σε όλο το κείμενο RTL
στο έγγραφο. Μην τη χρησιμοποιείτε, εάν το έγγραφο περιέχει διαφορετικά τμήματα
κείμενο, που είναι γραμμένο σε διαφορετικές γλώσσες.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Επιτρέπει τον ορισμό παράκαμψης της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing
για το κείμενο RTL (από δεξιά προς αριστερά), το οποίο θα εφαρμοστεί κατά τη
δημιουργία. Όταν δεν είναι καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο
πρόγραμμα) θα εντοπίσει (ή επιλέξει) τη γλώσσα RTL του εγγράφου σύμφωνα με τις
δικές του ρυθμίσεις ή άλλους παράγοντες.

*** ** * ** ***


Αυτή η επιλογή εφαρμόζει εξαναγκαστικά τη συγκεκριμένη γλώσσα σε όλο το κείμενο RTL
στο έγγραφο. Μην τη χρησιμοποιείτε, εάν το έγγραφο περιέχει διαφορετικά τμήματα
κείμενο, που είναι γραμμένο σε διαφορετικές γλώσσες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing
για το κείμενο Ανατολικής Ασίας, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν
δεν είναι καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει
(ή επιλέξει) τη γλώσσα Ανατολικής Ασίας του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις
ή άλλοι παράγοντες.

*** ** * ** ***


Αυτή η επιλογή εφαρμόζει εξαναγκαστικά την καθορισμένη τοπική ρύθμιση συνολικά
Κείμενο Ανατολικής Ασίας στο έγγραφο. Μην το χρησιμοποιήσετε, εάν το έγγραφο περιέχει
διαφορετικά τμήματα κειμένου, που είναι γραμμένα σε διαφορετικές
γλώσσες.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Επιτρέπει την παράκαμψη της τοπικής ρύθμισης (γλώσσας) για το έγγραφο WordProcessing
για το κείμενο Ανατολικής Ασίας, το οποίο θα εφαρμοστεί κατά τη δημιουργία του. Όταν
δεν είναι καθορισμένο (προεπιλεγμένη τιμή), το MS Word (ή άλλο πρόγραμμα) θα εντοπίσει
(ή επιλέξει) τη γλώσσα Ανατολικής Ασίας του εγγράφου σύμφωνα με τις δικές του ρυθμίσεις
ή άλλοι παράγοντες.

*** ** * ** ***


Αυτή η επιλογή εφαρμόζει εξαναγκαστικά την καθορισμένη τοπική ρύθμιση συνολικά
Κείμενο Ανατολικής Ασίας στο έγγραφο. Μην το χρησιμοποιήσετε, εάν το έγγραφο περιέχει
διαφορετικά τμήματα κειμένου, που είναι γραμμένα σε διαφορετικές
γλώσσες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από
HTML, το οποίο μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ο ορισμός αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης
κατά τη δημιουργία μεγάλων εγγράφων με κόστος πιο αργού χρόνου αποθήκευσης.
Η προεπιλογή είναι false (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για το καλό της
απόδοσης).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά τη δημιουργία εγγράφων από
HTML, το οποίο μειώνει την απόδοση ως κόστος της μείωσης της χρήσης μνήμης.
Ο ορισμός αυτής της επιλογής σε true μπορεί να μειώσει σημαντικά την κατανάλωση μνήμης
κατά τη δημιουργία μεγάλων εγγράφων με κόστος πιο αργού χρόνου αποθήκευσης.
Η προεπιλογή είναι false (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για το καλό της
απόδοσης).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφου για το
έγγραφο WordProcessing οποιασδήποτε μορφής, το οποίο υποστηρίζει
προστασία. Από προεπιλογή είναι NULL - η προστασία εγγράφου δεν θα χρησιμοποιηθεί.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Επιτρέπει τον έλεγχο και την εφαρμογή των επιλογών προστασίας εγγράφου για το
έγγραφο WordProcessing οποιασδήποτε μορφής, το οποίο υποστηρίζει
προστασία. Από προεπιλογή είναι NULL - η προστασία εγγράφου δεν θα χρησιμοποιηθεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο εξαγόμενο WordProcessing
εγγράφου. Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Υπεύθυνο για την ενσωμάτωση πόρων γραμματοσειρών στο εξαγόμενο WordProcessing
εγγράφου. Από προεπιλογή δεν ενσωματώνει καμία γραμματοσειρά (NotEmbed).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Δημιουργεί και επιστρέφει ένα πλήρες αντίγραφο αυτού του στιγμιότυπου του
WordProcessingSaveOptions κλάση


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance


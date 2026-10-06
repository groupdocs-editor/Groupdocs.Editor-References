---
title: "TextEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση απλών κειμένων TXT εγγράφων"
type: docs
weight: 39
url: /el/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων απλού κειμένου (TXT).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
άνοιγμα
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
άνοιγμα
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης στοιχείων αριθμημένης λίστας όταν το έγγραφο είναι |
εισαγόμενο από απλό κειμενικό μορφότυπο.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης στοιχείων αριθμημένης λίστας όταν το έγγραφο είναι |
εισαγόμενο από απλό κειμενικό μορφότυπο.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού κενού. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού κενού. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού κενού. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού κενού. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [getDirection()](#getDirection--) | Επιτρέπει τον καθορισμό της κατεύθυνσης ροής κειμένου στην εισαγόμενη απλή κειμενική |
εγγράφου.
|
|  | [setDirection(int value)](#setDirection-int-) | Επιτρέπει τον καθορισμό της κατεύθυνσης ροής κειμένου στην εισαγόμενη απλή κειμενική |
εγγράφου.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
άνοιγμα


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
άνοιγμα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης στοιχείων αριθμημένης λίστας όταν το έγγραφο είναι
εισαγόμενη από απλό κειμενικό μορφότυπο. Η προεπιλεγμένη τιμή είναι true.


*** ** * ** ***

Εάν αυτή η επιλογή οριστεί σε false, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λίστας, όταν οι αριθμοί λίστας τελειώνουν είτε με τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως "\\u2022", "\*", "-" ή "o"). Εάν αυτή η επιλογή οριστεί σε true, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας: ο αλγόριθμος αναγνώρισης λιστών για αριθμητική στυλ Αραβικών (1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και την τελεία (".") σύμβολα.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης στοιχείων αριθμημένης λίστας όταν το έγγραφο είναι
εισαγόμενη από απλό κειμενικό μορφότυπο. Η προεπιλεγμένη τιμή είναι true.


*** ** * ** ***

Εάν αυτή η επιλογή οριστεί σε false, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λίστας, όταν οι αριθμοί λίστας τελειώνουν είτε με τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως "\\u2022", "\*", "-" ή "o"). Εάν αυτή η επιλογή οριστεί σε true, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας: ο αλγόριθμος αναγνώρισης λιστών για αριθμητική στυλ Αραβικών (1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και την τελεία (".") σύμβολα.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού κενού. Από προεπιλογή
μετατρέπει τα αρχικά κενά σε αριστερή εσοχή.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης αρχικού κενού. Από προεπιλογή
μετατρέπει τα αρχικά κενά σε αριστερή εσοχή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού κενού. Από προεπιλογή
περικοπεί όλα τα τελικά κενά.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Λαμβάνει ή ορίζει την προτιμώμενη επιλογή διαχείρισης τελικού κενού. Από προεπιλογή
περικοπεί όλα τα τελικά κενά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. Από
η προεπιλογή είναι απενεργοποιημένη (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. Από
η προεπιλογή είναι απενεργοποιημένη (false).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Επιτρέπει τον καθορισμό της κατεύθυνσης ροής κειμένου στην εισαγόμενη απλή κειμενική
έγγραφο. Από προεπιλογή είναι από αριστερά προς δεξιά.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Επιτρέπει τον καθορισμό της κατεύθυνσης ροής κειμένου στην εισαγόμενη απλή κειμενική
έγγραφο. Από προεπιλογή είναι από αριστερά προς δεξιά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |


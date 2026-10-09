---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει επιλογές προστασίας φύλλου εργασίας που επιτρέπουν την προστασία ενός φύλλου εργασίας στο τελικό έγγραφο Spreadsheet από τροποποίηση συγκεκριμένου τύπου με συγκεκριμένο κωδικό πρόσβασης."
type: docs
weight: 49
url: /el/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Περιλαμβάνει επιλογές προστασίας φύλλου εργασίας, που επιτρέπουν την προστασία ενός φύλλου εργασίας
στο τελικό έγγραφο Spreadsheet από τροποποίηση συγκεκριμένου τύπου με ένα
συγκεκριμένο κωδικό πρόσβασης.


*** ** * ** ***

Οι περισσότεροι τύποι Spreadsheet όπως το XLSX επιτρέπουν την προστασία ενός φύλλου εργασίας από επεξεργασία με κωδικό πρόσβασης. Αυτή η κλάση επιτρέπει την ενεργοποίηση τέτοιας προστασίας και τον καθορισμό των επιλογών της.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Δημιουργεί νέα παρουσία με προεπιλεγμένες παραμέτρους. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Δημιουργεί νέα παρουσία με συγκεκριμένο τύπο προστασίας φύλλου εργασίας και |
κωδικός πρόσβασης
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Επιτρέπει τον καθορισμό ενός τύπου προστασίας φύλλου εργασίας. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Επιτρέπει τον καθορισμό ενός τύπου προστασίας φύλλου εργασίας. |
|
|  | [getPassword()](#getPassword--) | Κωδικός πρόσβασης, που χρησιμοποιείται για την προστασία ενός φύλλου εργασίας. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Κωδικός πρόσβασης, που χρησιμοποιείται για την προστασία ενός φύλλου εργασίας. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Δημιουργεί νέα παρουσία με προεπιλεγμένες παραμέτρους. Εάν δεν τροποποιηθεί και περαστεί
στο SpreadsheetSaveOptions, δεν θα εφαρμοστεί προστασία φύλλου εργασίας


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Δημιουργεί νέα παρουσία με συγκεκριμένο τύπο προστασίας φύλλου εργασίας και
κωδικός πρόσβασης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | protectionType | int | Τύπος προστασίας φύλλου εργασίας |
|
|  | κωδικός πρόσβασης | java.lang.String | Κωδικός πρόσβασης, που κλειδώνει την προστασία |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Επιτρέπει τον καθορισμό ενός τύπου προστασίας φύλλου εργασίας. Από προεπιλογή είναι 'None' -
η προστασία δεν εφαρμόζεται.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Επιτρέπει τον καθορισμό ενός τύπου προστασίας φύλλου εργασίας. Από προεπιλογή είναι 'None' -
η προστασία δεν εφαρμόζεται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Κωδικός πρόσβασης, που χρησιμοποιείται για την προστασία ενός φύλλου εργασίας. Εάν είναι NULL ή κενό
string, η προστασία δεν θα εφαρμοστεί.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Κωδικός πρόσβασης, που χρησιμοποιείται για την προστασία ενός φύλλου εργασίας. Εάν είναι NULL ή κενό
string, η προστασία δεν θα εφαρμοστεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |


---
title: "FormFieldCollection"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μια συλλογή από πεδία φόρμας."
type: docs
weight: 15
url: /el/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Αναπαριστά μια συλλογή από πεδία φόρμας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Εισάγει ένα πεδίο φόρμας στη συλλογή. |
|
|  | [get(String name)](#get-java.lang.String-) | Αποκτά το πεδίο φόρμας με το καθορισμένο όνομα. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Αποκτά το πεδίο φόρμας με το καθορισμένο όνομα και τύπο. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Ένας απαριθμητής που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Εισάγει ένα πεδίο φόρμας στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Το πεδίο φόρμας προς εισαγωγή. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Αποκτά το πεδίο φόρμας με το καθορισμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του πεδίου φόρμας. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Αποκτά το πεδίο φόρμας με το καθορισμένο όνομα και τύπο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του πεδίου φόρμας. |


T
: Ο τύπος του πεδίου φόρμας.
|
| τύπος | java.lang.Class<T> |  |

**Returns:**
T - Το πεδίο φόρμας με το καθορισμένο όνομα και τύπο, εάν βρεθεί· διαφορετικά, η προεπιλεγμένη τιμή για τον τύπο.


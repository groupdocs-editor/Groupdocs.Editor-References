---
title: "InvalidFormField"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει την ενημέρωση των μη έγκυρων ονομάτων πεδίων φόρμας κατά τη διάρκεια της λειτουργίας FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /el/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Αντιπροσωπεύει την ενημέρωση των μη έγκυρων ονομάτων πεδίων φόρμας κατά τη διάρκεια του
FormFieldManager.FixInvalidFormFieldNames
λειτουργία.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) κλάσης με το καθορισμένο όνομα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Λαμβάνει το αρχικό όνομα του πεδίου φόρμας που δεν μπορεί να τροποποιηθεί εκτός |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Λαμβάνει ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Λαμβάνει ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) κλάσης με το καθορισμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το αρχικό όνομα του πεδίου φόρμας. |
|

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το αρχικό όνομα του πεδίου φόρμας που δεν μπορεί να τροποποιηθεί εκτός
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Λαμβάνει ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή.
Αυτό το όνομα αφαιρεί διπλότυπους μοναδικούς ταυτοποιητές με άλλα πεδία φόρμας και ορίζει ένα μοναδικό όνομα σελιδοδείκτη.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Λαμβάνει ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή.
Αυτό το όνομα αφαιρεί διπλότυπους μοναδικούς ταυτοποιητές με άλλα πεδία φόρμας και ορίζει ένα μοναδικό όνομα σελιδοδείκτη.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |


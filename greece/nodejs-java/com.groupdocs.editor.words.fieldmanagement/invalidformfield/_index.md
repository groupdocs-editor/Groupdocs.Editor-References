---
title: "InvalidFormField"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει την ενημέρωση των μη έγκυρων ονομάτων πεδίων φόρμας κατά τη διάρκεια της λειτουργίας FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Αντιπροσωπεύει την ενημέρωση των μη έγκυρων ονομάτων πεδίων φόρμας κατά τη διάρκεια του
FormFieldManager.FixInvalidFormFieldNames
λειτουργίας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) με το καθορισμένο όνομα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Αποκτά το αρχικό όνομα του πεδίου φόρμας που δεν μπορεί να τροποποιηθεί εκτός |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Αποκτά ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Αποκτά ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) με το καθορισμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Το αρχικό όνομα του πεδίου φόρμας. |
|

### getName() {#getName--}
```
public final String getName()
```


Αποκτά το αρχικό όνομα του πεδίου φόρμας που δεν μπορεί να τροποποιηθεί εκτός
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Αποκτά ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή.
Αυτό το όνομα αφαιρεί διπλότυπους μοναδικούς αναγνωριστικούς με άλλα πεδία φόρμας και ορίζει ένα μοναδικό όνομα σελιδοδείκτη.

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


Αποκτά ή ορίζει το νέο όνομα για το πεδίο φόρμας μετά την επισκευή.
Αυτό το όνομα αφαιρεί διπλότυπους μοναδικούς αναγνωριστικούς με άλλα πεδία φόρμας και ορίζει ένα μοναδικό όνομα σελιδοδείκτη.

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


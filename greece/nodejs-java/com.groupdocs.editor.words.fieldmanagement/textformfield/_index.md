---
title: "TextFormField"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει ένα πεδίο φόρμας που δέχεται κειμενική εισαγωγή."
type: docs
weight: 20
url: /el/nodejs-java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Αντιπροσωπεύει ένα πεδίο φόρμας που δέχεται κειμενική εισαγωγή.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) με το καθορισμένο φύλλο στυλ και όνομα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Λαμβάνει το φύλλο στυλ που εφαρμόζεται στο πεδίο φόρμας. |
|
|  | [getReadonly()](#getReadonly--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πεδίο φόρμας είναι μόνο για ανάγνωση. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πεδίο φόρμας είναι μόνο για ανάγνωση. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα του πεδίου φόρμας. |
|
|  | [getType()](#getType--) | Αποκτά τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.Text για αυτήν την κλάση. |
|
|  | [getLocaleId()](#getLocaleId--) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [getStatusText()](#getStatusText--) | Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, |
την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, |
την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.
|
|  | [getHelpText()](#getHelpText--) | Αποκτά ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, |
την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Αποκτά ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, |
την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.
|
|  | [getValue()](#getValue--) | Αποκτά ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την εισαγωγή κειμένου. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Αποκτά ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την εισαγωγή κειμένου. |
|
|  | [getMaxLength()](#getMaxLength--) | Αποκτά ή ορίζει το μέγιστο μήκος της εισόδου για το πεδίο φόρμας. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Αποκτά ή ορίζει το μέγιστο μήκος της εισόδου για το πεδίο φόρμας. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) με το καθορισμένο φύλλο στυλ και όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | φύλλο στυλ | java.lang.String | Το φύλλο στυλ που θα εφαρμοστεί στο πεδίο φόρμας. |
|
|  | name | java.lang.String | Το όνομα του πεδίου φόρμας. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Λαμβάνει το φύλλο στυλ που εφαρμόζεται στο πεδίο φόρμας.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πεδίο φόρμας είναι μόνο για ανάγνωση.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πεδίο φόρμας είναι μόνο για ανάγνωση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα του πεδίου φόρμας.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Αποκτά τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.Text για αυτήν την κλάση.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Η ιδιότητα LocaleId καθορίζει ένα αναγνωριστικό τοπικής ρύθμισης (LCID) που αντιστοιχεί σε συγκεκριμένο πολιτισμό ή περιοχή.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Η ιδιότητα LocaleId καθορίζει ένα αναγνωριστικό τοπικής ρύθμισης (LCID) που αντιστοιχεί σε συγκεκριμένο πολιτισμό ή περιοχή.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας,
την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

<br />

*** ** * ** ***

Εάν οριστεί σε  false , το κείμενο κατάστασης δεν θα εφαρμοστεί.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας,
την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

<br />

*** ** * ** ***

Εάν οριστεί σε  false , το κείμενο κατάστασης δεν θα εφαρμοστεί.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Αποκτά ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας,
την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.

<br />

*** ** * ** ***

Εάν οριστεί σε  false , το κείμενο βοήθειας δεν θα εφαρμοστεί.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Αποκτά ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας,
την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.

<br />

*** ** * ** ***

Εάν οριστεί σε  false , το κείμενο βοήθειας δεν θα εφαρμοστεί.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


Αποκτά ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την εισαγωγή κειμένου.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Αποκτά ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την εισαγωγή κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Αποκτά ή ορίζει το μέγιστο μήκος της εισόδου για το πεδίο φόρμας.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Αποκτά ή ορίζει το μέγιστο μήκος της εισόδου για το πεδίο φόρμας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |


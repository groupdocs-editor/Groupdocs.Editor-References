---
title: "DateFormField"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά ένα πεδίο φόρμας που εμφανίζει μια ημερομηνία."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.words.fieldmanagement/dateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DateFormField implements IFormField
```

Αναπαριστά ένα πεδίο φόρμας που εμφανίζει μια ημερομηνία.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DateFormField(String stylesheet, String name)](#DateFormField-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) με το καθορισμένο φύλλο στυλ και όνομα. |
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
|  | [getType()](#getType--) | Λαμβάνει τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.Date για αυτήν την κλάση. |
|
|  | [getLocaleId()](#getLocaleId--) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [getStatusText()](#getStatusText--) | Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση. |
|
|  | [getHelpText()](#getHelpText--) | Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν το πεδίο φόρμας έχει εστίαση και ο χρήστης πατάει F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν το πεδίο φόρμας έχει εστίαση και ο χρήστης πατάει F1. |
|
|  | [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει μια ημερομηνία. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει μια ημερομηνία. |
|
### DateFormField(String stylesheet, String name) {#DateFormField-java.lang.String-java.lang.String-}
```
public DateFormField(String stylesheet, String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) με το καθορισμένο φύλλο στυλ και όνομα.


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


Λαμβάνει τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.Date για αυτήν την κλάση.


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
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
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


Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

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


Αποκτά ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

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


Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν το πεδίο φόρμας έχει εστίαση και ο χρήστης πατάει F1.

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


Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν το πεδίο φόρμας έχει εστίαση και ο χρήστης πατάει F1.

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
public final Date getValue()
```


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει μια ημερομηνία.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει μια ημερομηνία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |


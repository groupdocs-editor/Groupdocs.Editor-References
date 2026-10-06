---
title: "CurrentDateFormField"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά ένα πεδίο φόρμας που εμφανίζει την τρέχουσα ημερομηνία."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.words.fieldmanagement/currentdateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CurrentDateFormField implements IFormField
```

Αναπαριστά ένα πεδίο φόρμας που εμφανίζει την τρέχουσα ημερομηνία.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CurrentDateFormField(String stylesheet, String name)](#CurrentDateFormField-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) κλάσης με το καθορισμένο φύλλο στυλ και όνομα. |
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
|  | [getType()](#getType--) | Λαμβάνει τον τύπο του πεδίου φόρμας, που είναι πάντα FormFieldType.CurrentDate για αυτήν την κλάση. |
|
|  | [getLocaleId()](#getLocaleId--) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Λαμβάνει ή ορίζει το αναγνωριστικό τοπικής ρύθμισης (locale ID) του πεδίου φόρμας, το οποίο αντιπροσωπεύει τον πολιτισμό ή τις περιφερειακές ρυθμίσεις που σχετίζονται με το πεδίο φόρμας. |
|
|  | [getStatusText()](#getStatusText--) | Λαμβάνει ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Λαμβάνει ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση. |
|
|  | [getHelpText()](#getHelpText--) | Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1. |
|
|  | [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την τρέχουσα ημερομηνία. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την τρέχουσα ημερομηνία. |
|
### CurrentDateFormField(String stylesheet, String name) {#CurrentDateFormField-java.lang.String-java.lang.String-}
```
public CurrentDateFormField(String stylesheet, String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) κλάσης με το καθορισμένο φύλλο στυλ και όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | φύλλο στυλ | java.lang.String | Το φύλλο στυλ που θα εφαρμοστεί στο πεδίο φόρμας. |
|
|  | όνομα | java.lang.String | Το όνομα του πεδίου φόρμας. |
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


Λαμβάνει τον τύπο του πεδίου φόρμας, που είναι πάντα FormFieldType.CurrentDate για αυτήν την κλάση.


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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Η ιδιότητα LocaleId καθορίζει έναν αναγνωριστικό τοπικής ρύθμισης (LCID) που αντιστοιχεί σε συγκεκριμένο πολιτισμό ή περιοχή.

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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Η ιδιότητα LocaleId καθορίζει έναν αναγνωριστικό τοπικής ρύθμισης (LCID) που αντιστοιχεί σε συγκεκριμένο πολιτισμό ή περιοχή.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Λαμβάνει ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

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


Λαμβάνει ή ορίζει το κείμενο κατάστασης που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται στη γραμμή κατάστασης όταν ένα πεδίο φόρμας έχει την εστίαση.

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


Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.

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


Λαμβάνει ή ορίζει το κείμενο βοήθειας που σχετίζεται με το πεδίο φόρμας, την πηγή του κειμένου που εμφανίζεται σε παράθυρο μηνύματος όταν ένα πεδίο φόρμας έχει την εστίαση και ο χρήστης πατάει F1.

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


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την τρέχουσα ημερομηνία.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει την τρέχουσα ημερομηνία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |


---
title: "DropDownFormField"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά ένα πεδίο φόρμας που εμφανίζει μια λίστα επιλογής."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Αναπαριστά ένα πεδίο φόρμας που εμφανίζει μια λίστα επιλογής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) με το καθορισμένο φύλλο στυλ και όνομα. |
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
|  | [getSelectedIndex()](#getSelectedIndex--) | Λαμβάνει ή ορίζει το δείκτη του επιλεγμένου στοιχείου στη λίστα drop-down. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Λαμβάνει ή ορίζει το δείκτη του επιλεγμένου στοιχείου στη λίστα drop-down. |
|
|  | [getType()](#getType--) | Λαμβάνει τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.DropDown για αυτήν την κλάση. |
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
|  | [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει τη λίστα επιλογών στη λίστα drop-down. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει τη λίστα επιλογών στη λίστα drop-down. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) με το καθορισμένο φύλλο στυλ και όνομα.


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
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Λαμβάνει ή ορίζει το δείκτη του επιλεγμένου στοιχείου στη λίστα drop-down.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Λαμβάνει ή ορίζει το δείκτη του επιλεγμένου στοιχείου στη λίστα drop-down.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getType() {#getType--}
```
public final int getType()
```


Λαμβάνει τον τύπο του πεδίου φόρμας, ο οποίος είναι πάντα FormFieldType.DropDown για αυτήν την κλάση.


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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
public final List<String> getValue()
```


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει τη λίστα επιλογών στη λίστα drop-down.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Λαμβάνει ή ορίζει την τιμή του πεδίου φόρμας, η οποία αντιπροσωπεύει τη λίστα επιλογών στη λίστα drop-down.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.String> |  |


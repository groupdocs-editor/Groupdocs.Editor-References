---
title: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων μορφών WordProcessing Words‑συμβατών, όπως DOCX, RTF, ODT κ.λπ."
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων"
type: docs
weight: 44
url: /el/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων
Μορφές WordProcessing (σύμφωνες με Words) όπως DOC(X), RTF, ODT κ.λπ.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Δημιουργεί και επιστρέφει ένα νέο στιγμιότυπο του WordProcessingEditOptions |
κλάση, όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές της
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Δημιουργεί και επιστρέφει ένα νέο στιγμιότυπο του WordProcessingEditOptions |
κλάση με καθορισμένη σελιδοποίηση και προεπιλογή όλων των άλλων επιλογών
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο σήμα HTML σε |
μια μορφή των HTML χαρακτηριστικών 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο σήμα HTML σε |
μια μορφή των HTML χαρακτηριστικών 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα εξαχθούν μόνο οι πόροι γραμματοσειράς που |
χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα εξαχθούν μόνο οι πόροι γραμματοσειράς που |
χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου.
|
|  | [getFontExtraction()](#getFontExtraction--) | Υπεύθυνο για την εξαγωγή πόρων γραμματοσειράς, που χρησιμοποιούνται στην είσοδο |
εγγράφου WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Υπεύθυνο για την εξαγωγή πόρων γραμματοσειράς, που χρησιμοποιούνται στην είσοδο |
εγγράφου WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Επιτρέπει τον καθορισμό ενός ονόματος κλάσης, το οποίο θα τοποθετηθεί στο 'class' |
χαρακτηριστικά σε κάθε στοιχείο HTML, που αντιπροσωπεύει κάποιο πεδίο στην είσοδο
εγγράφου WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Επιτρέπει τον καθορισμό ενός ονόματος κλάσης, το οποίο θα τοποθετηθεί στο 'class' |
χαρακτηριστικά σε κάθε στοιχείο HTML, που αντιπροσωπεύει κάποιο πεδίο στην είσοδο
εγγράφου WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Ελέγχει πού θα αποθηκευτούν τα δεδομένα στυλ και μορφοποίησης του εισερχόμενου εγγράφου WordProcessing: σε εξωτερικό φύλλο στυλ ( |
false
) ή ως ενσωματωμένα στυλ στο σήμα HTML (
)
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Ελέγχει πού θα αποθηκευτούν τα δεδομένα στυλ και μορφοποίησης του εισερχόμενου εγγράφου WordProcessing: σε εξωτερικό φύλλο στυλ ( |
false
) ή ως ενσωματωμένα στυλ στο σήμα HTML (
)
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Δημιουργεί και επιστρέφει ένα νέο στιγμιότυπο του WordProcessingEditOptions
κλάση, όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές της


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Δημιουργεί και επιστρέφει ένα νέο στιγμιότυπο του WordProcessingEditOptions
κλάση με καθορισμένη σελιδοποίηση και προεπιλογή όλων των άλλων επιλογών


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | enablePagination | boolean | Σημαία σελιδοποίησης, που ενεργοποιεί την έξοδο HTML, προσαρμοσμένη για λειτουργία σελίδων |
|

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

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο σήμα HTML σε
μια μορφή των HTML χαρακτηριστικών 'lang'. Αυτή η επιλογή μπορεί να είναι χρήσιμη για αναδρομική
μετατροπή των πολυγλωσσικών εγγράφων. Από προεπιλογή είναι απενεργοποιημένη
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο σήμα HTML σε
μια μορφή των HTML χαρακτηριστικών 'lang'. Αυτή η επιλογή μπορεί να είναι χρήσιμη για αναδρομική
μετατροπή των πολυγλωσσικών εγγράφων. Από προεπιλογή είναι απενεργοποιημένη
(false).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα εξαχθούν μόνο οι πόροι γραμματοσειράς που
χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου.
Τιμή:  true  εάν απαιτείται η εξαγωγή μόνο εκείνων των πόρων γραμματοσειράς που χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου· διαφορετικά,  false . Η προεπιλεγμένη τιμή είναι  false .


*** ** * ** ***

Δεν όλες οι γραμματοσειρές που χρησιμοποιούνται στο έγγραφο WordProcessing χρησιμοποιούνται άμεσα κατά 100% (εφαρμόζονται σε κάποιο κείμενο). Μπορεί να προκύψει κατάσταση όπου μια γραμματοσειρά αναφέρεται στο έγγραφο και ακόμη μπορεί να είναι ενσωματωμένη, αλλά δεν εφαρμόζεται σε κανένα τμήμα κειμένου. Για παράδειγμα, κάποια γραμματοσειρά μπορεί να είναι συνδεδεμένη με κάποιο στυλ, αλλά αυτό το στυλ δεν εφαρμόζεται σε κανένα μέρος του κειμένου. Αυτή η επιλογή ελέγχει πώς να επεξεργαστεί τέτοιες περιπτώσεις.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα εξαχθούν μόνο οι πόροι γραμματοσειράς που
χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου.
Τιμή:  true  εάν απαιτείται η εξαγωγή μόνο εκείνων των πόρων γραμματοσειράς που χρησιμοποιούνται στο κειμενικό περιεχόμενο του εγγράφου· διαφορετικά,  false . Η προεπιλεγμένη τιμή είναι  false .


*** ** * ** ***

Δεν όλες οι γραμματοσειρές που χρησιμοποιούνται στο έγγραφο WordProcessing χρησιμοποιούνται άμεσα κατά 100% (εφαρμόζονται σε κάποιο κείμενο). Μπορεί να προκύψει κατάσταση όπου μια γραμματοσειρά αναφέρεται στο έγγραφο και ακόμη μπορεί να είναι ενσωματωμένη, αλλά δεν εφαρμόζεται σε κανένα τμήμα κειμένου. Για παράδειγμα, κάποια γραμματοσειρά μπορεί να είναι συνδεδεμένη με κάποιο στυλ, αλλά αυτό το στυλ δεν εφαρμόζεται σε κανένα μέρος του κειμένου. Αυτή η επιλογή ελέγχει πώς να επεξεργαστεί τέτοιες περιπτώσεις.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Υπεύθυνο για την εξαγωγή πόρων γραμματοσειράς, που χρησιμοποιούνται στην είσοδο
Έγγραφο WordProcessing. Από προεπιλογή δεν εξάγει καμία γραμματοσειρά
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Υπεύθυνο για την εξαγωγή πόρων γραμματοσειράς, που χρησιμοποιούνται στην είσοδο
Έγγραφο WordProcessing. Από προεπιλογή δεν εξάγει καμία γραμματοσειρά
(NotExtract).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Επιτρέπει τον καθορισμό ενός ονόματος κλάσης, το οποίο θα τοποθετηθεί στο 'class'
χαρακτηριστικά σε κάθε στοιχείο HTML, που αντιπροσωπεύει κάποιο πεδίο στην είσοδο
Έγγραφο WordProcessing. Από προεπιλογή είναι NULL - τα χαρακτηριστικά 'class' δεν είναι
εφαρμοσμένο.


*** ** * ** ***

Σχεδόν όλες οι μορφές από την οικογένεια μορφών WordProcessing περιέχουν πεδία \\u2014 συγκεκριμένες οντότητες εγγράφου, που επιτρέπουν την απόκτηση δεδομένων εισόδου από τους χρήστες. Υπάρχει μεγάλη ποικιλία πεδίων: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers κ.λπ. Όλα αυτά μεταφράζονται στις πιο κατάλληλες δομές και στοιχεία HTML, διατηρώντας τα εισαχθέντα δεδομένα χρήστη, εάν υπάρχουν στο έγγραφο εισόδου. Σε συγκεκριμένες περιπτώσεις χρήσης απαιτείται μόνο η συλλογή των εισαχθέντων δεδομένων στην πλευρά του πελάτη αντί για την επεξεργασία ολόκληρου του περιεχομένου του εγγράφου. Για αυτήν την περίπτωση απαιτείται η ταυτοποίηση των ελέγχων εισόδου με κάποιον τρόπο για την ανάκτησή τους μαζί με τα δεδομένα τους στην πλευρά του πελάτη. Αυτή η ιδιότητα επιτρέπει τον καθορισμό ενός ονόματος κλάσης, που θα εφαρμόζεται σε κάθε έλεγχο εισόδου στο σήμα HTML, ώστε ο κώδικας πελάτη να μπορεί να περιηγηθεί στη δομή του εγγράφου HTML και να συλλέξει τα δεδομένα.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Επιτρέπει τον καθορισμό ενός ονόματος κλάσης, το οποίο θα τοποθετηθεί στο 'class'
χαρακτηριστικά σε κάθε στοιχείο HTML, που αντιπροσωπεύει κάποιο πεδίο στην είσοδο
Έγγραφο WordProcessing. Από προεπιλογή είναι NULL - τα χαρακτηριστικά 'class' δεν είναι
εφαρμοσμένο.


*** ** * ** ***

Σχεδόν όλες οι μορφές από την οικογένεια μορφών WordProcessing περιέχουν πεδία \\u2014 συγκεκριμένες οντότητες εγγράφου, που επιτρέπουν την απόκτηση δεδομένων εισόδου από τους χρήστες. Υπάρχει μεγάλη ποικιλία πεδίων: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers κ.λπ. Όλα αυτά μεταφράζονται στις πιο κατάλληλες δομές και στοιχεία HTML, διατηρώντας τα εισαχθέντα δεδομένα χρήστη, εάν υπάρχουν στο έγγραφο εισόδου. Σε συγκεκριμένες περιπτώσεις χρήσης απαιτείται μόνο η συλλογή των εισαχθέντων δεδομένων στην πλευρά του πελάτη αντί για την επεξεργασία ολόκληρου του περιεχομένου του εγγράφου. Για αυτήν την περίπτωση απαιτείται η ταυτοποίηση των ελέγχων εισόδου με κάποιον τρόπο για την ανάκτησή τους μαζί με τα δεδομένα τους στην πλευρά του πελάτη. Αυτή η ιδιότητα επιτρέπει τον καθορισμό ενός ονόματος κλάσης, που θα εφαρμόζεται σε κάθε έλεγχο εισόδου στο σήμα HTML, ώστε ο κώδικας πελάτη να μπορεί να περιηγηθεί στη δομή του εγγράφου HTML και να συλλέξει τα δεδομένα.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Ελέγχει πού θα αποθηκευτούν τα δεδομένα στυλ και μορφοποίησης του εισερχόμενου εγγράφου WordProcessing: σε εξωτερικό φύλλο στυλ (
false
) ή ως ενσωματωμένα στυλ στο σήμα HTML (
)
). Από προεπιλογή χρησιμοποιούνται εξωτερικά στυλ (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Ελέγχει πού θα αποθηκευτούν τα δεδομένα στυλ και μορφοποίησης του εισερχόμενου εγγράφου WordProcessing: σε εξωτερικό φύλλο στυλ (
false
) ή ως ενσωματωμένα στυλ στο σήμα HTML (
)
). Από προεπιλογή χρησιμοποιούνται εξωτερικά στυλ (
false
).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


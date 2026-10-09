---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση της MHTML MIME ενσωμάτωσης συγκεντρωτικών εγγράφων HTML"
type: docs
weight: 26
url: /el/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση των εγγράφων MHTML (MIME encapsulation of aggregate HTML documents)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Καθορίζει εάν θα χρησιμοποιηθούν CID (Content-ID) URLs για την αναφορά πόρων (εικόνες, γραμματοσειρές, CSS) που περιλαμβάνονται σε έγγραφα MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Καθορίζει εάν θα χρησιμοποιηθούν CID (Content-ID) URLs για την αναφορά πόρων (εικόνες, γραμματοσειρές, CSS) που περιλαμβάνονται σε έγγραφα MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Καθορίζει εάν θα εξαχθούν ενσωματωμένες και προσαρμοσμένες ιδιότητες εγγράφου σε MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Καθορίζει εάν θα εξαχθούν ενσωματωμένες και προσαρμοσμένες ιδιότητες εγγράφου σε MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Καθορίζει εάν οι πληροφορίες γλώσσας θα εξαχθούν σε MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Καθορίζει εάν οι πληροφορίες γλώσσας θα εξαχθούν σε MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Καθορίζει εάν θα χρησιμοποιηθούν CID (Content-ID) URLs για την αναφορά πόρων (εικόνες, γραμματοσειρές, CSS) που περιλαμβάνονται σε έγγραφα MHTML. Η προεπιλεγμένη τιμή είναι
false
.

<br />

*** ** * ** ***


Από προεπιλογή, οι πόροι σε έγγραφα MHTML αναφέρονται με το όνομα αρχείου (π.χ., "image.png"), το οποίο ταιριάζει με τις κεφαλίδες "Content-Location" των τμημάτων MIME. Αυτή η επιλογή ενεργοποιεί μια εναλλακτική μέθοδο, όπου οι αναφορές σε αρχεία πόρων γράφονται ως CID (Content-ID) URLs (π.χ., "cid:image.png") και ταιριάζουν με τις κεφαλίδες "Content-ID".


Σ θεωρία, δεν θα πρέπει να υπάρχει διαφορά μεταξύ των δύο μεθόδων αναφοράς και καμία από αυτές δεν θα πρέπει να παρουσιάζει προβλήματα σε οποιονδήποτε περιηγητή ή πρόγραμμα αλληλογραφίας. Στην πράξη, ωστόσο, ορισμένα προγράμματα αποτυγχάνουν να ανακτήσουν πόρους με βάση το όνομα αρχείου. Εάν ο περιηγητής ή το πρόγραμμα αλληλογραφίας σας αρνείται να φορτώσει πόρους που περιλαμβάνονται σε ένα έγγραφο MTHML (δεν εμφανίζει εικόνες ή δεν φορτώνει στυλ CSS), δοκιμάστε να εξάγετε το έγγραφο με CID URLs.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Καθορίζει εάν θα χρησιμοποιηθούν CID (Content-ID) URLs για την αναφορά πόρων (εικόνες, γραμματοσειρές, CSS) που περιλαμβάνονται σε έγγραφα MHTML. Η προεπιλεγμένη τιμή είναι
false
.

<br />

*** ** * ** ***


Από προεπιλογή, οι πόροι σε έγγραφα MHTML αναφέρονται με το όνομα αρχείου (π.χ., "image.png"), το οποίο ταιριάζει με τις κεφαλίδες "Content-Location" των τμημάτων MIME. Αυτή η επιλογή ενεργοποιεί μια εναλλακτική μέθοδο, όπου οι αναφορές σε αρχεία πόρων γράφονται ως CID (Content-ID) URLs (π.χ., "cid:image.png") και ταιριάζουν με τις κεφαλίδες "Content-ID".


Σ θεωρία, δεν θα πρέπει να υπάρχει διαφορά μεταξύ των δύο μεθόδων αναφοράς και καμία από αυτές δεν θα πρέπει να παρουσιάζει προβλήματα σε οποιονδήποτε περιηγητή ή πρόγραμμα αλληλογραφίας. Στην πράξη, ωστόσο, ορισμένα προγράμματα αποτυγχάνουν να ανακτήσουν πόρους με βάση το όνομα αρχείου. Εάν ο περιηγητής ή το πρόγραμμα αλληλογραφίας σας αρνείται να φορτώσει πόρους που περιλαμβάνονται σε ένα έγγραφο MTHML (δεν εμφανίζει εικόνες ή δεν φορτώνει στυλ CSS), δοκιμάστε να εξάγετε το έγγραφο με CID URLs.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Καθορίζει εάν θα εξαχθούν ενσωματωμένες και προσαρμοσμένες ιδιότητες εγγράφου σε MHTML. Η προεπιλεγμένη τιμή είναι
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Καθορίζει εάν θα εξαχθούν ενσωματωμένες και προσαρμοσμένες ιδιότητες εγγράφου σε MHTML. Η προεπιλεγμένη τιμή είναι
false
.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Καθορίζει εάν οι πληροφορίες γλώσσας θα εξαχθούν σε MHTML. Η προεπιλεγμένη τιμή είναι
false
.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε  true , το GroupDocs.Editor εκδίδει το χαρακτηριστικό HTML  lang  στα στοιχεία του εγγράφου που καθορίζουν τη γλώσσα. Αυτό μπορεί να χρειάζεται για τη διατήρηση της σημασιολογίας που σχετίζεται με τη γλώσσα.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Καθορίζει εάν οι πληροφορίες γλώσσας θα εξαχθούν σε MHTML. Η προεπιλεγμένη τιμή είναι
false
.

<br />

*** ** * ** ***

Όταν αυτή η ιδιότητα οριστεί σε  true , το GroupDocs.Editor εκδίδει το χαρακτηριστικό HTML  lang  στα στοιχεία του εγγράφου που καθορίζουν τη γλώσσα. Αυτό μπορεί να χρειάζεται για τη διατήρηση της σημασιολογίας που σχετίζεται με τη γλώσσα.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


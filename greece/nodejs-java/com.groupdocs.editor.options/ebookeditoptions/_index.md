---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό και την προσαρμογή προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων E-book σε όλες τις υποστηριζόμενες μορφές ePub, MOBI και AZW3."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό και την προσαρμογή προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων E-book σε όλες τις υποστηριζόμενες μορφές: ePub, MOBI και AZW3.

<br />

*** ** * ** ***

Υποστηριζόμενες μορφές e-Book:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Ηλεκτρονική Δημοσίευση)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Μορφή Kindle 8t)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές. |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) με καθορισμένη λειτουργία σελιδοποίησης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό HTML έγγραφο. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο HTML markup με τη μορφή χαρακτηριστικών 'lang' HTML. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο HTML markup με τη μορφή χαρακτηριστικών 'lang' HTML. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές.


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) με καθορισμένη λειτουργία σελιδοποίησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | enablePagination | boolean | Ενεργοποιεί ( true ) ή απενεργοποιεί ( false ) τη σελιδοποίηση του περιεχομένου του e-book στο τελικό έγγραφο HTML. Από προεπιλογή είναι απενεργοποιημένη ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό έγγραφο HTML. Από προεπιλογή είναι απενεργοποιημένη (
false
).

<br />

*** ** * ** ***

Κατ' ουσίαν τα περισσότερα φορμά e‑book εσωτερικά είναι μορφή ροής όπως το Office Open XML, όπου το περιεχόμενο είναι ενιαίο και διαχωρίζεται σε κεφάλαια αλλά όχι σε σελίδες. Ωστόσο, περιέχει κάποιες πληροφορίες ειδικές για τις σελίδες, όπως αριθμούς σελίδων, υποσημειώσεις, κεφαλίδες/υποσέλιδα κ.λπ. Ορισμένοι αναγνώστες e‑book πραγματοποιούν διαχωρισμό του περιεχομένου σε σελίδες, ενώ άλλοι (ιδιαίτερα οι κινητές συσκευές) \\u2014 όχι. Αυτή η επιλογή επιτρέπει τον έλεγχο του τρόπου που το περιεχόμενο του e‑book θα πρέπει να αναπαρίσταται σε HTML/CSS κατά την επεξεργασία \\u2014 σε ελεύθερη ( false ) ή σελιδοποιημένη ( true ) προβολή.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση της σελιδοποίησης στο τελικό έγγραφο HTML. Από προεπιλογή είναι απενεργοποιημένη (
false
).

<br />

*** ** * ** ***

Κατ' ουσίαν τα περισσότερα φορμά e‑book εσωτερικά είναι μορφή ροής όπως το Office Open XML, όπου το περιεχόμενο είναι ενιαίο και διαχωρίζεται σε κεφάλαια αλλά όχι σε σελίδες. Ωστόσο, περιέχει κάποιες πληροφορίες ειδικές για τις σελίδες, όπως αριθμούς σελίδων, υποσημειώσεις, κεφαλίδες/υποσέλιδα κ.λπ. Ορισμένοι αναγνώστες e‑book πραγματοποιούν διαχωρισμό του περιεχομένου σε σελίδες, ενώ άλλοι (ιδιαίτερα οι κινητές συσκευές) \\u2014 όχι. Αυτή η επιλογή επιτρέπει τον έλεγχο του τρόπου που το περιεχόμενο του e‑book θα πρέπει να αναπαρίσταται σε HTML/CSS κατά την επεξεργασία \\u2014 σε ελεύθερη ( false ) ή σελιδοποιημένη ( true ) προβολή.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο HTML markup με τη μορφή χαρακτηριστικών 'lang' HTML.
Αυτή η επιλογή μπορεί να είναι χρήσιμη για τη μετατροπή roundtrip των πολυγλωσσικών εγγράφων. Από προεπιλογή είναι απενεργοποιημένη (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Καθορίζει εάν οι πληροφορίες γλώσσας εξάγονται στο HTML markup με τη μορφή χαρακτηριστικών 'lang' HTML.
Αυτή η επιλογή μπορεί να είναι χρήσιμη για τη μετατροπή roundtrip των πολυγλωσσικών εγγράφων. Από προεπιλογή είναι απενεργοποιημένη (
false
).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |


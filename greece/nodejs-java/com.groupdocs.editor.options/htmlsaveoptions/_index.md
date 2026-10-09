---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την αποθήκευση της  instance σε μορφή HTML"
type: docs
weight: 19
url: /el/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την αποθήκευση του [EditableDocument](../../com.groupdocs.editor/editabledocument) instance σε μορφή HTML

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο HTML markup: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο HTML markup: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Καθορίζει ποιο διαχωριστικό γύρω από τις τιμές των χαρακτηριστικών σε στοιχεία HTML θα χρησιμοποιηθεί: μονό απόστροφο (προεπιλεγμένη τιμή) ή διπλό απόστροφο |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Καθορίζει ποιο διαχωριστικό γύρω από τις τιμές των χαρακτηριστικών σε στοιχεία HTML θα χρησιμοποιηθεί: μονό απόστροφο (προεπιλεγμένη τιμή) ή διπλό απόστροφο |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Καθορίζει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι ( |
false
), ή ενσωματώνονται στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
αληθές
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Καθορίζει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι ( |
false
), ή ενσωματώνονται στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
αληθές
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο HTML markup: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο HTML markup: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Καθορίζει ποιο διαχωριστικό γύρω από τις τιμές των χαρακτηριστικών σε στοιχεία HTML θα χρησιμοποιηθεί: μονό απόστροφο (προεπιλεγμένη τιμή) ή διπλό απόστροφο


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Καθορίζει ποιο διαχωριστικό γύρω από τις τιμές των χαρακτηριστικών σε στοιχεία HTML θα χρησιμοποιηθεί: μονό απόστροφο (προεπιλεγμένη τιμή) ή διπλό απόστροφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Καθορίζει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι (
false
), ή ενσωματώνονται στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
αληθές
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Καθορίζει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι (
false
), ή ενσωματώνονται στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
αληθές
)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |


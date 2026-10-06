---
title: "HtmlSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την αποθήκευση του αντικειμένου σε μορφή HTML"
type: docs
weight: 19
url: /el/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την αποθήκευση του [EditableDocument](../../com.groupdocs.editor/editabledocument) αντικειμένου σε μορφή HTML

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο σήμα HTML: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο σήμα HTML: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Ελέγχει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι ( |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Ελέγχει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι ( |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | ), ή ενσωματώστε τα στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD ( |
false
true
)
Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | ), ή ενσωματώστε τα στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD ( |
false
true
)
Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML
|
|  | [getSavingCallback()](#getSavingCallback--) | XmlHighlightOptions |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | XmlHighlightOptions |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο σήμα HTML: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Ελέγχει πώς θα εμφανίζονται τα ονόματα ετικετών HTML στο σήμα HTML: όλα πεζά (προεπιλεγμένη τιμή), όλα κεφαλαία ή το πρώτο γράμμα κεφαλαίο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Ελέγχει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι (


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Ελέγχει πού θα αποθηκευτούν τα φύλλα στυλ CSS: ως εξωτερικοί πόροι (


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


), ή ενσωματώστε τα στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
false
true
)
Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


), ή ενσωματώστε τα στο σήμα HTML, μέσα στο στοιχείο STYLE στην ενότητα HTML-\>HEAD (
false
true
)
Διεπαφή, η οποία πρέπει να υλοποιηθεί από τον τελικό χρήστη για την αποθήκευση όλων των εξωτερικών πόρων HTML


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


XmlHighlightOptions


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


XmlHighlightOptions


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |


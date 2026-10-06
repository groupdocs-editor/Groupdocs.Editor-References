---
title: "XmlEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων XML eXtensible Markup Language και τη μετατροπή τους σε HTML"
type: docs
weight: 51
url: /el/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση XML (eXtensible Markup Language)
εγγράφων και τη μετατροπή τους σε HTML

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
άνοιγμα.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το |
άνοιγμα.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση του μηχανισμού για τη διόρθωση κατεστραμμένης δομής XML. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Επιτρέπει την ενεργοποίηση ή απενεργοποίηση του μηχανισμού για τη διόρθωση κατεστραμμένης δομής XML. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης διευθύνσεων email σε χαρακτηριστικό |
τιμές
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης διευθύνσεων email σε χαρακτηριστικό |
τιμές
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Επιτρέπει την ενεργοποίηση της περικοπής των τελικών κενών χαρακτήρων στο εσωτερικό ετικέτας |
κείμενο.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Επιτρέπει την ενεργοποίηση της περικοπής των τελικών κενών χαρακτήρων στο εσωτερικό ετικέτας |
κείμενο.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Επιτρέπει τον καθορισμό του τύπου εισαγωγικών (μονά ή διπλά) για τις τιμές χαρακτηριστικού. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Επιτρέπει τον καθορισμό του τύπου εισαγωγικών (μονά ή διπλά) για τις τιμές χαρακτηριστικού. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Επιτρέπει την προσαρμογή της επισήμανσης XML, η οποία θα εφαρμοστεί στη δομή XML όταν εμφανίζεται σε HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Επιτρέπει την προσαρμογή της μορφοποίησης XML, η οποία θα εφαρμοστεί στη δομή XML όταν εμφανίζεται σε HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
άνοιγμα. Από προεπιλογή είναι null \\u2014 θα εφαρμοστεί η εσωτερική κωδικοποίηση εγγράφου.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Κωδικοποίηση χαρακτήρων του κειμενικού εγγράφου, η οποία θα εφαρμοστεί για το
άνοιγμα. Από προεπιλογή είναι null \\u2014 θα εφαρμοστεί η εσωτερική κωδικοποίηση εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση του μηχανισμού για τη διόρθωση κατεστραμμένης δομής XML.
Από προεπιλογή είναι απενεργοποιημένο (false).

*** ** * ** ***


Από προεπιλογή μόνο τα σωστά, έγκυρα, καλά δομημένα έγγραφα XML είναι
αποδεκτά. Όταν αυτή η επιλογή είναι ενεργοποιημένη, το GroupDocs.Editor θα προσπαθήσει να διορθώσει
τη κατεστραμμένη δομή XML αν είναι δυνατόν.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Επιτρέπει την ενεργοποίηση ή απενεργοποίηση του μηχανισμού για τη διόρθωση κατεστραμμένης δομής XML.
Από προεπιλογή είναι απενεργοποιημένο (false).

*** ** * ** ***


Από προεπιλογή μόνο τα σωστά, έγκυρα, καλά δομημένα έγγραφα XML είναι
αποδεκτά. Όταν αυτή η επιλογή είναι ενεργοποιημένη, το GroupDocs.Editor θα προσπαθήσει να διορθώσει
τη κατεστραμμένη δομή XML αν είναι δυνατόν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης URI


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης διευθύνσεων email σε χαρακτηριστικό
τιμές


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Επιτρέπει την ενεργοποίηση του αλγορίθμου αναγνώρισης διευθύνσεων email σε χαρακτηριστικό
τιμές


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Επιτρέπει την ενεργοποίηση της περικοπής των τελικών κενών χαρακτήρων στο εσωτερικό ετικέτας
κείμενο. Από προεπιλογή είναι απενεργοποιημένο (false) \\u2014 τα τελικά κενά θα είναι
διατηρημένα.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Επιτρέπει την ενεργοποίηση της περικοπής των τελικών κενών χαρακτήρων στο εσωτερικό ετικέτας
κείμενο. Από προεπιλογή είναι απενεργοποιημένο (false) \\u2014 τα τελικά κενά θα είναι
διατηρημένα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Επιτρέπει τον καθορισμό του τύπου εισαγωγικών (μονά ή διπλά) για τις τιμές χαρακτηριστικού. Τα διπλά εισαγωγικά είναι προεπιλογή.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Επιτρέπει τον καθορισμό του τύπου εισαγωγικών (μονά ή διπλά) για τις τιμές χαρακτηριστικού. Τα διπλά εισαγωγικά είναι προεπιλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Επιτρέπει την προσαρμογή της επισήμανσης XML, η οποία θα εφαρμοστεί στη δομή XML όταν εμφανίζεται σε HTML. Χρησιμοποιείται η προεπιλεγμένη επισήμανση και είναι ρυθμιζόμενη. Δεν μπορεί να είναι null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Επιτρέπει την προσαρμογή της μορφοποίησης XML, η οποία θα εφαρμοστεί στη δομή XML όταν εμφανίζεται σε HTML. Χρησιμοποιείται η προεπιλεγμένη μορφοποίηση και είναι ρυθμιζόμενη. Δεν μπορεί να είναι null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)

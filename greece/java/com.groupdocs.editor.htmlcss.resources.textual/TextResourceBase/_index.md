---
title: "TextResourceBase"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Βασική κλάση για οποιονδήποτε υποστηριζόμενο πόρο κειμένου με περιεχόμενο κειμένου και κωδικοποίηση."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Βασική κλάση για οποιονδήποτε υποστηριζόμενο πόρο κειμένου με περιεχόμενο κειμένου και κωδικοποίηση.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Δημιουργεί νέο πόρο κειμένου από το καθορισμένο κειμενικό περιεχόμενο με κωδικοποίηση |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Δημιουργεί νέο πόρο κειμένου από το καθορισμένο ρεύμα byte και κωδικοποίηση |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Disposed](#Disposed) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Επιστρέφει το όνομα αυτού του πόρου κειμένου χωρίς την επέκταση αρχείου |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Επιστρέφει το σωστό όνομα αρχείου αυτού του πόρου κειμένου, το οποίο αποτελείται από το όνομα |
και την επέκταση
|
|  | [getEncoding()](#getEncoding--) | Επιστρέφει την κωδικοποίηση αυτού του πόρου κειμένου. |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως ρεύμα byte με το αρχικό |
κωδικοποίηση
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως τυπική συμβολοσειρά |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτόν τον πόρο κειμένου στο καθορισμένο αρχείο |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτήν την παρουσία με το καθορισμένο για ισότητα. |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτόν τον πόρο κειμένου, αποδεσμεύοντας το περιεχόμενό του και κάνοντας το μεγαλύτερο μέρος |
μεθόδους και ιδιότητες μη λειτουργικές.
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν αυτός ο πόρος κειμένου είναι αποδεσμευμένος ή όχι |
|
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του κειμένου |
πόρος
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Δημιουργεί νέο πόρο κειμένου από το καθορισμένο κειμενικό περιεχόμενο με κωδικοποίηση


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Υποχρεωτικό όνομα του πόρου, που λειτουργεί ως μοναδικό αναγνωριστικό του. Συνήθως είναι ένα όνομα αρχείου. |
|
|  | textualContent | java.lang.String | Κειμενικό περιεχόμενο του πόρου, δεν μπορεί να είναι NULL ή κενό |
|
|  | originalEncoding | java.nio.charset.Charset | Αρχική κωδικοποίηση του πόρου, δεν μπορεί να είναι NULL ή κενό |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Δημιουργεί νέο πόρο κειμένου από το καθορισμένο ρεύμα byte και κωδικοποίηση


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Υποχρεωτικό όνομα του πόρου, που λειτουργεί ως μοναδικό αναγνωριστικό του. Συνήθως είναι ένα όνομα αρχείου. |
|
|  | binaryContent | java.io.InputStream | Δυαδικό περιεχόμενο ενός πόρου ως ροή byte. Δεν μπορεί να είναι NULL, αποδεσμευμένο, πρέπει να είναι αναγνώσιμο και αναζητήσιμο. |
|
|  | originalEncoding | java.nio.charset.Charset | Αρχική κωδικοποίηση του πόρου, δεν μπορεί να είναι NULL ή κενό |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα αυτού του πόρου κειμένου χωρίς την επέκταση αρχείου


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Επιστρέφει το σωστό όνομα αρχείου αυτού του πόρου κειμένου, το οποίο αποτελείται από το όνομα
και την επέκταση


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Επιστρέφει την κωδικοποίηση αυτού του κειμενικού πόρου. Συνήθως επιστρέφει UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως ρεύμα byte με το αρχικό
κωδικοποίηση


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως τυπική συμβολοσειρά


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Αποθηκεύει αυτόν τον πόρο κειμένου στο καθορισμένο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί ή θα ξαναγραφεί εάν υπάρχει ήδη |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Ελέγχει αυτήν την παρουσία με το καθορισμένο για ισότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλος πόρος HTML άγνωστου τύπου, που είναι επίσης πιθανός κληρονόμος του TextResourceBase |
|

**Returns:**
boolean - Επιστρέφει true εάν είναι ίσα, ή false εάν είναι διαφορετικά

### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει αυτόν τον πόρο κειμένου, αποδεσμεύοντας το περιεχόμενό του και κάνοντας το μεγαλύτερο μέρος
μεθόδους και ιδιότητες μη λειτουργικές. Ανθεκτικό σε πολλαπλές κλήσεις.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Καθορίζει εάν αυτός ο πόρος κειμένου είναι αποδεσμευμένος ή όχι


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του κειμένου
πόρος


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)

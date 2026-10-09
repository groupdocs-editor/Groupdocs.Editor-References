---
title: "TextResourceBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Βασική κλάση για οποιονδήποτε υποστηριζόμενο πόρο κειμένου με περιεχόμενο κειμένου και κωδικοποίηση."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
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
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Δημιουργεί νέο πόρο κειμένου από καθορισμένη ροή byte και κωδικοποίηση |
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
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως ροή byte με την αρχική |
κωδικοποίηση
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως τυπική συμβολοσειρά |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτόν τον πόρο κειμένου στο καθορισμένο αρχείο |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα. |
|
|  | [dispose()](#dispose--) | Καταστρέφει αυτόν τον πόρο κειμένου, καταστρέφοντας το περιεχόμενό του και καθιστώντας τις περισσότερες |
μεθόδους και ιδιότητες μη λειτουργικές.
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει αν αυτός ο πόρος κειμένου έχει καταστραφεί ή όχι |
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
|  | name | java.lang.String | Υποχρεωτικό όνομα του πόρου, που λειτουργεί ως μοναδικό του αναγνωριστικό. Συνήθως είναι όνομα αρχείου. |
|
|  | textualContent | java.lang.String | Περιεχόμενο κειμένου του πόρου, δεν μπορεί να είναι NULL ή κενό |
|
|  | originalEncoding | java.nio.charset.Charset | Αρχική κωδικοποίηση του πόρου, δεν μπορεί να είναι NULL ή κενό |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Δημιουργεί νέο πόρο κειμένου από καθορισμένη ροή byte και κωδικοποίηση


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Υποχρεωτικό όνομα του πόρου, που λειτουργεί ως μοναδικό του αναγνωριστικό. Συνήθως είναι όνομα αρχείου. |
|
|  | binaryContent | java.io.InputStream | Δυαδικό περιεχόμενο ενός πόρου ως ροή byte. Δεν μπορεί να είναι NULL, καταστραμμένο, πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. |
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


Επιστρέφει την κωδικοποίηση αυτού του πόρου κειμένου. Συνήθως επιστρέφει UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτού του πόρου κειμένου ως ροή byte με την αρχική
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
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή του αρχείου, η οποία θα δημιουργηθεί ή θα ξαναγραφεί εάν υπάρχει ήδη |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλος πόρος HTML άγνωστου τύπου, που είναι επίσης πιθανός κληρονόμος του TextResourceBase |
|

**Returns:**
boolean - Επιστρέφει true εάν είναι ίσα, ή false εάν δεν είναι ίσα

### dispose() {#dispose--}
```
public final void dispose()
```


Καταστρέφει αυτόν τον πόρο κειμένου, καταστρέφοντας το περιεχόμενό του και καθιστώντας τις περισσότερες
μέθοδοι και ιδιότητες δεν λειτουργούν. Ανθεκτικό σε πολλαπλές κλήσεις.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Καθορίζει αν αυτός ο πόρος κειμένου έχει καταστραφεί ή όχι


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

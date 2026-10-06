---
title: "FontResourceBase"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Βασική κλάση για οποιονδήποτε υποστηριζόμενο τύπο γραμματοσειράς ως πόρο για το έγγραφο HTML με όλες τις ιδιότητές του"
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Βασική κλάση για οποιονδήποτε υποστηριζόμενο τύπο γραμματοσειράς ως πόρο για το έγγραφο HTML
με όλες τις ιδιότητές του

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Disposed](#Disposed) | Γεγονός, που συμβαίνει όταν αυτή η γραμματοσειρά διαγραφεί |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Επιστρέφει το όνομα αυτού του πόρου γραμματοσειράς. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Επιστρέφει το σωστό όνομα αρχείου αυτού του πόρου γραμματοσειράς, το οποίο αποτελείται από το όνομα |
και την επέκταση.
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως ροή byte |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως συμβολοσειρά κωδικοποιημένη σε base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτή τη γραμματοσειρά στο καθορισμένο αρχείο |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο HTML για ισότητα αναφοράς |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο γραμματοσειράς για ισότητα αναφοράς |
|
|  | [dispose()](#dispose--) | Καταστρέφει αυτόν τον πόρο γραμματοσειράς, καταστρέφοντας το περιεχόμενό του και κάνοντας το μεγαλύτερο μέρος |
μεθόδους και ιδιότητες μη λειτουργικές
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν αυτή η γραμματοσειρά έχει καταστραφεί ή όχι |
|
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του συγκεκριμένου |
πόρου γραμματοσειράς ως μια παρουσία του συγκεκριμένου τύπου FontType, που
περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Γεγονός, που συμβαίνει όταν αυτή η γραμματοσειρά διαγραφεί


### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα αυτού του πόρου γραμματοσειράς. Συνήθως δεν περιέχει όνομα αρχείου
η επέκταση και θεωρητικά μπορεί να διαφέρει από το όνομα αρχείου.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Επιστρέφει το σωστό όνομα αρχείου αυτού του πόρου γραμματοσειράς, το οποίο αποτελείται από το όνομα
και την επέκταση. Θεωρητικά μπορεί να διαφέρει από το όνομα.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως ροή byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτής της γραμματοσειράς ως συμβολοσειρά κωδικοποιημένη σε base64. Αυτή η τιμή είναι
αποθηκευμένη στην κρυφή μνήμη μετά την πρώτη κλήση.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Αποθηκεύει αυτή τη γραμματοσειρά στο καθορισμένο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί ή ξαναγραφεί |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο HTML για ισότητα αναφοράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλος κληρονόμος της διεπαφής IHtmlResource |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Ελέγχει αυτήν την παρουσία με τον καθορισμένο πόρο γραμματοσειράς για ισότητα αναφοράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Άλλος κληρονόμος της αφηρημένης κλάσης FontResourceBase |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### dispose() {#dispose--}
```
public final void dispose()
```


Καταστρέφει αυτόν τον πόρο γραμματοσειράς, καταστρέφοντας το περιεχόμενό του και κάνοντας το μεγαλύτερο μέρος
μεθόδους και ιδιότητες μη λειτουργικές


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Καθορίζει εάν αυτή η γραμματοσειρά έχει καταστραφεί ή όχι


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του συγκεκριμένου
πόρου γραμματοσειράς ως μια παρουσία του συγκεκριμένου τύπου FontType, που
περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)

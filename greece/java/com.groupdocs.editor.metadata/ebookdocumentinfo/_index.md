---
title: "EbookDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου EBook"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου EBook

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων στην περίπτωση MOBI ή AZW3 ή τον αριθμό των κεφαλαίων στην περίπτωση ePub. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου eBook. |
|
|  | [isEncrypted()](#isEncrypted--) | Επειδή τα έγγραφα eBook δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτή η ιδιότητα πάντα επιστρέφει 'false'. |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσία EbookDocumentInfo. |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει τον αριθμό των σελίδων στην περίπτωση MOBI ή AZW3 ή τον αριθμό των κεφαλαίων στην περίπτωση ePub.

<br />

*** ** * ** ***

Τα έγγραφα eBook συνήθως δεν έχουν σταθερές σελίδες και συνεπώς αριθμό σελίδων. Στην περίπτωση ePub είναι δυνατόν να υπολογιστεί ο αριθμός των κεφαλαίων. Ωστόσο, οι μορφές MOBI και AZW3 δεν έχουν επίσης κεφάλαια, έτσι αυτός ο αριθμός υπολογίζεται από το τυπικό μέγεθος σελίδας ορισμένο σε A4 σε πορτραίτο προσανατολισμό.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου eBook.


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Επειδή τα έγγραφα eBook δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτή η ιδιότητα πάντα επιστρέφει 'false'.


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσία EbookDocumentInfo.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Άλλη παρουσία EbookDocumentInfo, η οποία πρέπει να ελεγχθεί για ισότητα με αυτήν. |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες


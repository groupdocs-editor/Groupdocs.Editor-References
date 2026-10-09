---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου EBook"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
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
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων σε περίπτωση MOBI ή AZW3 ή τον αριθμό των κεφαλαίων σε περίπτωση ePub. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου eBook |
|
|  | [isEncrypted()](#isEncrypted--) | Επειδή τα έγγραφα eBook δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτή η ιδιότητα πάντα επιστρέφει 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Καθορίζει αν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσία EbookDocumentInfo |
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


Επιστρέφει τον αριθμό των σελίδων σε περίπτωση MOBI ή AZW3 ή τον αριθμό των κεφαλαίων σε περίπτωση ePub.

<br />

*** ** * ** ***

Τα έγγραφα eBook συνήθως δεν έχουν σταθερές σελίδες και επομένως δεν υπάρχει αριθμός σελίδων. Σε περίπτωση ePub είναι δυνατόν να υπολογιστεί ο αριθμός των κεφαλαίων. Ωστόσο, οι μορφές MOBι και AZW3 επίσης δεν έχουν κεφάλαια, έτσι αυτός ο αριθμός υπολογίζεται από το τυπικό μέγεθος σελίδας ορισμένο σε A4 σε κατακόρυφη προσανατολισμό.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου eBook


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Επειδή τα έγγραφα eBook δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτή η ιδιότητα πάντα επιστρέφει 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Καθορίζει αν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσία EbookDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Άλλη παρουσία EbookDocumentInfo, που πρέπει να ελεγχθεί για ισότητα με αυτήν |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά


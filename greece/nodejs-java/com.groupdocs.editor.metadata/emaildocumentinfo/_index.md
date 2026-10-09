---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου email οποιασδήποτε υποστηριζόμενης μορφής email"
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου email οποιασδήποτε υποστηριζόμενης μορφής email

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει τη μορφή αυτού του εγγράφου email |
|
|  | [getPageCount()](#getPageCount--) | Πάντα επιστρέφει 1, επειδή τα έγγραφα email δεν έχουν προβολή σε σελίδες |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου email |
|
|  | [isEncrypted()](#isEncrypted--) | Επειδή τα έγγραφα email δεν μπορούν να κρυπτογραφηθούν με κωδικό πρόσβασης, αυτή η ιδιότητα πάντα επιστρέφει 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το άλλο καθορισμένο αντικείμενο EmailDocumentInfo |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει τη μορφή αυτού του εγγράφου email


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Πάντα επιστρέφει 1, επειδή τα έγγραφα email δεν έχουν προβολή σε σελίδες


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου email


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Επειδή τα έγγραφα email δεν μπορούν να κρυπτογραφηθούν με κωδικό πρόσβασης, αυτή η ιδιότητα πάντα επιστρέφει 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το άλλο καθορισμένο αντικείμενο EmailDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Άλλο αντικείμενο EmailDocumentInfo, το οποίο θα πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά


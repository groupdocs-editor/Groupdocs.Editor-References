---
title: "WordProcessingDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου WordProcessing"
type: docs
weight: 17
url: /el/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου WordProcessing

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο WordProcessing είναι κρυπτογραφημένο και |
απαιτεί κωδικό πρόσβασης για άνοιγμα
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης σελίδας με μορφή εικόνας SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
αντίγραφο WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει τον αριθμό των σελίδων


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο WordProcessing είναι κρυπτογραφημένο και
απαιτεί κωδικό πρόσβασης για άνοιγμα


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης σελίδας με μορφή εικόνας SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageIndex | int | Δείκτης 0‑βάσης της επιθυμητής σελίδας. Δεν μπορεί να είναι μικρότερος από 0, δεν μπορεί να υπερβαίνει τον αριθμό των σελίδων σε αυτό το έγγραφο WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται
αντίγραφο WordProcessingDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Άλλο αντίγραφο WordProcessingDocumentInfo, που πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες


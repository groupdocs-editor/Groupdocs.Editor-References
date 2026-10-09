---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Επεξεργασίας Κειμένου"
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Επεξεργασίας Κειμένου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει τη μορφή αυτού του εγγράφου WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο WordProcessing είναι κρυπτογραφημένο και |
απαιτεί κωδικό πρόσβασης για άνοιγμα
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης σελίδας σε μορφή εικόνας SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
αντικείμενο WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Επιστρέφει τη μορφή αυτού του εγγράφου WordProcessing


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


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου WordProcessing


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


Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης σελίδας σε μορφή εικόνας SVG


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
αντικείμενο WordProcessingDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Άλλο αντικείμενο WordProcessingDocumentInfo, το οποίο θα πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά


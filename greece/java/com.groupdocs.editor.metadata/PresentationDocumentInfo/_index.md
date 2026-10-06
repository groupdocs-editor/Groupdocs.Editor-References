---
title: "PresentationDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Presentation"
type: docs
weight: 14
url: /el/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Presentation

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μορφή αυτού του εγγράφου Presentation |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει αριθμό διαφανειών σε αυτό το έγγραφο Presentation |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Presentation είναι κρυπτογραφημένο και απαιτεί κωδικό για το άνοιγμα |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης διαφάνειας σε μορφή εικόνας SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Επιστρέφει μορφή αυτού του εγγράφου Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει αριθμό διαφανειών σε αυτό το έγγραφο Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Presentation είναι κρυπτογραφημένο και απαιτεί κωδικό για το άνοιγμα


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης διαφάνειας σε μορφή εικόνας SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | slideIndex | int | Δείκτης βάσει 0 της επιθυμητής διαφάνειας. Δεν μπορεί να είναι μικρότερος από 0, δεν μπορεί να υπερβεί τον αριθμό των διαφανειών σε αυτήν την παρουσίαση. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class


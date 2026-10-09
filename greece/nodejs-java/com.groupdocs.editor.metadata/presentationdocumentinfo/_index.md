---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Παρουσίασης"
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Παρουσίασης

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου Presentation |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των διαφανειών σε αυτό το έγγραφο Presentation |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Presentation είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης διαφάνειας σε μορφή εικόνας SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει τον αριθμό των διαφανειών σε αυτό το έγγραφο Presentation


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


Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Presentation είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα


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
|  | slideIndex | int | Δείκτης βάσει 0 του επιθυμητού slide. Δεν μπορεί να είναι μικρότερος από 0, δεν μπορεί να υπερβαίνει τον αριθμό των slides σε αυτήν την παρουσίαση. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class


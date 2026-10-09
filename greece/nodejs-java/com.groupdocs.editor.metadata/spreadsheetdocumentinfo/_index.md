---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Φύλλου Εργασίας"
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Φύλλου Εργασίας

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου Spreadsheet |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των καρτελών |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Spreadsheet |
|
|  | [isEncrypted()](#isEncrypted--) | Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Spreadsheet είναι κρυπτογραφημένο και |
απαιτεί κωδικό πρόσβασης για άνοιγμα
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση του επιλεγμένου φύλλου εργασίας σε μορφή εικόνας SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
Παράδειγμα SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου Spreadsheet


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει τον αριθμό των καρτελών


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Spreadsheet


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Δείχνει εάν αυτό το συγκεκριμένο έγγραφο Spreadsheet είναι κρυπτογραφημένο και
απαιτεί κωδικό πρόσβασης για άνοιγμα


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Δημιουργεί και επιστρέφει μια προεπισκόπηση του επιλεγμένου φύλλου εργασίας σε μορφή εικόνας SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | worksheetIndex | int | Δείκτης βάσει 0 του επιθυμητού worksheet. Δεν μπορεί να είναι μικρότερος από 0, δεν μπορεί να υπερβαίνει τον αριθμό των worksheets σε αυτό το spreadsheet. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται
Παράδειγμα SpreadsheetDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Άλλο αντικείμενο SpreadsheetDocumentInfo, το οποίο θα πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά


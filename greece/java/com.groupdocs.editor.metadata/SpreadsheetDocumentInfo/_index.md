---
title: "SpreadsheetDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Spreadsheet"
type: docs
weight: 15
url: /el/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Spreadsheet

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του Spreadsheet εγγράφου |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των καρτελών |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του Spreadsheet εγγράφου |
|
|  | [isEncrypted()](#isEncrypted--) | Δείχνει αν αυτό το συγκεκριμένο Spreadsheet έγγραφο είναι κρυπτογραφημένο και |
απαιτεί κωδικό πρόσβασης για άνοιγμα
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Δημιουργεί και επιστρέφει μια προεπισκόπηση του επιλεγμένου φύλλου εργασίας σε μορφή εικόνας SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
SpreadsheetDocumentInfo αντίγραφο
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Επιστρέφει μια μορφή αυτού του Spreadsheet εγγράφου


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


Επιστρέφει το μέγεθος σε bytes αυτού του Spreadsheet εγγράφου


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Δείχνει αν αυτό το συγκεκριμένο Spreadsheet έγγραφο είναι κρυπτογραφημένο και
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
|  | worksheetIndex | int | Δείκτης βάσει 0 του επιθυμητού φύλλου εργασίας. Δεν μπορεί να είναι μικρότερος από 0, δεν μπορεί να υπερβεί τον αριθμό των φύλλων εργασίας σε αυτό το spreadsheet. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται
SpreadsheetDocumentInfo αντίγραφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Άλλο SpreadsheetDocumentInfo αντίγραφο, που πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες


---
title: "FixedLayoutDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου με μορφή σταθερής διάταξης όπως PDF ή XPS"
type: docs
weight: 12
url: /el/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου με μορφή σταθερής διάταξης όπως PDF ή XPS

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου σταθερής διάταξης |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου σταθερής διάταξης |
|
|  | [isEncrypted()](#isEncrypted--) | Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο σταθερής διάταξης είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Καθορίζει εάν αυτό το αντίγραφο είναι ίσο με το άλλο καθορισμένο αντίγραφο FixedLayoutDocumentInfo |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου σταθερής διάταξης


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Επιστρέφει το μέγεθος σε byte αυτού του εγγράφου σταθερής διάταξης


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο σταθερής διάταξης είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Καθορίζει εάν αυτό το αντίγραφο είναι ίσο με το άλλο καθορισμένο αντίγραφο FixedLayoutDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Άλλο αντίγραφο FixedLayoutDocumentInfo, που πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες


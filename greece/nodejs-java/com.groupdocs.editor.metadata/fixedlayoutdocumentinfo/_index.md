---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου με μορφή σταθερής διάταξης όπως PDF ή XPS"
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
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
|  | [getFormat()](#getFormat--) | Επιστρέφει τη μορφή αυτού του εγγράφου fixed-layout |
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου fixed-layout |
|
|  | [isEncrypted()](#isEncrypted--) | Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο fixed-layout είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για το άνοιγμα |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το άλλο καθορισμένο αντικείμενο FixedLayoutDocumentInfo |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει τη μορφή αυτού του εγγράφου fixed-layout


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


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου fixed-layout


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Καθορίζει εάν αυτό το συγκεκριμένο έγγραφο fixed-layout είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για το άνοιγμα


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το άλλο καθορισμένο αντικείμενο FixedLayoutDocumentInfo


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Άλλο αντικείμενο FixedLayoutDocumentInfo, το οποίο θα πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά


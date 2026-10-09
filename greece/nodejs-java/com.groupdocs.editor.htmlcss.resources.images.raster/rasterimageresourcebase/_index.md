---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Βασική κλάση για οποιαδήποτε υποστηριζόμενη raster εικόνα με σταθερό όνομα, διαστάσεις, λόγο διαστάσεων, τύπο, μέγεθος και περιεχόμενο."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Βασική κλάση για οποιαδήποτε υποστηριζόμενη raster εικόνα με σταθερό όνομα, διαστάσεις, λόγο
λόγο, τύπο, μέγεθος και περιεχόμενο.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Disposed](#Disposed) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Επιστρέφει το όνομα αυτής της raster εικόνας. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Επιστρέφει το σωστό όνομα αρχείου αυτής της raster εικόνας, το οποίο αποτελείται από το όνομα και |
επέκταση.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Επιστρέφει τις γραμμικές διαστάσεις αυτής της raster εικόνας (πλάτος και ύψος) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Επιστρέφει το λόγο διαστάσεων αυτής της εικόνας ως σχέση πλάτος προς ύψος |
|
|  | [getLength()](#getLength--) | Επιστρέφει το μήκος αυτού του αρχείου raster εικόνας σε bytes |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της raster εικόνας ως ροή byte |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της raster εικόνας ως συμβολοσειρά κωδικοποιημένη σε base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτή τη raster εικόνα στο καθορισμένο αρχείο |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα αναφοράς. |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτή τη raster εικόνα, απελευθερώνοντας το περιεχόμενό της και καθιστώντας τις περισσότερες μεθόδους |
και τις ιδιότητες μη λειτουργικές
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν αυτή η ραστική εικόνα έχει διαγραφεί ή όχι |
|
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο της ραστικής εικόνας |
εικόνα
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα αυτής της ραστικής εικόνας. Συνήθως δεν περιέχει όνομα αρχείου
επέκταση και θεωρητικά μπορεί να διαφέρει από το όνομα αρχείου.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Επιστρέφει το σωστό όνομα αρχείου αυτής της raster εικόνας, το οποίο αποτελείται από το όνομα και
επέκταση. Θεωρητικά μπορεί να διαφέρει από το όνομα.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Επιστρέφει τις γραμμικές διαστάσεις αυτής της raster εικόνας (πλάτος και ύψος)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Επιστρέφει το λόγο διαστάσεων αυτής της εικόνας ως σχέση πλάτος προς ύψος


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Επιστρέφει το μήκος αυτού του αρχείου raster εικόνας σε bytes


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της raster εικόνας ως ροή byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτής της raster εικόνας ως συμβολοσειρά κωδικοποιημένη σε base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Αποθηκεύει αυτή τη raster εικόνα στο καθορισμένο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί ή θα ξαναγραφεί |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα αναφοράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλος κληρονόμος του IHtmlResource |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει αυτή τη raster εικόνα, απελευθερώνοντας το περιεχόμενό της και καθιστώντας τις περισσότερες μεθόδους
και τις ιδιότητες μη λειτουργικές


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Καθορίζει εάν αυτή η ραστική εικόνα έχει διαγραφεί ή όχι


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο της ραστικής εικόνας
εικόνα


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 

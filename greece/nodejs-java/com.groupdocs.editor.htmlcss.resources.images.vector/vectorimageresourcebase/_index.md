---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Βασική κλάση για οποιαδήποτε υποστηριζόμενη διανυσματική εικόνα."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Βασική κλάση για οποιαδήποτε υποστηριζόμενη διανυσματική εικόνα.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Disposed](#Disposed) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Επιστρέφει το όνομα αυτής της διανυσματικής εικόνας. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Επιστρέφει το σωστό όνομα αρχείου αυτής της διανυσματικής εικόνας, το οποίο αποτελείται από το όνομα και |
επέκταση.
|
|  | [getAspectRatio()](#getAspectRatio--) | Επιστρέφει την αναλογία διαστάσεων αυτής της διανυσματικής εικόνας |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Επιστρέφει τις γραμμικές διαστάσεις αυτής της διανυσματικής εικόνας (πλάτος και ύψος) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα αναφοράς. |
|
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν αυτή η ραστική εικόνα έχει διαγραφεί ή όχι |
|
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του διανύσματος |
εικόνα
|
|  | [getByteContent()](#getByteContent--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει το περιεχόμενο αυτής της διανυσματικής εικόνας ως byte |
ροή
|
|  | [getTextContent()](#getTextContent--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει το περιεχόμενο αυτής της διανυσματικής εικόνας σε κείμενο |
μορφή: κωδικοποιημένο base64 του XML σχετικά με τον τύπο της εικόνας
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύει αυτή την εικόνα στο δίσκο στη συγκεκριμένη διαδρομή |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύει την τρέχουσα διανυσματική εικόνα σε raster PNG |
μορφοποίηση σε καθορισμένη ροή byte
|
|  | [dispose()](#dispose--) | Στην υλοποίηση, ο τύπος πρέπει να απελευθερώνει αυτή την παρουσία |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα αυτής της διανυσματικής εικόνας. Συνήθως δεν περιέχει όνομα αρχείου
επέκταση και θεωρητικά μπορεί να διαφέρει από το όνομα αρχείου.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Επιστρέφει το σωστό όνομα αρχείου αυτής της διανυσματικής εικόνας, το οποίο αποτελείται από το όνομα και
επέκταση. Θεωρητικά μπορεί να διαφέρει από το όνομα.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Επιστρέφει την αναλογία διαστάσεων αυτής της διανυσματικής εικόνας


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Επιστρέφει τις γραμμικές διαστάσεις αυτής της διανυσματικής εικόνας (πλάτος και ύψος)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Ελέγχει αυτό το αντικείμενο με το καθορισμένο για ισότητα αναφοράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Άλλη παρουσία διανυσματικής εικόνας |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

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


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει πληροφορίες σχετικά με τον τύπο του διανύσματος
εικόνα


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει το περιεχόμενο αυτής της διανυσματικής εικόνας ως byte
ροή


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει το περιεχόμενο αυτής της διανυσματικής εικόνας σε κείμενο
μορφή: κωδικοποιημένο base64 του XML σχετικά με τον τύπο της εικόνας


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύει αυτή την εικόνα στο δίσκο στη συγκεκριμένη διαδρομή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύει την τρέχουσα διανυσματική εικόνα σε raster PNG
μορφοποίηση σε καθορισμένη ροή byte


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ροή byte, στην οποία θα αποθηκευτεί η έκδοση PNG αυτής της raster εικόνας. Δεν πρέπει να είναι NULL και πρέπει να υποστηρίζει εγγραφή. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Στην υλοποίηση, ο τύπος πρέπει να απελευθερώνει αυτή την παρουσία



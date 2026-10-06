---
title: "IImageResource"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει πόρο εικόνας οποιουδήποτε τύπου, raster ή vector"
type: docs
weight: 13
url: /el/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Αντιπροσωπεύει πόρο εικόνας οποιουδήποτε τύπου, ραστερικό ή διανυσματικό.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει έναν τύπο συγκεκριμένης εικόνας ως |
παρουσία συγκεκριμένου ImageType, η οποία περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο
|
|  | [getAspectRatio()](#getAspectRatio--) | Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει την αναλογία διαστάσεων μιας συγκεκριμένης εικόνας |
ανεξαρτήτως του τύπου της.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει τις γραμμικές διαστάσεις της εικόνας. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει έναν τύπο συγκεκριμένης εικόνας ως
παρουσία συγκεκριμένου ImageType, η οποία περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει την αναλογία διαστάσεων μιας συγκεκριμένης εικόνας
ανεξαρτήτως του τύπου της. Και οι εικόνες vector και raster έχουν ενδογενείς
αναλογία διαστάσεων μεταξύ του πλάτους και του ύψους.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Στην υλοποίηση, ο τύπος θα πρέπει να επιστρέφει τις γραμμικές διαστάσεις της εικόνας. Για
τις εικόνες raster είναι ενδογενείς διαστάσεις σε εικονοστοιχεία. Οι εικόνες vector, σε
αντίστοιχο, δεν έχουν σταθερές διαστάσεις, αλλά τα μεταδεδομένα τους μπορούν να περιέχουν
ορισμένες βασικές διαστάσεις σε διαφορετικές μονάδες μέτρησης.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 

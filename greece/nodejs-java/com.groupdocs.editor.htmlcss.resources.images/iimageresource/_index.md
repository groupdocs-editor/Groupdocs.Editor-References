---
title: "IImageResource"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά πόρο εικόνας οποιουδήποτε τύπου raster ή vector"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
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
|  | [getType()](#getType--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει έναν τύπο συγκεκριμένης εικόνας ως |
αντίγραφο του συγκεκριμένου ImageType, το οποίο περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο
|
|  | [getAspectRatio()](#getAspectRatio--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει μια αναλογία διαστάσεων μιας συγκεκριμένης εικόνας |
ανεξαρτήτως του τύπου της.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει τις γραμμικές διαστάσεις της εικόνας. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει έναν τύπο συγκεκριμένης εικόνας ως
αντίγραφο του συγκεκριμένου ImageType, το οποίο περιλαμβάνει όλες τις πληροφορίες ειδικές για τον τύπο


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει μια αναλογία διαστάσεων μιας συγκεκριμένης εικόνας
ανεξαρτήτως του τύπου της. Τόσο οι vector όσο και οι raster εικόνες έχουν ενδογενή
αναλογία διαστάσεων μεταξύ του πλάτους και του ύψους της.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Στην υλοποίηση, ο τύπος πρέπει να επιστρέφει τις γραμμικές διαστάσεις της εικόνας. Για
οι raster εικόνες είναι ενδογενείς διαστάσεις σε pixel. Οι vector εικόνες, σε
αντίθετη περίπτωση, δεν έχουν σταθερές διαστάσεις, αλλά τα μεταδεδομένα τους μπορούν να περιέχουν
ορισμένες βασικές διαστάσεις σε διαφορετικές μονάδες μέτρησης.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
